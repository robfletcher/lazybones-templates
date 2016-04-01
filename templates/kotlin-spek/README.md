Basic Kotlin project
----------------------------------

You have just created a basic Kotlin project with Spek and Mockito available for unit testing.
IntelliJ integration is also included.

The project has the following file structure:

    .
    ├── build.gradle
    ├── gradle
    │   ├── idea
    │   │   ├── codeStyleSettings.xml
    │   │   └── gradleSettings.xml
    │   ├── idea.gradle
    │   ├── kotlin.gradle
    │   ├── mockito.gradle
    │   └── spek.gradle
    └── src
        ├── main
        │   ├── kotlin
        │   └── resources
        └── test
            ├── kotlin
            └── resources

Add your source files to `src/main/kotlin`, your test cases to `src/test/kotlin`.

You can build and test with `gradle build` and generate an IntelliJ IDEA `.ipr` project file with `gradle idea`.
