# Introduction

A real-time Figma clone with live collaboration with cursor chat, comments, reactions, and canvas design using fabric.js.
Project based on work of JavaScript Mastery's FIGMA CLONE.

## Tech Stack

- Next.js
- TypeScript
- Liveblocks
- Fabric.js
- Shadcn
- Tailwind CSS

## ⚙️ Dependencies and Their Usage

### External Libraries

#### Liveblocks

- **@liveblocks/client**: Real-time collaboration and synchronization.
- **@liveblocks/node**: Server-side integration with Liveblocks.
- **@liveblocks/react**: React bindings for Liveblocks.
- **@liveblocks/react-comments**: React components for Liveblocks comments.

#### Radix UI

- **@radix-ui/react-collapsible**: Collapsible UI components.
- **@radix-ui/react-context-menu**: Context menu for UI interactions.
- **@radix-ui/react-dropdown-menu**: Dropdown menus for user selections.
- **@radix-ui/react-label**: Label components for form inputs.
- **@radix-ui/react-select**: Select components for user choices.
- **@radix-ui/react-slot**: Slot components for customizable UI.
- **@radix-ui/react-tooltip**: Tooltip components for UI hints.

#### Other Utilities

- **class-variance-authority**: Handling class variance.
- **clsx**: Utility for conditionally joining class names together.
- **fabric**: HTML5 canvas library for drawing and manipulating graphics.
- **jspdf**: Library for generating PDFs.
- **lucide-react**: Icon components for Lucide icons.
- **next**: Framework for server-rendered React applications.
- **react**: JavaScript library for building user interfaces.
- **react-dom**: React package for working with the DOM.
- **tailwind-merge**: Tailwind CSS utility for merging classes.
- **tailwindcss-animate**: Tailwind CSS plugin for animations.
- **uuid**: Utility for generating unique IDs.

### Versions

- **next**: 14.1.0
- **react**: ^18
- **react-dom**: ^18

Other packages are specified with their respective versions to maintain compatibility and utilize the latest features and improvements.

## Features

- **Multi Cursors, Cursor Chat, and Reactions**: Collaborate with multiple users with individual cursors, real-time chat, and reactions.
- **Active Users**: List of active users for visibility into current engagement.
- **Comment Bubbles**: Attach comments to canvas elements for feedback.
- **Creating Different Shapes**: Tools to generate various shapes on the canvas.
- **Uploading Images**: Import images onto the canvas.
- **Customization**: Adjust properties of design elements.
- **Freeform Drawing**: Free drawing on the canvas.
- **Undo/Redo**: Reverse or restore actions.
- **Keyboard Actions**: Keyboard shortcuts for various actions.
- **History**: Review action history.
- **Managing Canvas**: Delete, scale, move, clear, and export designs.