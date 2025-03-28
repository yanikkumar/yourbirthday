# My Blessings ![GitHub Stars](https://img.shields.io/github/stars/yanikkumar/myblessings?style=social)

**For your Birthday/Anniversary**

Send a cute Birthday/Anniversary wish to your loved ones. Basic text-wishes are so boring now. Make the person smile with this web-based blessing. Made with a simple **`PHP`** script mixed with some **`Vanilla JS`** for animations and interactions, added with **`TailwindCSS`** for a good-looking User Interface.

**Live at: [myblessings.great-site.net](https://myblessings.great-site.net/)**

## What is this?

This web application provides a fun and interactive way to send personalized wishes for birthdays and anniversaries. Instead of sending a plain text message, you can generate a special link with animated emojis and a customized message.

### For Normal Users

This is a simple tool to create fun, shareable wishes for your friends and family. You can create a unique link to send someone for their birthday or anniversary.

#### How to Use?

It's super easy to use:

1.  **Go to the Generator:** Open your web browser and go to [myblessings.great-site.net/generate-blessings](https://myblessings.great-site.net/generate-blessings)
2.  **Fill the form:**
    - Select "Birthday" or "Anniversary".
    - Enter the name of the person you're sending the wish to.
    - Optionally, add your name as the sender.
    - Optionally, enter the date (birthday or anniversary date). _If you leave this blank, the message will be purely celebratory. If you include the date, a mildly sarcastic message related to the age or years will be added._
3.  **Generate and Copy:** Click the "Generate Link" button. The website will create a special message for you. Click the "Copy Message" button to copy the message to your clipboard.
4.  **Share:** Paste the copied message into WhatsApp, a social media post, or anywhere else you want to share it!

The person receiving your message will see an animated page with your wishes.

> If you don't want to show the sarcastic message, do not add the date.

If you like the work, make sure to ⭐ this repo! 🤩 It will help me create some more open-source fun projects.

---

## For Curious Eyes 👀 (and Developers!)

This project was created with simplicity and ease of use in mind, but also with the potential for extension and contribution. Here's a bit more detail for those who want to get involved:

### Developer's Perspective

As the developer, I aimed to create a simple, fun, and easily shareable web application using PHP for the backend logic, Tailwind CSS for rapid and consistent styling, and Vanilla JavaScript for dynamic front-end effects. The application generates a unique, shareable link that displays a customized (blessing) message.

The goal was to move away from boring, plain-text wishes and add some animations and a touch of humor (with the optional sarcastic messages).

### Setting up Locally

If you want to contribute to this project, or just run it on your own machine, here's how:

1.  **Prerequisites:**

    - PHP (version 7.4 or later is recommended)
    - A web server (Apache, Nginx, or PHP's built-in server)
    - Git (optional, for cloning the repository)

2.  **Installation:**
    - **Clone the repository:**
      ```bash
      git clone [https://github.com/yanikkumar/myblessings.git](https://github.com/yanikkumar/myblessings.git)
      cd myblessings
      ```
    - **Set up your web server:**
      - If you have Apache or Nginx, create a virtual host that points to the project's `public` directory (if you had one). Since this project doesn't have a public directory, just point it to the project root.
      - If you're using PHP's built-in server:
      ```bash
      php -S localhost:8000 -t .  #  Run from the project root
      ```
    - **Access the application:** Open your web browser and go to `http://localhost:8000` (or the URL you set up).

## Developer Usage

1.  **Generate a Blessing:**

    - Go to the `generate.php` page.
    - Select the wish type (Birthday or Anniversary).
    - Enter the recipient's name.
    - Optionally, enter the sender's name and the date.
    - Click the "Generate Link" button.

2.  **Share the Blessing:**

    - The application will generate a shareable link.
    - Copy the link and share it with your friends and family via social media, messaging apps, or email.

3.  **View a Blessing:**

    - When someone clicks on the shared link, they will be directed to the `index.php` page, where they can view the personalized blessing message.

## File Structure

- `index.php`: Displays the personalized blessing message.
- `generate.php`: Form to generate shareable blessing links.
- `README.md`: Project documentation.

### Contribution

I welcome contributions to make this project even better! If you have any ideas for new features or improvements, feel free to submit a pull request or open an issue.Here are some ways you can contribute:

- **Add more messages:** The messages in `index.php` can be expanded.
- **Improve the animations:** The JavaScript in `index.php` could be enhanced.
- **Add features:** Think of new ways to make the more interactive and engaging.
- **Fix bugs:** If you find any issues, please report them or submit a pull request with a fix.

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes.
4.  Push to your fork.
5.  Submit a pull request.

If you like the work, make sure to ⭐ this repo! 🤩 It will help me create some more open-source fun projects.

## Developer

- [Yanik Kumar](https://youtube.com/yanikkumarvlogs)

## License

This project is open-source.

---

## Sponsor this project

If you find this project helpful and want to support its development, please consider sponsoring me. Your contributions will help me dedicate more time to improving the project and adding new features.
You can sponsor me on:

- [GitHub](https://github.com/yanikkumar)
- [Buy Me a Coffee](https://www.buymeacoffee.com/yanikkumar)

---

## Previous Version

The previous version of this project is hosted at: 👇🏻
[https://yourbirthday.great-site.net](https://yourbirthday.great-site.net)

The previous version had a different URL structure, this is kept for historical reasons.

Direct link parameters for the old version:

[https://yourbirthday.great-site.net/?name=Yanik&sender=BelieveMaster&dob=1998-03-21](https://yourbirthday.great-site.net/?name=name=Yanik&sender=BelieveMaster&dob=1998-03-21)

- name={BIRTHDAY_PERSON_NAME}
- sender={NAME_OF_THE_PERSON_SENDING_WISHES}
- (optional) dob={DOB_OF_BIRTHDAYPERSON} FORMAT: `YYYY-MM-DD`

> If you don't want to show the sarcastic message, do not add DOB in params.
