# Whale Sound Audio Scraper

## Project Overview
The Whale Sound Audio Scraper is a Python-based tool designed to download WAV and MP3 audio files from the Woods Hole Oceanographic Institution (WHOI) website. This project aims to facilitate the collection of whale sounds for research and educational purposes.

## Features
- Download WAV and MP3 audio files from WHOI.
- Filter audio files by species, date, and other criteria.
- Easy-to-use command-line interface.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/skalaliya/audio-scrape.git
   ```
2. Navigate to the project directory:
   ```bash
   cd audio-scrape
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Examples
To download audio files, run the following command:
```bash
python scraper.py --species humpback --format mp3
```

## Dependencies
- Python 3.x
- requests
- beautifulsoup4

Use the `requirements.txt` file to install the necessary packages.

## Project Structure
```
audio-scrape/
│
├── scraper.py                 # Main script to run the audio scraper
├── requirements.txt           # List of dependencies
└── README.md                  # Project documentation
```

## Example Output
Upon running the scraper, you will see output like:
```
Downloading humpback_whale_2021_01_01.mp3...
Download completed: humpback_whale_2021_01_01.mp3
```

## Contributing Guidelines
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request detailing your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.