# Laravel Real-Time Chat with Reverb and Vue 3

This project provides a foundation for building a real-time chat application using Laravel, Laravel Reverb (a Pusher alternative), and Vue 3. It enables users to connect, send messages, and receive updates in real-time, fostering a dynamic and engaging chat experience.


## Video Tutorial
[![Real-time Chat system](https://i3.ytimg.com/vi/8ykxcM0-3Yg/hqdefault.jpg)](https://www.youtube.com/watch?v=8ykxcM0-3Yg)

**Try [Spec Coder: VSCode Extension](https://qirolab.com/spec-coder) - Code Faster & Smarter with AI!**



## Installation:

1. Clone the repository:
```
git clone git@github.com:qirolab/laravel-reverb-chat.git
```

2. Navigate to the project directory:
```
cd laravel-reverb-chat
```

3. Install dependencies:
```
composer install
npm install # or yarn install
```

4. Generate application key:
```
php artisan key:generate
```

5. Configure database connection:

Edit `.env` file according to your database credentials.

6. Migrate database tables
```
php artisan migrate
```

7. Start development server
```
php artisan serve
npm run dev:tailwind
```

Here we used `npm run dev:tailwind` instead of `npm run dev` because we created
a `tailwind` theme using the Laravel Themer package in this project.


## Want to Support My Work?

If you found this demo helpful and want to support my work, check out some of my other products:

<div style="display:flex;">
  <a href="https://qirolab.com/ctrl-alt-cheat" title="Ctrl+Alt+Cheat - The Ultimate Cheat Sheets at Your Fingertips">
    <img width="200" src="https://i.imgur.com/6igLwXU.png" alt="Ctrl+Alt+Cheat" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://qirolab.com/spec-coder" title="Spec Coder: AI-Powered VS Code Extension">
     <img width="200" src="https://i.imgur.com/zHSNlJu.png" alt="Spec Coder" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://qirolab.gumroad.com/l/javascript-from-es2015-to-es2023" title="JavaScript: A Comprehensive Guide from ES2015 to ES2023 - eBook">
      <img width="200" src="https://i.imgur.com/vXnJAul.png" alt="JavaScript Guide" />
  </a>
</div>



---

#### Get $200 free credit for DigitalOcean! (Use this link to sign up)

[![DigitalOcean Referral
Badge](https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg)](https://www.digitalocean.com/?refcode=e740238537d0&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)
