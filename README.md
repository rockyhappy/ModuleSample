# ModuleSample

## Overview
This project is an Android application designed with a modular architecture. It is divided into several modules to promote clean architecture principles, such as separation of concerns, easier testing, and better maintainability. The modules include Core, Data, Domain, Presentation, FeatureA, and FeatureB.

## Modules

### Core
The Core module contains the base classes, common utilities, and dependency injection setup used throughout the application.

### Data
The Data module handles data management, including repository implementations, local database interactions, and remote data sources.

### Domain
The Domain module defines the business logic and use cases of the application. It contains entities, use cases, and repository interfaces that are implemented in the Data module.

### Presentation
The Presentation module contains the UI logic, including ViewModels, Compose UI components, and other presentation-layer classes.

### FeatureA
The FeatureA module encapsulates all functionality related to Feature A of the application. It includes its own ViewModels, UI components, and any specific business logic.

### FeatureB
The FeatureB module encapsulates all functionality related to Feature B of the application. It includes its own ViewModels, UI components, and any specific business logic.

## Project Structure
project-root
```│
├── core
│   ├── src
│   └── build.gradle
│
├── data
│   ├── src
│   └── build.gradle
│
├── domain
│   ├── src
│   └── build.gradle
│
├── presentation
│   ├── src
│   └── build.gradle
│
├── featureA
│   ├── src
│   └── build.gradle
│
├── featureB
│   ├── src
│   └── build.gradle
│
└── app
    ├── src
    └── build.gradle
```

## Getting Started

### Prerequisites
- Android Studio Bumblebee or later
- Java 8 or later
- Kotlin 1.5 or later

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rockyhappy/ModuleSample.git
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
