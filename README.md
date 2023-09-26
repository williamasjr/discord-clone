# PROJECT
<h2>In this project is development a real-time discord clone, all with servers, channels, video calls, audio calls, editing and deleting messages as well as member roles.

  I'm development this with the classes of channel code with Antonio.
  Available in https://www.codewithantonio.com/projects/team-chat-platform
     </h2>
  

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## key features

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

### Cloning the repository

```shell
git clone git@github.com:williamasjr/discord-clone.git
```

### Install packages

```shell
npm i
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Starts a development instance of the app `npm run dev`

