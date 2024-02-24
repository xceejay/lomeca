### Lomeca: LOcal MEdia CAst

Lomeca (short for Local Media Cast) is an open-source software designed to effortlessly parse a directory of media files and display them on a webpage. It also allows users with access to the webpage to stream the content through a peer-to-peer (p2p) proxy, enabling seamless media sharing within a local network.

#### Features
- **Directory Parsing**: Automatically scans a designated directory for media files.
- **Web Interface**: Provides a user-friendly web interface to browse and select media files.
- **Streaming via P2P**: Enables users to stream selected media content through a peer-to-peer proxy.
- **Customizable Settings**: Easily configurable settings for directory paths, server ports, and more.
- **Open Source**: Released under the MIT License for full transparency and community collaboration.

#### Technologies Used
- **Golang**: Backend server for handling directory parsing and streaming functionality.
- **Next.js**: Web framework for creating the user interface and handling HTTP requests.
- **WebTorrent**: P2P streaming library for efficient media sharing.

#### Installation

##### Prerequisites
- Node.js & npm installed on your machine

##### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lomeca.git
   ```


#### Usage
1. Upon accessing the web interface, Lomeca will automatically scan the specified directory for media files.
2. Browse through the available media files.
3. Click on a file to start streaming through the built-in peer-to-peer proxy.
4. Share the provided streaming link with others on your local network for collaborative media watching.

#### Contributing
Contributions are welcome! If you'd like to contribute to Lomeca, please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

#### License
Lomeca is licensed under the [Apache License](LICENSE).

#### Disclaimer
Lomeca is intended for personal, non-commercial use within local networks. Please ensure you have the necessary rights to stream and share media files.

#### Support
For any questions, issues, or feature requests, please create an [issue](https://github.com/xceejay/lomeca/issues) on GitHub.

#### Acknowledgements
- This project was inspired by the need for a simple, self-hosted media casting solution.
- Special thanks to the open-source community for their invaluable contributions.

---

Feel free to customize this README with more specific instructions, detailed usage examples, or additional features as you develop Lomeca further. Happy coding! 🚀
