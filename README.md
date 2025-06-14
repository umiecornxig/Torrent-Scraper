# 📺 Torrent Link Scraper Chatbot

A Python-based chatbot that lets users search and retrieve torrent magnet links for TV shows based on season and episode. It uses the [TV Maze API](https://www.tvmaze.com/api) for show metadata and dynamically scrapes torrent websites for up-to-date magnet links.

---

## 🚀 Features

- 🔍 Search for TV shows and browse by season and episode
- ⚙️ Uses TV Maze API for accurate show data
- 🧲 Extracts torrent details: title, seeders, leechers, and magnet links
- ⚡ Fast performance with `diskcache` (cached queries respond in <0.2s)
- 💬 Interactive chatbot-style CLI interface

---

## 🛠️ Installation

### Requirements

- Python 3.7+
- pip

### Install dependencies

```bash
pip install -r requirements.txt
