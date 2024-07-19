# Tether 📹

Tether is a comprehensive video conferencing platform designed for seamless, secure, and versatile online meetings. With features such as real-time interactions, advanced meeting controls, and responsive design, Tether provides an optimal user experience across devices.

## Features

- Authentication: Secure login via social sign-on or traditional email and password methods using Clerk, ensuring appropriate access levels and permissions.
- New Meeting: Start a new meeting with configurable camera and microphone settings before joining.
- Meeting Controls: Full control over meeting aspects, including: recording, emoji reactions, screen sharing, microphone control, sound adjustments, various layouts, participant list view, individual participant management (pinning, muting, unmuting, blocking, allowing video share), and exiting/ending meetings.
- Schedule Future Meetings: Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page.
- Past Meetings List: Access a list of previously held meetings, including details and metadata.
- View Recorded Meetings: Access recordings of past meetings for review or reference.
- Personal Room: Users have a personal room with a unique meeting link for instant meetings, shareable with others.
- Join Meetings via Link: Easily join meetings created by others by providing a link.
- Secure Real-time Functionality: All interactions are secure and occur in real-time, maintaining user privacy and data integrity.
- Responsive Design: Ensures optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.

## Try it out!

You can access Tether at [tethervc.vercel.app](https://tethervc.vercel.app). Enjoy!

If you'd like, you can run a development instance by cloning this repository, installing the dependencies with `npm`, and setting up `.env.local` with the following keys:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

## Usage

- Authentication: Register or log in using social sign-on or email/password.
- New Meeting: Click "Start New Meeting" and configure your camera and microphone settings.
- Meeting Controls: Use the control panel to manage your meeting settings and participants.
- Schedule Meeting: Navigate to the 'Upcoming Meetings' page and fill in the meeting details.
- View Past Meetings: Go to the 'Past Meetings' page to view previous meetings and their recordings.
- Personal Room: Use your unique personal room link for instant meetings.

## Contributing

We welcome contributions to improve Tether. To contribute, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
