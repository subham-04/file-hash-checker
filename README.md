# File Hash Calculator

A powerful Windows desktop application for calculating file hashes with comprehensive VirusTotal integration. Built with Python and tkinter, featuring modern dark/light theme support and secure API management.

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Python](https://img.shields.io/badge/python-3.7+-green)
![License](https://img.shields.io/badge/license-Non--Commercial-red)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

## ✨ Key Features

- 🔐 **Multi-Hash Support**: MD5, SHA1, SHA256, and SHA512 calculation
- 🦠 **VirusTotal Integration**: Security analysis with 40+ antivirus engines  
- 🎨 **Modern UI**: Dark/light theme with tabbed interface
- 📁 **Batch Processing**: Process files and folders recursively
- 🖱️ **Drag & Drop**: Intuitive file selection
- 📊 **Data Export**: CSV export with timestamps
- 🔒 **Secure Storage**: Windows Registry-based API key management
- ⚡ **Real-time Progress**: Pause/resume/stop controls

## 🚀 Quick Start

1. **Install Python 3.7+** (with tkinter)
2. **Install dependencies**:
   ```bash
   pip install requests
   ```
3. **Run the application**:
   ```bash
   python File_Hash_Calculator.py
   ```

## 🎯 Perfect For

- **🔒 Security Analysts**: Malware analysis and file verification
- **💻 IT Administrators**: System integrity monitoring  
- **🛡️ Incident Response**: Digital forensics and investigation
- **📁 File Management**: Duplicate detection and organization
- **🔍 Quality Assurance**: Software testing and verification

## 🔑 VirusTotal Setup

1. Get a free API key from [VirusTotal](https://www.virustotal.com/gui/my-apikey)
2. Launch the application and go to "VirusTotal" tab
3. Click "🔑 Set API Key" and paste your key
4. Start analyzing files for threats!

**Free Account Limits**: 500 requests/day, 15,000/month

## 📚 How to Use

### Basic Hash Calculation
1. **Choose input**: Folder, files, or drag & drop
2. **Start processing**: Click "🚀 Start Processing"
3. **View results**: See hashes in the "Results" tab

### VirusTotal Analysis
1. **Select files**: Check boxes in Results tab
2. **Move to VT**: Click "🔍 Move to VirusTotal"
3. **Analyze**: Click "🔍 Check with VirusTotal"
4. **View threats**: � Clean, 🔴 Threat, ⚠️ Error

## �️ System Requirements

- **OS**: Windows 10/11
- **Python**: 3.7+ with tkinter
- **RAM**: 2GB recommended
- **Storage**: 50MB free space
- **Internet**: For VirusTotal only

## 📊 Performance

- **Small files** (<1MB): ~1000 files/minute
- **Medium files** (1-10MB): ~200 files/minute
- **Large files** (>100MB): ~10 files/minute
- **Memory usage**: ~50MB base + 20MB per 1000 files

## 🔒 Security & Privacy

- ✅ **Local processing**: All hashes calculated on your machine
- ✅ **No telemetry**: Zero data collection or tracking
- ✅ **Secure storage**: API keys stored in Windows Registry
- ✅ **Data integrity**: Automatic validation and corruption detection
- ✅ **Optional internet**: Only used for VirusTotal features

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Test thoroughly on Windows 10/11
4. Submit a pull request

See [LICENSE](LICENSE) for usage terms.

## 📄 License

This project is licensed under a **Non-Commercial License**. See the [LICENSE](LICENSE) file for details.

**Summary**: Free for personal, educational, and non-profit use. Commercial use requires permission.

## 🆘 Support

- **📖 Issues**: Create GitHub issues for bugs or feature requests
- **� Contact**: For commercial licensing inquiries
- **� Troubleshooting**: Check Python and dependencies installation

---

**Built with ❤️ for the cybersecurity community**
