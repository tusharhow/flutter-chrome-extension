# Case Changer - Chrome extension

Chrome extension created using Flutter for changing the text case. It can be used to change the text case to **UPPERCASE**, **lowercase**

![Chrome extension in action](https://user-images.githubusercontent.com/65107679/215836495-19089a3f-cbb2-46b9-beef-7ccafaa058a8.gif)

## Usage

To use this project as a Chrome extension, follow the steps below:

1. Clone this project using:
   
    ```sh
    git clone https://github.com/tusharhow/flutter-chrome-extension.git
    ```

2. From the project directory, run:
   
   ```sh
   flutter build web --web-renderer html --csp
   ```

3. Go to the following URL from Chrome browser:
   
   ```url
   chrome://extensions
   ```

4. Enable the **Developer mode**.

5. Click **Load unpacked**. Select the `<project_dir>/build/web` folder.

This will install the extension to your Chrome browser and then you will be able to access the extension by clicking on the **extension icon**.

---
### Need Help?

If you need help in setting up the project or have any questions, feel free to reach out to me on [Twitter](https://twitter.com/tusharhow) or [LinkedIn](https://www.linkedin.com/in/tusharhow/)

---
### Social Media

[![Twitter Follow](https://img.shields.io/twitter/follow/tusharhow.svg?style=social)](https://twitter.com/tusharhow)
[![Linkedin: tusharhow](https://img.shields.io/badge/-tusharhow-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tusharhow/)](https://www.linkedin.com/in/tusharhow/)
![GitHub followers](https://img.shields.io/github/followers/tusharhow.svg?style=social&label=Follow)

---

## License
```
Copyright (c) 2023 Tushar Mahmud

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.