# [WebShell | Terminal Portfolio Website](https://terminal.nader.codes/)

> Forked from [https://github.com/nasan016/webshell](https://github.com/nasan016/webshell)

![terminal.nader.codes](_terminal.png)

![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Features
* **[Tab]** for auto completion.
* **[Esc]** to clear the input line.
* **[↑][↓]** to scroll through your command history.

## ???
<div align="center">
  <img alt="banner" src="https://raw.githubusercontent.com/nasan016/webshell/main/res/secret.png">
</div>
How did we get here?

## Configuration

Most of the configuration is done in the `config.json` file.

> Generate ascii [here](https://patorjk.com/software/taag/). ANSI Shadow is the current font family.

```json
{
  "ascii": [
    "███╗   ██╗ █████╗ ██████╗ ███████╗██████╗ ",
    "████╗  ██║██╔══██╗██╔══██╗██╔════╝██╔══██╗",
    "██╔██╗ ██║███████║██║  ██║█████╗  ██████╔╝",
    "██║╚██╗██║██╔══██║██║  ██║██╔══╝  ██╔══██╗",
    "██║ ╚████║██║  ██║██████╔╝███████╗██║  ██║",
    "╚═╝  ╚═══╝╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝ "
  ],
  "repoLink": "https://github.com/dabit3/terminal-portfolio",
  "social": {
    "email": "shawakash2003@gmail.com",
    "github": "shawakash",
    "linkedin": "shawakash"
  },
  "aboutGreeting": "Hi I'm Akash. I'm a full stack engineer doing undergrad in ECE.",
  "projects": [
    [
      "Youtube Creator",
      "Full stack framework for Uploading youtube videos where editor can edit which then could be published on providing authentication.",
      "https://github.com/shawkash/youtubeCreator"
    ],
    [
      "Whatsai",
      "Whatsapp Bot that lets you talk to ai(chatgpt)",
      "https://github.com/shawakash/whatsai"
    ],
    [
      "Game_Of_Life",
      "Conway's game of life implementaion in rust.",
      "https://github.com/shawakash/game_of_life"
    ],
    [
      "xChange",
      "Upcoming a end to end exchange like binance",
      "https://github.com/shawakash/game_of_life"
    ],
    [
      "Distributed Chat System",
      "Pub/Sub redis powered chat backend.",
      "https://github.com/shawakash/DistributeChat_Redis"
    ],
    [
      "Course_Selling App",
      "Simple Crud based Course selling app.",
      "https://github.com/shawakash/Course-Selling-App"
    ],
  ]
}
```

## Run the Project Locally:

Clone the repository
```shell
git clone https://github.com/nasan016/webshell.git
```
Go to the project directory
```shell
cd webshell
```
Install the dependencies
```shell
yarn install
```
Start the server
```shell
yarn run dev
```
