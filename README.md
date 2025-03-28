# My Photo Gallery

This project is a simple photo gallery website built using HTML, CSS, and Bootstrap. It showcases a collection of beautiful images with a hover effect and a contact form.

## Features

- Responsive design using Bootstrap
- Image gallery with hover effect
- Contact form with validation
- Content Security Policy for enhanced security

## Usage

1. **Fork the Repository:**
   - Go to the GitHub page of the repository.
   - Click the "Fork" button at the top right corner of the page to create a copy of the repository under your own GitHub account.

2. **Clone the Forked Repository:**
   - Open your terminal or command prompt.
   - Run the following command, replacing `your-username` with your GitHub username:
     ```sh
     git clone https://github.com/your-username/my_photo_gallery.git
     ```
   - Navigate into the cloned repository:
     ```sh
     cd my_photo_gallery
     ```

3. **Open the Project:**
   - Open [index.html](http://_vscodecontentref_/0) in your web browser to view the photo gallery.

## Dependencies

- [Bootstrap](https://getbootstrap.com/)
- [Animate.css](https://animate.style/)
- [Pageclip](https://pageclip.co/)

## Contact Form

The contact form uses Pageclip to handle form submissions. Replace the `action` attribute in the form with your own Pageclip URL.

```html
<form action="https://send.pageclip.co/your-pageclip-url" class="pageclip-form" method="post">
    <input type="text" name="name" placeholder="Name" required/>
    <input type="email" name="email" placeholder="Email" required/>
    <button type="submit" class="pageclip-form__submit">
        <span>Send</span>
    </button>
</form>