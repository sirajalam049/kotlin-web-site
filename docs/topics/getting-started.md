[//]: # (title: Get started with Kotlin)

Kotlin is a modern but already mature programming language designed to make developers happier.
It's concise, safe, interoperable with Java and other languages, and provides many ways to reuse code between multiple platforms for productive programming.

To start, why not take our tour of Kotlin? This tour covers the fundamentals of the Kotlin programming language.

<a href="kotlin-tour-hello-world.md"><img src="start-kotlin-tour.svg" width="700" alt="Start the Kotlin tour"/></a>

## Install Kotlin

Kotlin is included in each [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) and [Android Studio](https://developer.android.com/studio) release.
Download and install one of these IDEs to start using Kotlin.

## Create your powerful application with Kotlin
 
<tabs>

<tab id="backend" title="Backend app">

Here is how you can take the first steps in developing Kotlin server-side applications.

1. **Create your first backend application:**
   
   * To start from scratch, [create a basic JVM application with the IntelliJ IDEA project wizard](jvm-get-started.md).
   * If you prefer more robust examples, choose one of the frameworks below and create a project:

   <table width="100%" >
   <tr>
      <th>Spring</th>
      <th>Ktor</th>
   </tr>
   <tr>
   <td width="50%">
     A mature family of frameworks with an established ecosystem that is used by millions of developers worldwide.
   <br/>
   <list>
      <li><a href="jvm-get-started-spring-boot.md">Create a RESTful web service with Spring Boot</a>.</li>
      <li><a href="https://spring.io/guides/tutorials/spring-boot-kotlin/">Build web applications with Spring Boot and Kotlin</a>.</li>
      <li><a href="https://spring.io/guides/tutorials/spring-webflux-kotlin-rsocket/">Use Spring Boot with Kotlin and RSocket</a>.</li>
   </list>
   </td>
   <td width="50%">
      A lightweight framework for those who value freedom in making architectural decisions.
   <list>
      <li><a href="https://ktor.io/docs/creating-http-apis.html">Create HTTP APIs with Ktor</a>.</li>
      <li><a href="https://ktor.io/docs/creating-web-socket-chat.html">Create a WebSocket chat with Ktor</a>.</li>
      <li><a href="https://ktor.io/docs/creating-interactive-website.html">Create an interactive website with Ktor</a>.</li>
      <li><a href="https://ktor.io/docs/heroku.html">Publish server-side Kotlin applications: Ktor on Heroku</a>.</li>
   </list>
   
   </td>
   </tr>
   </table>

2. **Use Kotlin and third-party libraries in your application**. Learn more about [adding library and tool dependencies to your project](gradle-configure-project.md#configure-dependencies).
   * The [Kotlin standard library](https://kotlinlang.org/api/latest/jvm/stdlib/) offers a lot of useful things such as [collections](collections-overview.md) or [coroutines](coroutines-guide.md).
   * Take a look at the following [third-party frameworks, libs and tools for Kotlin](https://blog.jetbrains.com/kotlin/2020/11/server-side-development-with-kotlin-frameworks-and-libraries/).

3. **Learn more about Kotlin for server-side:**
   * [How to write your first unit test](jvm-test-using-junit.md).
   * [How to mix Kotlin and Java code in your application](mixing-java-kotlin-intellij.md).

4. **Join the Kotlin server-side community:**
   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA), [#server](https://kotlinlang.slack.com/archives/C0B8RC352), [#spring](https://kotlinlang.slack.com/archives/C0B8ZTWE4), or [#ktor](https://kotlinlang.slack.com/archives/C0A974TJ9) channels.
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: subscribe to the ["kotlin"](https://stackoverflow.com/questions/tagged/kotlin), ["spring-kotlin"](https://stackoverflow.com/questions/tagged/spring-kotlin), or ["ktor"](https://stackoverflow.com/questions/tagged/ktor) tags.

5. **Follow Kotlin** on ![Twitter](twitter.svg){width=25}{type="joined"} [Twitter](https://twitter.com/kotlin), ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

<tab id="cross-platform-mobile" title="Cross-platform mobile app">

Here you'll learn how to develop and improve your cross-platform mobile application using [Kotlin Multiplatform](https://kotlinlang.org/lp/multiplatform/).

1. **[Set up your environment for cross-platform mobile development](multiplatform-mobile-setup.md).**

2. **Create your first application for iOS and Android:**

   * To start from scratch, [create a basic cross-platform mobile application with the project wizard](multiplatform-mobile-create-first-app.md).
   * If you have an existing Android application and want to make it cross-platform, complete the [Make your Android application work on iOS](multiplatform-mobile-integrate-in-existing-app.md) tutorial.
   * If you prefer real-life examples, clone and play with an existing project, for example the networking and data storage project from the [Create a multiplatform app using Ktor and SQLdelight](multiplatform-mobile-ktor-sqldelight.md) tutorial or any [sample project](multiplatform-mobile-samples.md).

3. **Use a wide set of multiplatform libraries** to implement the required business logic only once in the shared module. Learn more about [adding dependencies](multiplatform-add-dependencies.md).

   |Library|Details|
   |-------|-------| 
   | Ktor | [Docs](https://ktor.io/docs/client.html)| 
   | Serialization | [Docs](serialization.md) and [sample](multiplatform-mobile-ktor-sqldelight.md#create-an-application-data-model)|
   | Coroutines | [Docs](coroutines-guide.md) and [sample](coroutines-and-channels.md)|
   | DateTime | [Docs](https://github.com/Kotlin/kotlinx-datetime#readme)|
   | SQLDelight | Third-party library. [Docs](https://cashapp.github.io/sqldelight/)|
   
   > You can also find a multiplatform library in the [community-driven list](https://libs.kmp.icerock.dev/).
   > 
   {type="tip"}

4. **Learn more about Kotlin Multiplatform for mobile:**
   * Learn more about [Kotlin Multiplatform](multiplatform-get-started.md).
   * Look through [samples on GitHub](multiplatform-mobile-samples.md).
   * [Create and publish a multiplatform library](multiplatform-library.md).
   * Learn how Kotlin Multiplatform is used at [Netflix](https://netflixtechblog.com/netflix-android-and-ios-studio-apps-kotlin-multiplatform-d6d4d8d25d23), [VMware](https://kotlinlang.org/lp/multiplatform/case-studies/vmware/), [Yandex](https://kotlinlang.org/lp/multiplatform/case-studies/yandex/), and [many other companies](https://kotlinlang.org/lp/multiplatform/case-studies/).

5. **Join the Kotlin Multiplatform community:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#multiplatform](https://kotlinlang.slack.com/archives/C3PQML5NU) channels.
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: Subscribe to the ["kotlin-multiplatform" tag](https://stackoverflow.com/questions/tagged/kotlin-multiplatform).

6. **Follow Kotlin** on ![Twitter](twitter.svg){width=25}{type="joined"} [Twitter](https://twitter.com/kotlin), ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

<tab id="android" title="Android app">

* If you want to start using Kotlin for Android development, read [Google's recommendation for getting started with Kotlin on Android](https://developer.android.com/kotlin/get-started).

* If you're new to Android and want to learn to create applications with Kotlin, check out [this Udacity course](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012).

Follow Kotlin on ![Twitter](twitter.svg){width=25}{type="joined"} [Twitter](https://twitter.com/kotlin), ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

</tab>

<tab id="multiplatform-library" title="Multiplatform library">

Support for multiplatform programming is one of Kotlin's key benefits. It reduces time spent writing and maintaining the same code for different platforms while retaining the flexibility and benefits of native programming.

Here you'll learn how to develop and publish a multiplatform library:

1. **Create a multiplatform library:**

   * Complete the [Create and publish a multiplatform library](multiplatform-library.md) tutorial. It shows how to create a multiplatform library for JVM, JS, and Native platforms, test it and publish to a local Maven repository.

2. **Use libraries in your application:**

   * [Ktor](https://ktor.io/docs/)
   * [Serialization](serialization.md)
   * [Coroutines](coroutines-overview.md)
   * [DateTime](https://github.com/Kotlin/kotlinx-datetime#readme)

   > Learn more about [adding dependencies on libraries](multiplatform-add-dependencies.md).
   > You can also find a multiplatform library in the [community-driven list](https://libs.kmp.icerock.dev/).
   >
   {type="tip"}

3. **Learn more about Kotlin Multiplatform programming:**

   * [Introduction to Kotlin Multiplatform](multiplatform-get-started.md).
   * [Kotlin Multiplatform supported platforms](multiplatform-dsl-reference.md#targets).
   * [Kotlin Multiplatform programming benefits](multiplatform.md).

4. **Join the Kotlin Multiplatform community:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#multiplatform](https://kotlinlang.slack.com/archives/C3PQML5NU) channels.
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: Subscribe to the ["kotlin-multiplatform" tag](https://stackoverflow.com/questions/tagged/kotlin-multiplatform).

5. **Follow Kotlin** on ![Twitter](twitter.svg){width=25}{type="joined"} [Twitter](https://twitter.com/kotlin), ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

If you've encountered any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

</tabs>

## Is anything missing?

If anything is missing or seems confusing on this page, please [share your feedback](https://surveys.hotjar.com/d82e82b0-00d9-44a7-b793-0611bf6189df).
