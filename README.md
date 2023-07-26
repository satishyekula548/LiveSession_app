# LiveSession_App

This repository contains a Live Session App for neatSkills that allows users to schedule and host meetings using the Jitsi Meet External API. With this app, users can easily create and join video conferences with participants.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Features

- Schedule and host Jitsi video conferences.
- Join scheduled meetings with a unique room ID.
- Customizable interface properties for the Jitsi video conferencing experience.
- Participants' display names are customizable.
- Video and audio control options during the meeting.
- Thank-you page redirection after leaving the meeting.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/ritik2358/LiveSession_App.git
```

2. Change directory to the project folder:

```bash
cd LiveSession_App
```

3. Install the dependencies:

```bash
npm install
```

## Usage

To start the development server and run the application:

```bash
npm run dev
```

The application will be accessible at  `http://127.0.0.1:5173/` in your web browser.

## Getting Started

1. Schedule a Meeting:
   - On the home page, enter your name and click "Schedule Meeting."
   - The application will generate a unique room ID for your meeting.
   - Share the room ID with participants who will join the meeting.

2. Join a Scheduled Meeting:
   - On the home page, enter your name and the room ID provided by the meeting organizer.
   - Click "Join Meeting" to join the video conference.

3. During the Meeting:
   - Once in the meeting, you can control your video and audio using the icons at the bottom center.
   - To leave the meeting, click the red "Leave" button, and you will be redirected to the thank-you page.

## Contributing

Contributions to this project are welcome. If you find any bugs or have suggestions for improvements, please feel free to open an issue or create a pull request.

When submitting a pull request, please make sure to follow the existing coding style and add appropriate test coverage if applicable.


**Note:** This project relies on the Jitsi Meet External API, which may have its own terms and conditions. Please make sure to review and comply with the Jitsi Meet External API's licensing and usage terms.
