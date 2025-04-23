# Color Palette Generator

The **Color Palette Generator** is a tool designed to streamline the process of creating and exporting color palettes. It reads color names and hex codes from a CSV file and generates a PDF containing color swatches, hex codes, and their corresponding RGB values. This makes it easy to share and use color palettes in design workflows.

## Features

- **CSV Input**: Import color names and hex codes from a CSV file.
- **PDF Output**: Generate a PDF with:
    - Color swatches for visual reference.
    - Hex codes for precise color identification.
    - RGB values for compatibility with various design tools.
- **Fast and Easy Exporting**: Quickly create professional-looking color palette documents in a PDF format for sharing with your team.

## Installation

1. Clone the repository:
     ```bash
     git clone https://github.com/nordpolen/color-palette-generator.git
     cd color-palette-generator
     ```

## Usage

1. Prepare a CSV file with the following format:
     ```csv
     Name,Hex
     Red,#FF0000
     Green,#00FF00
     Blue,#0000FF
     ```

2. Run the HTML file in browser.

3. The generated PDF will be saved as `output.pdf`.

## Example Output

The PDF will include:
- A swatch of each color.
- The hex code (e.g., `#FF0000`).
- The RGB values (e.g., `255, 0, 0`).

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the tool.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the open-source community for providing the tools and libraries that made this project possible.