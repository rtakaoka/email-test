# IPG HEALTH CHALLENGE - PART 1
This is the changes log for the IPG HEALTH's E-MAIL test for Senior Front End Developer position.

## How does it work?
I've listed below every change I made to the HTML code, so it becomes easy to follow. Starting from the first comment and ending with the last one from the *EmailComments.pdf* document.

## Tools I used to work on this challenge
Email responsivity validation
- [HTML Email Checker](https://www.htmlemailcheck.com/check/)
- [Can I Email](https://www.caniemail.com/)

Design the new header and footer images
- [Canva](https://www.canva.com)

## 1. Change Log: From "Test Instructions" item 1
*Make changes on the e-mail according to the pdf comments attached in this test.*

### 1.1. BONUS: Redesign this header image with money and coffee imagery (can be either photorealistic OR cartoony)
- Changed `href` attributes on the header `<img>` tag to `images/new-header.gif`.
- Changed `href` attributes on the footer `<img>` tag to `images/new-footer.gif`.
- My intention here was to bring an approach closer o the "coffee" concept and give some movement with the coin rain.

### 1.2. Bump font to 20px and BOLD
- Changed `font-size` property to `20px` value.
- Added `font-weight` property with `bold` value.
- Changed `line-height` property changed to `20px` value for a better readability.

### 1.3. Underline `Employee Referral Bonus`
- Changed `<strong>` tag to `<b>` tag for compatibility with older email clients.
- Added `<u>` tag for underline because `text-decoration` property with `underline` value is not compatible with some clients, i.e. iOS's Proton Mail.

### 1.4. Change color to `#eb05a2`
- Changed `color` property to value `#eb05a2`.

### 1.5. Center this text (NOW FOR THE RAFFLE WINNER!!!!!!!!!)
- Changed `text-align` property to value `center`.

### 1.6. Change to `Congratulations,`
- Changed text content to `Congratulations,`.

### 1.7. Delete all but two exclamation points
- Removed 5 exclamation points "!".

### 1.8. Set URL to https://www.amazon.com
- Changed `href` attribute to `https://www.amazon.com` value.

## 2. Change Log: From "Test Instructions" item 2
Fill the media query to make the e-mail responsive until 480px wide screen.

### 2.1. The texts in this range of screen size must have `14px` for `font-size` and `18px` for `line-height`.
*It was necessary to use the `!important` rule because I needed to overwrite inline `width` attributes.*

- Added `.text` class selector to media query with the following properties:
  - `font-size: 14px !important;`
  - `line-height: 18px !important;`
- Added `.table` class selector to media query
  - `width: 100% !important;`
- Added `.image` class selector to media query
  - `width: 100% !important;`
  - `height: auto !important;`
- Added `.pad` class selector to media query
  - `width: 5% !important;`