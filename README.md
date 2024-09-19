# **Skizify**

Skizify is a video consultation platform designed to connect users with experts or professionals via video calls. It enables users to post meetings, receive applications from professionals, and schedule one-on-one video sessions. Skizify leverages modern web technologies like WebRTC and WebSockets to facilitate real-time video communication and efficient meeting management.

## **Features**

- **Post & Apply for Meetings**: Users can post meetings, and professionals can apply. Users can review applicants and select the expert they wish to consult.
- **Real-Time Video Communication**: Implemented using WebRTC to ensure high-quality video and audio during sessions.
- **Profile & Explore Pages**: Separate profile pages for users and professionals, enabling them to manage their activities, view meetings, and customize their profiles.
- **Chat Integration**: In-session chat feature for both users and experts to communicate effectively during a meeting.
- **Scheduling & Notification System**: WebSocket-powered real-time notifications for meeting schedules and session reminders.
- **Authentication & Security**: Integrated with NextAuth for secure user authentication.

## **Tech Stack**

- **Frontend**:
    - Next.js (React-based framework)
    - TypeScript
    - Tailwind CSS (UI Styling)
    - Recoil (State management)
    - ShadCN , AcertanityUI , MagicUI (Design system components)
- **Backend**:
    - Node.js with Express (Server-side framework)
    - PostgreSQL with Prisma ORM (Database management)
    - WebRTC (Real-time video communication)
    - WebSockets (Real-time messaging and notification)
    - NextAuth (User authentication)
- **Tools**:
    - Turborepo (Monorepo management)
