# Weather AI 🌦️🤖

Weather AI is a modern Android application that provides real-time weather forecasts for various states across India. Built with Jetpack Compose and powered by the Open-Meteo API, it offers a visually rich and performant user experience.

## ✨ Features

- **Dynamic State Grid**: Explore weather information for all Indian states through a beautiful, image-driven grid.
- **Real-time Forecasts**: Get up-to-date temperature, humidity, and wind speed data.
- **Detailed Forecasts**:
    - Current weather conditions with descriptive status.
    - 24-hour hourly temperature forecast.
    - 7-day daily forecast with high and low temperatures.
- **Rich Visuals**: Uses high-quality landscape imagery for each state, fetched and cached efficiently using Coil.
- **Modern UI/UX**: Fully built with Jetpack Compose following Material 3 design guidelines.

## 🛠️ Tech Stack

- **Language**: [Kotlin](https://kotlinlang.org/)
- **UI Framework**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Networking**: [Retrofit](https://square.github.io/retrofit/) with [Moshi](https://github.com/square/moshi) for JSON parsing.
- **Image Loading**: [Coil](https://coil-kt.github.io/coil/) for asynchronous image fetching and caching.
- **Architecture**: MVVM (Model-View-ViewModel) with StateFlow for reactive UI updates.
- **Dependency Injection**: Manual DI via a centralized `NetworkModule`.
- **Navigation**: [Jetpack Compose Navigation](https://developer.android.com/jetpack/compose/navigation) for seamless screen transitions.

## 🚀 Getting Started

### Prerequisites

- Android Studio Ladybug (or newer)
- Android SDK 24+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-ai.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Run the app on an emulator or a physical device.

## 🌐 API Reference

The app uses the [Open-Meteo API](https://open-meteo.com/), a free and open-source weather API. No API key is required for basic usage.

## 📸 Screenshots

*(Add your screenshots here)*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
