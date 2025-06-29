# WaveStreamGo

WaveStreamGo is a lightweight, high-performance Go library for text-to-speech (TTS) and audio synthesis, bridging Go and C++ for fast audio processing.

---

## Features

- Text-to-speech conversion in Go
- Seamless integration with C++ audio backends via cgo
- Simple, idiomatic Go API
- Ready-to-use example provided
- Easy to build with Makefile or Docker

---

## Getting Started

### Prerequisites

- [Go](https://golang.org/dl/) 1.18+ installed
- C++ compiler (e.g., `g++`)
- (Optional) [Docker](https://www.docker.com/) for container builds

### Build

```bash
make

Or, build and run with Docker:

docker build -t wavestreamgo .

Run Example

cd example
go run main.go


⸻

Project Structure
	•	piper.go / WaveStreamGo.cpp / WaveStreamGo.h — Core source files
	•	example/ — Example usage in Go
	•	Makefile, Dockerfile — For building and testing

⸻

License

This project is licensed under the MIT License.
Copyright (c) 2024
Parth Sojitra parthsojitra10@gmail.com

⸻

Author

Parth Sojitra
GitHub

⸻

Contributing

Pull requests and suggestions are welcome. Open an issue or submit a PR!

---

**How to use:**  
- Save as `README.md` in your project root.
- Commit & push to GitHub.

Let me know if you want badges (build status, Go report, etc.), or a shorter/longer version!
