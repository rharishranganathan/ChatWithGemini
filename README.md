# ChatWithGemini

This project demonstrates how to build a knowledge-based assistant using SwiftUI and Google Gemini APIs. The app can respond to user queries by integrating the Google Gemini API. This implementation is based on Etisha Garg's project to learn how to integrate the Gemini API with SwiftUI.

## Features

- Integration with Google Gemini API
- Setup and use API keys securely
- Basic SwiftUI interface for user interaction

## Installation

### Prerequisites

- Xcode 15.0 or higher
- iOS 15 or higher
- `GoogleGenerativeAI` package installed
- Gemini API key (can be obtained from Google AI Studio)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ChatWithGemini.git
    cd ChatWithGemini
    ```

2. Open the project in Xcode:
    ```bash
    open ChatWithGemini.xcodeproj
    ```

3. Install the `GoogleGenerativeAI` package:
    - Right-click on the project in Xcode.
    - Select `Add Package Dependencies`.
    - Enter the URL: `https://github.com/google/generative-ai-swift`.
    - Click `Add Package`.

4. Set up the API key:
    - Create a new Property List file named `GenerativeAI-Info.plist`.
    - Add your API key to the file with the key `API_KEY`.

## Usage

1. Run the app in Xcode.
2. Enter your queries in the provided text field.
3. The app will respond using the integrated Gemini API.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

For more detailed instructions and the full tutorial, check out the [blog post](https://www.swiftanytime.com/blog/implement-gemini-ai-sdk-with-swiftui).

---
