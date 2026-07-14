# Frontend Mentor - Blog preview card

## Preview
You can see preview here.
For mobile version => (./preview_mobile.png)
For desktop version => (./preview_desktop.png)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

I found this challenging looks quite so easy to pick up as a newbie.

## HTML

First thing I do is sketch out the html structure of the page to be as semantic as I can be.

It's a blog preview card. So, I wanted to contain content into a card container. Also, this preview card is more than just a card, it says what it's about. So, instead of "<div>" I used "<article>" element as a container.

And for image, I wrapped it with "<figure>".

Also, for the "Published 21 Dec 2023" part, I think it would be better to use "<time>" element for that instead of just <span> or <p>.

Also, for the author part, I divided it apart from the other parts above it. So, I used "<footer>" inside the "<article>" container.

## CSS

I started by setting custom css properties for colors.

And I prepared for base styles - font-family, font-sizes, background-colors

Then, I styles one by one from top to bottom.

But before all that, I make the card to be centered using flex box method.
And from top to bottom, I styled one by one.
I used flex box method in card container too. With it, easier to make gaps between each elements with flex box instead of using margin-top & margin-bottom multiple times.

To make as responsive as it can be, I used relative units like - "rem" and "%" and used not just width property but also max-width property.
You will notice that I don't use any media queries.

## The End 