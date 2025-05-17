# CC Recipe Website

[cc.eats](https://cc-eats.vercel.app/)

This is a simple cooking website that contains a portfolio of recipes that 
are intended for daily use in the CC family.
There are no ads, trackers or cookies (unless recipes thereof).

## Ways to contribute

- By adding a recipe.
- Make a recipe and take a nice picture of it if no nice picture already
  exists. Submitted images should be small `.webp` files ideally less than 100K
  or so.
- Fix errors in recipes or add minor improvements.

## Rules for submission

- Model submission files after [example.md](example.md). Put them in `content/`.
- File names should be the name of the dish with words separated by hyphens
  (`-`). Not underscores, and definitely not spaces.
- Recipe must be "based," i.e. good traditional and substantial food. Nothing
  ironic, meme-tier hyper-sugary, meat-substitute, etc.
- Don't include salt and pepper and other ubiquitous things in the ingredients
  list.
- Don't include an image unless (1) you took it yourself, and more importantly
  (2), **it actually looks good**! Most existing images on this site IMO look
  like unappetizing NEET photos, so you are welcome to take one a better one
  yourself and submit it if you make a dish. If you don't know if your image is
  good, please have a real-live woman in real life approve your photo before
  you submit it. I'm serious about this, it's a waste for me to wade through
  disgusting photos in PRs.
- The file needs to be `\n` terminated in unix-fashion (if you're on Linux you
  don't need to care, it should be automatic).

### Tags

Remember to add tags to your recipe, but try to use tags already used by other recipes.

If your recipe contains no meat or dairy, include the `fasting` tag.
If it includes dairy but no milk, include the `cheesefare` tag.

### Images

Images are stored in `/pix`.

Each recipe can have a title image at the top and perhaps several instructional
images as absolutely necessary.

Do not add stock images you found on the internet. Take a good picture yourself
of the actual dish created. If you see a bad or substandard image, you may
submit a better one.

Images should be in `.webp` format and with as small file size as possible. If
you submit an image for say, `chicken-parmesan.md`, it should be added as
`pix/chicken-parmesan.webp`.

If you would like to add additional directional images,
they should be numbered with two digits like: `pix/chicken-parmesan-01.webp`, etc.

Note also that images should have links beginning with a slash in this use
case, i.e. `/pix/...`.
