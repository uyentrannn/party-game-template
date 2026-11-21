# Bachelor / Bachelorette Party Games

A set of party games for a bachelor/bachelorette (hen/stag) night, played on a laptop or TV in your web browser. No account and no installation needed.

- **Meet the Bachelors** and **Meet the Bachelorettes**: guests vote on "who would…" questions about a cast of characters.
- **How well does the groom know the bride?**: quiz with answers you reveal.
- **Couple trivia teams**: two teams, points for each question.

Everything below is written for non-technical people. You don't need to code.

---

## 1. Get your own copy

1. Make a free account at [github.com](https://github.com) if you don't have one.
2. On this repository's page, click the green **Use this template** button, then **Create a new repository**.
3. Give it a name (for example `our-party-games`), choose **Private** if you will add real photos, then click **Create repository**.

You now have your own copy that you can change freely.

## 2. Play it (pick one way)

### Option A: Double-click (easiest, works offline)

1. On your copy's page click the green **Code** button, then **Download ZIP**.
2. Open the ZIP file so it becomes a normal folder.
3. Double-click **index.html**. It opens in your browser and you can play.

Note: the optional YouTube background music does not work this way. Everything else does. If you want music, use Option B.

### Option B: Put it online with a link (works on any phone or TV, supports music)

1. On your copy's page click **Settings**, then **Pages** in the left menu.
2. Under "Build and deployment", set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then click **Save**.
3. Wait 1 to 2 minutes. The same page then shows your link, like `https://yourname.github.io/our-party-games/`.

Note: free GitHub Pages only works for **private** repositories on paid plans. On a free account, either make the repository public (so don't put real photos in it) or use Option A.

## 3. Make it yours

### Names, questions and music (inside the game)

1. Open the game and click **Host setup**.
2. Change the groom's and bride's names, the cast of characters, the questions and answers, and the YouTube music link.
3. Everything saves automatically **in that browser**. Use the same browser and device on the night.

Tip: type `{groom}` and `{bride}` in a question and it fills in the names for you.

### Photos

The characters show a grey "Your photo here" picture until you add photos.

1. Open the **photos** folder.
2. Add pictures with **exactly** these names (all lowercase, ending in `.jpg`):
   - `bachelor-1.jpg` to `bachelor-6.jpg`
   - `bachelorette-1.jpg` to `bachelorette-9.jpg`
3. Portrait photos (taller than wide) look best. Photos you don't add keep the placeholder.

To add files on GitHub's website: open the **photos** folder, click **Add file**, then **Upload files**, drag your pictures in and click **Commit changes**. Keep each file under 25 MB.

### Reveal videos (optional)

If you recorded video answers, put them in a `videos` folder named `q01.mp4`, `q02.mp4`, and so on, then change the line starting `const VIDEOS = [];` near the top of `index.html` to list them. Skip this if you don't have videos.

## Troubleshooting

- **My changes in Host setup disappeared.** They are stored in one browser. A different browser, device or private window starts fresh.
- **Photos don't show.** Check the file name is exactly right (`bachelor-1.jpg`, not `Bachelor-1.JPG` or `.png`).
- **No music.** Music needs Option B and an internet connection. Some YouTube videos block embedding, so try another link.
- **Start over.** In Host setup, use **Restore default setup**.
