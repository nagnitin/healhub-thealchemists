/* font family Raleway */

@import url('https://fonts.googleapis.com/css2?family=Belleza&family=Raleway:wght@100;200;300;400;500;600;700;800;900&display=swap');
/* font family Barlow */

@import url('https://fonts.googleapis.com/css2?family=Barlow:wght@100;200;300;400;500;600;700;800;900&display=swap');

/* Scroll cdn */
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

    <!-- Scroll animation lib -->
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
        AOS.init({
            offset: 150,
            duration: 1250,
            once: true,
        });
    </script>

    <!-- jquery js cdn -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.js"
        integrity="sha512-+k1pnlgt4F1H8L7t3z95o3/KO+o78INEcXTbnoJQ/F2VqDVhWoaiVml/OEHv9HsVgxUaVW+IbiZPUJQfF/YxZw=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <!-- jquery min js cdn -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"
        integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>

    <!-- slick carousel min js cdn -->
    <script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"
        integrity="sha256-DHF4zGyjT7GOMPBwpeehwoey18z8uiz98G4PRu2lV0A=" crossorigin="anonymous"></script>

/* ============= 01. Reset section ============= */

html,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
}

/* HTML5 display-role reset for older browsers */

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
    content: "";
}

button:focus {
    outline: none;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}

select {
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

select::-ms-expand {
    display: none;
}

label {
    font-weight: normal;
}

iframe {
    width: 100%;
}

/* ===== 02. Global Style ===== */
body {
    overflow-x: hidden;
}

h1 {
    font-size: 75px;
    font-weight: 800;
    line-height: 85px;
    font-family: "Raleway", sans-serif;
}

h2 {
    font-size: 45px;
    font-weight: 800;
    line-height: 51px;
    font-family: "Raleway", sans-serif;
}

h3 {
    font-size: 25px;
    font-weight: 800;
    line-height: 31px;
    font-family: "Raleway", sans-serif;
}

h4 {
    font-size: 22px;
    font-weight: 800;
    line-height: 28px;
    font-family: "Raleway", sans-serif;
}

h5 {
    font-size: 20px;
    font-weight: 600;
    line-height: 26px;
    font-family: "Raleway", sans-serif;
}

h6 {
    font-size: 14px;
    font-weight: 500;
    line-height: 20px;
    font-family: "Raleway", sans-serif;
}

p {
    font-size: 16px;
    font-weight: 400;
    line-height: 22px;
    font-family: "Barlow", sans-serif;
}

button {
    font-size: 16px;
    font-weight: 500;
    line-height: 22px;
    padding: 16px 38px 16px 38px;
    text-transform: capitalize;
    font-family: "Barlow", sans-serif;
}

a {
    font-size: 16px;
    font-weight: 500;
    line-height: 22px;
    text-transform: capitalize;
    font-family: "Barlow", sans-serif;
    text-decoration: none;
    transition: all 0.3s ease;
    color: #c9c3c3;
}

.container {
    max-width: 1320px;
    width: 100%;
    margin: 0 auto;
    padding-left: 15px;
    padding-right: 15px;
}


@media screen and (max-width: 768px) {

    /* global style */
    h1 {
        font-size: 60px;
        font-weight: 800;
        line-height: 66px;
    }

    h2 {
        font-size: 34px;
        font-weight: 800;
        line-height: 48px;
    }

    h3 {
        font-size: 18px;
        font-weight: 600;
        line-height: 24px;
    }

    h4 {
        font-size: 16px;
        font-weight: 700;
        line-height: 22px;
    }

    h5 {
        font-size: 14px;
        font-weight: 500;
        line-height: 20px;
    }

    h6 {
        font-size: 12px;
        font-weight: 500;
        line-height: 18px;
    }

    p {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
    }

    button {
        font-size: 14px;
        font-weight: 400;
        line-height: 18px;
        padding: 14px 30px 14px 30px;
    }

    a {
        font-size: 14px;
        font-weight: 400;
        line-height: 18px;
        padding: 14px 30px 14px 30px !important;
    }

    .flex-sb {
        flex-wrap: wrap;
    }

    .w-50 {
        width: 100%;
    }
}


@media screen and (max-width: 500px) {

    /* global style */
    h1 {
        font-size: 40px;
        font-weight: 700;
        line-height: 46px;
    }

    h2 {
        font-size: 30px;
        font-weight: 700;
        line-height: 36px;
    }

    h3 {
        font-size: 18px;
        font-weight: 600;
        line-height: 22px;
    }

    h4 {
        font-size: 16px;
        font-weight: 600;
        line-height: 22px;
    }

    h5 {
        font-size: 16px;
        font-weight: 500;
        line-height: 20px;
    }

    h6 {
        font-size: 14px;
        font-weight: 500;
        line-height: 20px;
    }

    p {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
    }

    button {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
        padding: 12px 26px 12px 26px;
    }

    a {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
        padding: 12px 26px 12px 26px !important;
    }

}


@media screen and (max-width: 480px) {


    /* global style */
    h1 {
        font-size: 40px;
        font-weight: 700;
        line-height: 46px;
    }

    h2 {
        font-size: 30px;
        font-weight: 700;
        line-height: 36px;
    }

    h3 {
        font-size: 18px;
        font-weight: 600;
        line-height: 22px;
    }

    h4 {
        font-size: 16px;
        font-weight: 600;
        line-height: 22px;
    }

    h5 {
        font-size: 16px;
        font-weight: 500;
        line-height: 20px;
    }

    h6 {
        font-size: 14px;
        font-weight: 500;
        line-height: 20px;
    }

    p {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
    }

    button {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
        padding: 12px 26px 12px 26px;
    }

    a {
        font-size: 14px;
        font-weight: 400;
        line-height: 20px;
        padding: 12px 26px 12px 26px !important;
    }
}