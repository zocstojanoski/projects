# MoviesApp

`MoviesApp` is an application that provides a list of movies and TV shows sorted by genre.

## How to Build

1. Ensure you have [CocoaPods](https://cocoapods.org/) installed.
   
   ```bash
   $ sudo gem install cocoapods
   ```

2. Clone the repository:
   
   ```bash
   $ git clone https://github.com/[Your-Username]/MoviesApp.git
   ```

3. Navigate to the project directory and install the necessary pods:
   
   ```bash
   $ cd MoviesApp
   $ pod install
   ```

4. Open the `.xcworkspace` file with Xcode:
   
   ```bash
   $ open MoviesApp.xcworkspace
   ```

5. Build and run the app using Xcode.

## General Architecture

The app uses the **MVVM (Model-View-ViewModel)** architectural pattern, which allows for a clear separation of concerns, modular code, and easy unit testing.

- **Model**: Represents the data and the business logic.
- **View**: Represents the UI.
- **ViewModel**: Acts as a bridge between the Model and the View.

## Libraries Used

- **RxSwift & RxCocoa**: These libraries are used to implement reactive programming in the app. RxSwift provides dynamic data streams (observables), while RxCocoa offers bindings for UI elements, making it easier to reactively update the UI based on data changes.


- **AlamofireImage**: An image component library for Alamofire that offers easy image downloading and caching.
