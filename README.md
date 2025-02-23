
# Python Asynchronous Translation Software

This is a simple asynchronous text translation software using Google Translate in Python. It allows users to input text and translate it between different languages using the `googletrans` library.

## Features
- Asynchronous translation using `asyncio`
- Supports multiple languages
- User-friendly command-line interface
- Error handling for invalid inputs

## Prerequisites
Ensure you have Python installed (Python 3.7+ is recommended). You also need to install the required dependencies.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/ucheblessed28/translator.git
   cd translator
   ```

2. Install the required dependencies:
   ```bash
   pip install googletrans==4.0.0-rc1
   ```

## Usage

Run the script using:
```bash
python translator.py
```

### Example Usage
1. Enter the text to translate.
2. Enter the source language code (e.g., `en` for English).
3. Enter the target language code (e.g., `yo` for Yoruba).
4. View the translated text.

### Sample Input & Output
#### Input:
```
Enter text: Hello, how are you?
Enter source language code: en
Enter target language code: fr
```
#### Output:
```
Original Text: Hello, how are you?
Translated Text: Bonjour, comment allez-vous?
```

## Supported Languages
The software supports multiple language codes, such as:
- **English:** `en`
- **Yoruba:** `yo`
- **Hausa:** `ha`
- **Igbo:** `ig`
- **French:** `fr`
- **Spanish:** `es`
- And many more...

## Known Issues
- The `googletrans` library may sometimes fail due to API limitations.
- The script may not work properly with certain special characters.

---

### Author
Developed by [Uche Blessed](https://github.com/ucheblessed28)
