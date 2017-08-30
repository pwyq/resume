# One-Page Resume

    Author: Yanqing Wu
    Language: HTML+CSS

### Say something
I am tired of editing my resume on Word or something similar as they have a bunch of restrictions.
I also found that LaTex/Tex is not easy to adjust everything down to pixel (and there is extra learning cost).

Therefore, I use HTML+CSS to make my new resume. Hope you may also like it.

### DEMO
![alt text][png-demo]

### How To Use
0. Required knowledge: very very basic of `html` :) If you don't know `html` it's still ok, as I wrote detailed comments in the file, just follow all `TODO`s

1. Clone this repository to your local machine

    open a terminal and `cd` to your work repostiroy, then copy following
    
    `git clone https://github.com/pwyq/resume.git`
    
    Alternatively, click `Download ZIP` under the green `clone or download` button on [this page][1]. Next, extract the compressed file.

2. Open `resume-template.html` file with your favourite text editor or a front-end IDE

3. Change everything based on your own need. Remember to save :)

4. Rename the file to `resume-FirstName-LastName.html`

5. To print to `.pdf` file. Open the modified `resume-FirstName-LastName.html` on one of the listed browsers, and follow the corresponding instructions.

    P.S. usually double-click can open the `html` file on your default browser. If this is not working, right-click the `html` file and choose a browser from `open with`.

    - [Google Chrome](#google-chrome)
    
6. <a name="last-name">Last step</a>, open the `.pdf` file of your resume, now print to a actual piece of paper :P
    
    P.S. If the printed resume is cropped somehow, on the `Page Sizing & Handling`, select `Shrink oversizzed page`.
    
            - This may vary from different PDF viewers, similar setting is `Shrink to Printable Area`
            - If the printed resume still does not look right, feel free to contact me.

### Tested Browser

- <a name="google-chrome">Google Chrome</a>

    1. After opening the `resume-FirstName-LastName.html` on browser, right click the page (anywhere works) and click `Print`;
    
    2. Click `More settings`;
    
    3. Make sure followings:
    
        - Layout: `Portrait`
        - Paper size: `A4`
        - Margins: `None`
        - uncheck `header and footer`
        
    4. Click `save`. Now you should have a `.pdf` format file of your resume.
    
    5. Go back to `How To Use` for the [final step](#last-step).

### TODO
1. Add mobile version?
2. Tested on more browsers


[1]: https://git.io/v5WGN
[png-demo]: /demo/resume-demo.png
