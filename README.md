# Sentiance SDK Starter

A simple single-view application that uses the Sentiance SDK and demonstrates how to enable/disable the SDK based on Firebase Remote Config.

The Sentiance SDK must be initialized in the `onCreate()` method of your `Application` class. This must happen before the `onCreate()` method returns, therefore it should be done synchronously on the main application thread.