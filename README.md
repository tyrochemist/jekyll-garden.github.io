# Jekyll Garden 
This is a simple Jekyll theme created for building a digital garden with Obsidian and Github Pages. You have to fork this theme to your Github account, configure Github pages, and start using the `_notes` folder as the Obsidian vault. Check out [the demo](https://jekyll-garden.github.io/). 

This theme is based on [Simple Jekyll](https://github.com/raghuveerdotnet/simply-jekyll) theme.

## Installation (Github pages)
_Detailed Installation how-to, with screenshots available [here](https://jekyll-garden.github.io/jekyll-garden/posts/how-to)_

Building a Jekyll website on Github Page is simple and seamless.
Step 1: Sign-In to Github, visit the theme page and click on 'Use this Template'
Step 2: Name the forked repo as `yourusername.github.io`
Step 3: Go to your repo's settings > pages and set the source to your main branch. 
Step 4 (Optional): If you have a custom domain, set CNAME. 

Claps! The Jekyll website with a Note Garden theme is ready. Visit  `yourusername.github.io` to see that. 
_If it's not working, edit this readme (add something and commit) to trigger static page generation._

Now Part 2, setting Github Repo with Obsidian.

Step 1: Go to `yourusername.github.io`, and clone your repository to your machine. For this, you can use git-commands or install Github for desktop. 
Step 2: Once you have successfully cloned the repository to your machine, Open the Obsidian app, and set the folder `_notes` inside the repository as your vault. 
Step 3: You can start adding notes to this vault and add frontmatter to support. Read about YAML at [Welcome to the garden]()
Step 4: Once you have enough notes, got to the Github Desktop app, commit the changes to main, and push the changes to Github. Github will update the pages!

#### Credits & Thanks
- [raghuveerdotnet](https://github.com/raghuveerdotnet), who wrote 90% of the code.
- [Asim K T](https://github.com/asimkt), who coded the base HTML for me. 
- [Santosh Thottingal](https://github.com/santhoshtr), [Binny V A](https://github.com/binnyva), Puttalu for Note taking inspiration
- Team [Obsidian](https://obsidian.md/) for making obsidian a [markdown](https://daringfireball.net/projects/markdown/) based product

#### Install Local 

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. `_notes` contain all atomic notes. If you want to use this for blog, add posts inside `_posts` folder, following standard Jekyll frontamtter. 

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## 0.2 Version To-Do
- [ ] Cleanup CSS
- [x] Cleanup Config
- [x] Write Readme
- [x] Write demo pages - Welcome, markdown, unfeed-demo
- [x] Add sample blog
- [x] Cleanup Index
- [x] Cleanup Nav links
- [ ] Add Links at README --> Welcome to the Garden.
- [ ] Add links to Workflow at README and Unfeed-demo and how-to-post
- [x] Modify license 
- [x] Dark Theme Support (Partial; needs testing)
- [ ] Icon as SVG/Asset (Knows how to do)
    - [ ] Set `var(--text-sub)` to sun/moon icons
    - [ ] Replace logo with SVG
- [x] Check Obsidian image attachment to Jekyll
- [x] Remove Simple Jekyll Assets
- [x] Logo & FavIcon
- [x] Add Github Screenshots (Or create another note, with same note + images)
- [ ] BUG Tool tip inside tool tip :D 

## Future
- [ ] Show tags on notes
- [ ] Automatic tag pages
- [ ] Tag list on homepage, above search
- [ ] Add css to URL/post/ page (Blog list)
- [ ] Add Gatsby link
