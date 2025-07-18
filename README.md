# PixelPals

An AI-driven virtual friends framework for Habbo-style retro CMS projects. Bring your retro hotel to life with interactive, programmable NPCs who can chat, guide users, or run automated in-game events.

---

## Description

PixelPals is a modular library designed to plug into Habbo retro CMS installations (e.g. Arcturus, Plus, etc.). It allows hotel owners to create **virtual characters** who:
- Walk around rooms
- Chat with users
- Share news or promotions
- Help onboard new users
- Run scheduled events

It’s the perfect way to make your hotel feel **alive**!

---

## Table of Contents

- [Features](#features)
- [Known Issue](#known-issues)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Contributors](#contributors)
- [License](#license)

---

## Features

✅ AI conversation scripts  
✅ Random room-wandering behavior  
✅ Scheduled announcements/events  
✅ Easy integration into Habbo retro CMS  
✅ Customizable NPC appearances and names  
✅ Event triggers based on user actions

--- 

## Known Issues

- NPC sometimes walks into walls and gets stuck
- Conversation bubbles overlap when too many NPCs talk at once
- NPC pathfinding occasionally causes jittery movements
- NPC randomly disappears from the room under heavy server load
- NPC accidentally blocks doors, preventing users from leaving the room
- Delayed responses if the AI API is rate-limited
- NPC ignores movement scripts and stands still indefinitely
- NPC accidentally repeats the same line several times
- Performance slows down when spawning more than 20 NPCs in a single room
- Error thrown if NPC’s appearance string is empty or invalid
- NPC starts speaking in all caps for no apparent reason
- Random PHP fatal error when saving very long conversation scripts
- NPCs sometimes appear wearing default clothes instead of assigned outfits
- NPC accidentally interrupts user conversations with random comments
- Room loading times increase when too many NPCs are spawned
- NPC randomly tries to leave the hotel permanently (logs show “Goodbye cruel world!”)


---

## Technologies Used

- PHP
- Laravel (or any PHP MVC framework)
- MySQL
- JavaScript
- Node.js (optional for advanced AI scripts)
- WebSocket (for real-time updates)
- OpenAI API (optional for advanced chatbot conversations)

---

## Installation

Clone the repo:

```git clone https://github.com/yourusername/July4_Assignment_3.git```

CD into the repo

```cd July4_Assignment_3```

Install Composer 

```composer install```

Install Front-End Dependencies

```npm install```
```npm run build```

Create .env file 

```cp .env.example .env```

Serve the Application 

```php artisan serve```

---

## Contributors

- **Chunk** ([@chunk082](https://github.com/rbegin95))

---

## License

PixelPals is released under the GPL License. See the LICENSE file for more details.
