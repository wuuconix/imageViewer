# Image Viewer

[中文说明](./README-CN.md)

an simple html page simulating browser native image viewer

click and try:

<div style="display: grid; grid-template-columns: repeat(2, minmax(auto, 200px)); gap: 20px; align-self: center;">
    <a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png">
        <img src="https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png">
    </a>
    <a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg">
        <img src="https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg">
    </a>
</div>

the site will get the img src from the hash in the url you request.

format: `https://img-viewer.netlify.app/#${img-src}`