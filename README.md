# Text Document Analyzer
![Grammar Correction](https://img.shields.io/badge/Grammar-Correction-blue)
![Document Processing](https://img.shields.io/badge/Document-Processing-green)
![Streamlit App](https://img.shields.io/badge/Streamlit-App-red)

## Overview

Text Document Analyzer is a powerful Streamlit application for correcting grammar in documents while preserving formatting. The application uses language models to analyze and correct grammar errors in DOCX, DOC, and TXT files while maintaining the original document structure, formatting, tables, and other elements.

App link - https://textdocanalyer.streamlit.app/

[Link Text](https://example.com)

Note: This application is hosted on Streamlit Cloud and may take a few seconds to load initially.


## Features

- **Grammar Error Correction:** Automatically detects and corrects various types of grammar errors while preserving the original meaning
- **Format Preservation:** Sophisticated XML processing to maintain document formatting, tables, images, and other elements
- **Multiple Compatibility Modes:**
  - **Preserve All:** Maintains all document formatting, tables, and images
  - **Safe Mode:** Balances formatting preservation with compatibility
  - **Ultra Safe Mode:** Creates a new document with perfect compatibility
- **In-depth Error Analysis:** Detailed breakdown of grammar errors with visualizations
- **Customizable Corrections:** Add specific instructions to guide the grammar correction process
- **Export Options:** Download corrected documents in DOCX format and detailed error reports

## Technical Details

### Key Components

1. **DocxValidator:** Validates and fixes issues in DOCX XML structure
2. **XMLDocumentCorrector:** Modifies document XML while preserving formatting
3. **GrammarCorrectorForm:** Interfaces with language models to correct grammar
4. **DocumentAnalyzerForm:** Analyzes and categorizes grammar errors
5. **DocumentProcessorForm:** Orchestrates the complete document processing workflow
6. **DocumentCorrectionAppView:** Streamlit UI for the application

### Error Types Detected

The application can identify and correct over 25 different types of grammar errors, including:
- Punctuation errors
- Capitalization issues
- Verb tense inconsistencies
- Subject-verb agreement
- Article usage problems
- Preposition errors
- Run-on sentences
- Sentence fragments
- Redundancy
- Wordiness
- Passive voice
- And many more

### Technical Architecture

The application uses a sophisticated processing pipeline:
1. Document parsing and validation
2. Text extraction and segmentation
3. Grammar correction via language models
4. XML structure preservation and modification
5. Error analysis and classification
6. Report generation and visualization

## Getting Started

### Prerequisites

- Python 3.7+
- Streamlit
- Language model server (e.g., LM Studio) accessible via API

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/TextDocumentAnalyzer.git
cd TextDocumentAnalyzer

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run TextDocumentAnalyzer.py
```

### Configuration

The application allows configuration of:
- Language model API URL
- Model selection
- Temperature setting for corrections
- Document compatibility mode
- Analysis visualization options

## How It Works

1. **Upload:** Users upload a document (.docx, .doc, or .txt)
2. **Configure:** Set processing options and provide any specific instructions
3. **Process:** The app processes the document, correcting grammar while preserving format
4. **Analyze:** Error types are identified and visualized
5. **Download:** Get the corrected document and detailed error reports

## Use Cases

- **Academic Writing:** Improve research papers and essays while maintaining citations and formatting
- **Professional Documentation:** Polish business documents, proposals, and reports
- **Technical Writing:** Ensure technical documentation is grammatically correct
- **Educational Use:** Help students improve their writing with detailed error analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to the Streamlit team for their excellent framework
- This project uses language models for grammar correction

## Contact

- Author: Srinivas K M
- Created: May 2024
- Last Modified: May 2025
