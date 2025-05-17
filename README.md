# ARİVA OSINT V4

🌟 **ARİVA OSINT V4** is a powerful Python-based Open-Source Intelligence (OSINT) tool designed for *educational purposes only*. It enables users to gather information through various methods, including phone number analysis, website WHOIS lookups, nickname searches across social media, IP address lookups, and more.

⚠️ **Disclaimer**: This tool is intended for *ethical and educational use only*. Any illegal or unethical usage is strictly prohibited, and the developers are not responsible for misuse. Always comply with local laws and regulations.

📢 **Join our community**: [Telegram @ArivaTools](https://t.me/ArivaTools)  
🎨 **Designed by**: @AtahanArslan  
🚀 **Version**: 1.0.0

## Features
- **Phone Number Lookup**: Retrieve carrier, country, region, timezone, and social media links (Telegram, WhatsApp, Viber).
- **Website WHOIS Lookup**: Extract domain registration details, including owner, organization, and name servers.
- **Nickname Search**: Check username availability across platforms like Instagram, TikTok, Twitter, Facebook, YouTube, Telegram, Roblox, and Twitch.
- **IP Address Lookup**: Obtain geolocation, ISP, and organization details for an IP address.
- **Database Search**: Search for text within local database files with multiple encoding support.
- **Text Transformation**: Convert text using a custom transliteration dictionary (e.g., Cyrillic to Latin).
- **Guides**: Includes educational guides for doxing, swatting, and anonymity (for learning purposes only).
- **Cross-Platform**: Supports Windows, Linux, and Termux.
- **User-Friendly**: Colorful CLI interface powered by `pystyle` with automatic dependency installation.

## Prerequisites
- Python 3.6 or higher
- Internet connection
- Git (for cloning the repository)

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/siberdunyaniz/arivaosintv3.git
   cd arivaosintv3
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   *Note*: The tool automatically installs required modules (`fake_useragent`, `pystyle`, `phonenumbers`, `requests`, `whois`) on first run if missing.

3. **Run the Tool**:
   ```bash
   python arivaosintv3.py
   ```

## Usage
1. Launch the tool:
   ```bash
   python arivaosintv3.y
   ```
2. Select an option from the menu:
   - `[1]` Phone Number Lookup: Enter a phone number (e.g., `+1234567890`).
   - `[2]` Website Info: Enter a domain (e.g., `example.com`).
   - `[3]` Nickname Search: Enter a username (e.g., `exampleuser`).
   - `[4]` IP Address Lookup: Enter an IP address (e.g., `8.8.8.8`).
   - `[5]` Database Search: Provide a file path and search text.
   - `[6-8]` Guides: View doxing, swatting, or anonymity guides.
   - `[9]` Text Transformation: Enter text to transform.
   - `[0]` Exit.
3. Follow the prompts to input data and view results.

## Example
```bash
  ariva@osint ═> 3
Kullanıcı adını girin: exampleuser
============================================================
Instagram: https://www.instagram.com/exampleuser - Hesap bulundu
Twitter: https://twitter.com/exampleuser - Hesap bulunamadı
============================================================
```

## Screenshots
![ARİVA OSINT Banner](screenshots/banner.png)  
*Banner displayed on tool startup*

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## Notes
- **Version Check**: The tool attempts to check for updates, but the version check URL is currently empty in the code. Update the `check_version()` function with a valid URL (e.g., a GitHub raw file) for this feature to work.
- **Guides**: The doxing, swatting, and anonymity guides are for *educational purposes only* and should not be used for malicious activities.
- **Dependencies**: Ensure all required modules are installed. If issues arise, manually install them using `pip install <module>`.

## Legal Notice
This tool is provided for **educational purposes only**. The developers are not responsible for any misuse, illegal activities, or damages caused by this tool. Always ensure compliance with local laws and ethical standards when conducting OSINT activities.

## Contact
- 📢 Telegram: [@ArivaTools](https://t.me/ArivaTools)
- 🎨 Developer: [@AtahanArslan](https://t.me/AtahanArslan)
- 📧 Issues: Create a [GitHub Issue](https://github.com/siberdunyaniz/arivaosintv4/issues)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

🌟 **ARİVA OSINT V4** - Empowering ethical OSINT research!  
🚀 Follow us on [Telegram](https://t.me/ArivaTools) for updates!