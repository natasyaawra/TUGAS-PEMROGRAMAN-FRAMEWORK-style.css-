# TUGAS-PEMROGRAMAN-FRAMEWORK-style.css-


header {
    background-image: url(../imgs/header.png);
    background-size: cover;
}

.small-container {
    width: 95%;
    margin: 0 auto;
}

.overlay {
    background-color: rgba(0, 0, 0, .51);
    width: 100%;
    height: 100%;
}

.violet-overlay {
    background-color: rgba(189, 140, 191, .51);
    width: 100%;
    height: 100%;
    padding: 70px 0;
}

.white-overlay {
    background-color: rgba(255, 255, 255, .7);
    height: 100%;
    width: 100%;
}

.margin_top_30 {
    margin-top: 30px;
}

.service_blog h3.blog_head {
    float: left;
    background: #4fcaff;
    text-align: center;
    font-size: 24px;
    text-transform: none;
    margin: 0;
    min-height: 50px;
    line-height: 50px;
    padding: 0 50px;
    color: #fff;
    position: absolute;
    bottom: 0;
    width: 100%;
    max-width: 300px;
    left: 15px;
}

.service_blog h3.blog_head::after {
    width: 50px;
    height: 50px;
    content: "";
    display: block;
    position: absolute;
    right: -20px;
    background: #4fcaff;
    top: 0;
    transform: skew(-30deg);
}

h2 span, h1 span {
    color: #bd8cbf;
}

li {
    list-style-type: none;
}

a:hover {
    text-decoration: none;
}

a, button {
    transition: all .5s ease;
}

button {
    padding: 0
}

body {
    font-size: 1.1rem;
}

/* navbar */

nav.navbar {
    position: relative;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    font-family: 'Roboto', sans-serif;
    background: #0c2326;
    min-height: 95px;
}

nav.navbar a, nav.navbar ul li a {
    color: #FFF !important;
}

nav.navbar ul li {
    padding: 0 15px;
    position: relative;
}

nav.navbar .search-container {
    position: relative;
}

nav.navbar form {
    padding: 5px;
    background-color: white;
    position: absolute;
    width: 260px;
    display: none;
    right: 0;
}

nav.navbar form input {
    padding: 5px 10px;
    border: none;
    background-color: #fff;
    width: 100%;
    font-weight: 300;
    font-size: 16px;
}

.navbar-nav li a {
    font-size: 18px;
    font-weight: 300;
}

.layout_padding {
    padding: 90px 0;
}

.about_section h3 {
    font-size: 40px;
    margin: 5px 0 25px 0;
    font-weight: 600;
}

.about_section h4 {
    color: #4fcaff;
    font-size: 18px;
    margin: 0;
}

p {
    font-size: 18px;
    font-weight: 300;
}

.full {
    width: 100%;
    float: left;
    margin: 0; 
}

.text_align_center {
    text-align: center;
}

.img-responsive {
    max-width: 100%;
}

.white_font {
    color: #fff !important;
}

.h3, h3 {
    font-size: 40px;
    font-weight: 700;
    color: #3a3a3a;
    text-transform: uppercase;
}   

.contact-form {
    padding: 55px 65px;
    background: #4fcaff;
    min-height: 600px;
    margin-top: 60px;
}

.contact-form form input {
    width: 100%;
    background: #fff;
    border: none;
    height: 60px;
    padding: 0 20px;
    text-transform: uppercase;
    margin: 15px 0;
}

.contact-form form textarea {
    width: 100%;
    background: #fff;
    border: none;
    min-height: 120px;
    padding: 15px 20px;
    text-transform: uppercase;
    margin: 15px 0;
}

.contact-form form input[type="submit"] {
    background: #fa3e19;
    color: #fff;
    width: 190px;
    margin: 15px auto 0;
    font-size: 19px;
    font-weight: 300;
    float: none;
    display: flex;
    cursor: pointer;
}

.contact-form form input[type="submit"]:hover,
.contact-form form input[type="submit"]:focus {
    background: #111;
    color: #fff;
    transition: ease all 0.5s;
}

/* header */

header {
    position: relative;
    color: #FFF;
    font-family: 'Roboto', sans-serif;
}

header .container {
    height: 100%
}

header .container > div {
    margin: 0 auto;
    position: relative;
/*    text-align: center;*/
}

header .container > div h1 {
    font-size: 90px;
}

header button {
    background-color: transparent;
    display: block;
    border: 1px solid #FFF;
    border-radius: 50px;
    padding: 0;
    margin: 30px auto;
}

header button a {
    padding: 10px 40px;
    display: block;
    color: #FFF;
}

header button:hover {
    background-color: #bd8cbf;
    border: 1px solid #bd8cbf;
}

header button:hover a {
    color: white;
}

h3.blog_head {
    width: 100%;
    float: left;
    background: #fff;
    text-align: center;
    font-size: 25px;
    text-transform: uppercase;
    color: #090101;
    margin: 0;
    min-height: 75px;
    line-height: 75px;
}

/* about us */

.about-us {
    position: relative;
    padding: 100px 0;
    font-family: 'Open Sans', sans-serif;
}

.about-us .row > .col-lg-6:first-of-type {
    position: relative;
    left: 50px;
}

.about-us .small-container > p + div {
    padding: 70px 0;
    background-color: white;
    box-shadow: 5px 5px 10px #d2cfcf, -5px -5px 10px #d2cfcf;
}

.about-us .small-container > p + div h4 {
    margin-bottom: 40px
}

.about-us .small-container .text-right p {
    margin-bottom: 40px;
    width: 80%;
    float: right;
}

.about-us .small-container > p + div button {
    background-color: #bd8cbf;
    border: none;
}

.about-us .small-container > p + div a {
    display: block;
    color: #FFF;
    padding: 10px 40px;
}

.about-us .item {
    width: 200px;
    position: absolute;
    color: white;
    background-color: #bd8cbf;
}

.about-us .item p {
    font-size: 15px;
}

.about-us .item img {
    width: 100%;
    height: 150px
}

.about-us .item h5 {
    margin: 5px 0;
}

.about-us .item p {
    margin-bottom: 5px;
}

.about-us .item:first-of-type {
    left: 405px;
    bottom: 115px;
    z-index: 2;
    box-shadow: -2px 2px 10px #5d5959;
}

.about-us .item:nth-of-type(2) {
    left: 105px;
    bottom: 115px;
    z-index: 2;
    box-shadow: 2px 2px 10px #5d5959;
}

.about-us .item:nth-of-type(3) {
    position: relative;
    top: 162px;
    left: -45px;
}

.about-us .item:nth-of-type(3) img {
    position: absolute;
    bottom: 70px;
    right: 0px;
    z-index: 0;
}

.about-us .item:last-of-type {
    left: 268px;
    top: 90px;
}

.about-us .first {
    width: 100px;
    height: 200px;
    position: absolute;
    background-color: #bd8cbf;
    top: 140px;
    z-index: -5;
}

.about-us .second {
    width: 100px;
    height: 200px;
    position: absolute;
    background-color: #bd8cbf;
    bottom: 58px;
    right: 34px;
    z-index: -5;
}

.about-us .row > div > .item:nth-of-type(3) div {
    position: relative;
    z-index: 5;
    background-color: #bd8cbf;
    padding: 5px;
}

.blue_bt {
    width: 255px;
    height: 58px;
    background: #4fcaff;
    color: #fff;
    float: left;
    text-align: center;
    line-height: 58px;
    font-size: 20px;
    font-weight: 300;
}

.blue_bt:hover,
.blue_bt:focus {
    background: #fff;
    color: #0c2326;
}

/* services */

.services {
    margin-bottom: 100px;
    font-family: 'Open Sans', sans-serif;
}

.services .slide {
    width: 70%;
    margin: 0 auto;
}

.services .carousel-inner .carousel-item {
    width: 100%;
    height: 100%
}

.services .carousel-inner img {
    height: 100%;
    width: 100%;
}

.services .carousel-control-next, .services .carousel-control-prev {
    width: 60px;
    height: 60px;
    background: #bd8cbf;
    border-radius: 50%;
}

.services .carousel-control-next i, .services .carousel-control-prev i {
    color: #000
}

.services .carousel-control-next {
    right: 0;
    top: 80%;
    right: 40%;
    background-color: #FFF;
}

.services .carousel-control-prev {
    top: 80%;
    left: 40%;
}

.services i {
    color: #bd8cbf;
}

/* agency */

.agency {
    background-image: url('../imgs/agency.png');
    font-family: 'Open Sans', sans-serif;
    background-size: cover;
}

.agency .container > div {
    margin: 0 auto;
    width: 86%;
    margin-bottom: 30px;
}

.agency .white-overlay {
   padding: 50px 0 20px;
}

.agency .container > div > div {
    display: inline-block;
    position: relative
}

.agency .container > div > div img {
    width: 500px;
    margin: 0 20px;
}

.agency img:first-of-type, .agency img:last-of-type {
    width: 200px;
}

.agency .container > div h2 {
    position: absolute;
    color: white;
    bottom: 105px;
    left: 195px;
    font-size: 40px;
}

/* statistics */

.statistics {
    padding: 50px 0;
    font-family: sans-serif;
}

.statistics i, .statistics p {
    color: #bd8cbf;
}

.statistics i {
    margin-bottom: 10px;
}

.statistics h3 {
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 0;
}

.ovarlay_slide_cont {
    background: rgba(5,3,0,0.63);
    position: absolute;
    width: 60%;
    margin: 0 15%;
    z-index: 1111111111;
    top: 135px;
    left: 0;
    padding: 50px 60px 70px;
}

.ovarlay_slide_cont h2 {
    color: #fff;
    text-transform: uppercase;
    font-size: 70px;
    font-weight: 700;
    line-height: normal;
    margin: 0;
}

.ovarlay_slide_cont h4 {
    color: #4fcaff;
    font-size: 32px;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 15px 0;
    line-height: normal;
}

.ovarlay_slide_cont p {
    color: #fff;
    font-weight: 300;
    margin: 0 0 30px 0;
    font-size: 21px;
    padding: 0 75px 0 0;
    line-height: 28px;
}

/* contact */

.contact {
    background-image: url('../imgs/contact.png');
    background-size: cover;
}

.contact h2 {
    color: white;
    margin-bottom: 30px;
}

.contact .contact-form {
    width: 50%;
    margin: 0 auto;
}

.contact form input, .contact form textarea {
    width: 100%;
    outline: none;
    border: none;
    padding: 5px 10px;
}

.contact form input{
    border-radius: 50px;
    margin-bottom: 20px;
}

.contact form textarea {
    resize: none;
    height: 130px;
    border-radius: 25px;
    margin-bottom: 30px;
}

.contact form input[type="submit"] {
    width: 130px;
    height: 40px;
    padding: 0;
    line-height: 40px;
    background-color: #ef44f8;
    color: white;
    margin: 0 auto;
    display: block;
}

/* footer */

footer, footer a {
    color: white;
}

footer {
    display: block;
    overflow: hidden;
    background-color: #0c2326;
}

footer a:hover {
    color: #4fcaff;
}

footer .container > ul {
    overflow: hidden;
    margin: 30px 0;
    padding-left: 0;
}

footer .container > ul li {
    float: left;
    padding-right: 25px;
}

footer .item h4 {
    margin-bottom: 20px
}

footer .item p.address {
    line-height: 1.2;
    font-size: 16px;
}

footer .item ul {
    padding-left: 0;
}

footer .item ul li {
    margin-bottom: 3px;
    font-size: 16px;
}

footer .date p {
    margin-bottom: 5px;
    font-size: 16px;
    font-weight: 300;
}

footer .item form {
    overflow: hidden;
}

footer .item form input {
    width: 100%;
    margin-bottom: 15px;
    padding: 5px 10px;
}

footer .item form input[type="submit"] {
    width: 100px;
    height: 40px;
    line-height: 4px;
    background-color: #ef44f8;
    border: none;
    float: right;
    color: #FFF;
    padding: 0
}

footer .copyright {
    padding: 15px 0;
}

footer .copyright p {
    margin-bottom: 0;
    font-size: 16px;
}

/* media queries */

@media (max-width: 1200px) {
    
    /* about */
    
    .about-us .row > .col-lg-6:first-of-type {
        left: -10px;
    }
    .about-us .small-container .text-right p {
        width: 70%
    }
    .about-us .item {
        width: 150px
    }
    .about-us .item img {
        height: 125px
    }
    .about-us .item:first-of-type {
        left: 440px;
        bottom: 154px;
    }
    .about-us .item:nth-of-type(2) {
        left: 167px;
        bottom: 153px;
    }
    .about-us .item:nth-of-type(3) {
        top: 149px;
        left: 19px;
    }
    .about-us .item:last-of-type {
        left: 305px;
        top: 132px;
    }
    
    .about-us .row > div > .item:nth-of-type(3) img {
        position: static
    }
    
    .about-us .row > div > .item:nth-of-type(3) p {
        display: none;
    }

    /* agency */
    
    .agency img:first-of-type, .agency img:last-of-type {
        width: 150px
    }
    .agency .container > div > div img {
        max-width: 400px;
        width: 100%;
    }
    .agency .container > div h2 {
        bottom: 87px;
        left: 164px;
        font-size: 30px;
    }
    .agency .container > div h2 {
        display: none;
    }

}

@media (max-width: 992px) {
    
    /* header */
    
    header h1 {
        font-size: 65px !important;
    } 
    
    /* navbar */
    
    .navbar ul {
        background-color: #4fcaff;
    }
    .navbar ul li {
        margin: 10px 0;
    }
    nav.navbar form {
        width: 100%;
        position: static;
    }
    
    /* about */
    
    .about-us .small-container > p + div {
        padding: 50px 0;
    }
    .about-us .row > .col-lg-6:first-of-type {
        height: 350px;
        left: 50px;
    }
    .about-us .small-container .text-right p {
        width: 100%;
    }
    
    /* services */
    
    .services .slide {
        width: 80%
    }
    
    .services .carousel-control-next, .services .carousel-control-prev {
        width: 50px;
        height: 50px;
    }
    
    /* agency */
    
    .agency img:first-of-type, .agency img:last-of-type {
        display: none
    }
    .agency .container > div > div img {
        display: block;
    }
    .agency .container > div {
        width: 56%;
    }
    
    /* statistics */
    
    .statistics .col-lg-3 {
        margin-bottom: 40px
    }
    
    /* contact */
    
    .contact .contact-form {
        width: 70%
    }
    
    /* footer */
    
    footer .col-lg-3 {
        margin-bottom: 40px;
    }
    
}

@media (max-width: 768px) {
    
    /* header */
    
    header h1 {
        font-size: 50px !important;
    } 
    
    /* about */
    
    .about-us .row > .col-lg-6:first-of-type {
        display: none;
    }
    
    /* services */
    
    .services .slide {
        width: 90%
    }
    .services .carousel-control-next, .services .carousel-control-prev {
        display: none;
    }
    
    /* agency */
    
    .agency .container > div {
        width: 87%;
    }
    
}



.testimonial_blog {
    background: #a1a1a1;
    width: 100%;
    padding: 40px 50px;
    box-shadow: 50px 50px 0 0 #4fcaff;
}

.testimonial_blog p {
    color: #fff;
}

.testimonial_blog p + p {
    margin: 0;
}

.testimonial_blog p:first-child {
    font-size: 30px;
    font-weight: 500;
}

.subcribe {
    background: #4fcaff;
    padding: 80px 0;
}

.subcribe h3 {
    color: #fff;
}

.subcribe p {
    margin: 0;
    color: #fff;
}

.subcribe form {
    height: 72px;
    background: yellow;
    margin-top: 20px;
}

.subcribe form {
    height: 72px;
    background: #fff;
    margin-top: 20px;
    padding: 0;
    font-weight: 300;
    font-size: 19px;
    display: flex;
}

.subcribe form input {
    margin: 0;
    padding: 0 30px;
    width: 100%;
    border: none;
    font-size: 20px;
    font-weight: 300;
}

.subcribe form button {
    background: #fa3e19;
    color: #fff;
    width: 255px;
    border: none;
    font-size: 20px;
}

.subcribe form button:hover,
.subcribe form button:focus {
    background: #111;
    color: #fff;
}

footer .item p img {
    position: absolute;
    left: 0;
    top: 5px;
}

footer .item p {
    position: relative;
    padding-left: 25px;
    font-size: 16px;
    margin: 0 0 10px 0;
}

footer .copyright {
    padding: 15px 0 16px;
    border-top: solid #10d0e7 1px;
    margin-top: 30px;
}

footer .item p strong {
    font-weight: 700;
    margin-bottom: 5px;
    float: left;
    width: 100%;
}

footer {
    display: block;
    overflow: hidden;
    background-color: #0c2326;
    padding: 90px 0 0; 
}

.cpy {
    margin: 0;
    padding: 0;
}

footer .item h4 {
    margin-bottom: 20px;
    font-size: 20px;
    font-weight: 700;
}

.navbar-light .navbar-toggler {
    color: #000;
    background: #4fcaff;
    width: 50px;
    padding: 0;
    height: 45px;
    border: none;
}

@media (min-width: 992px) and (max-width: 1199px) {

}

@media (min-width: 768px) and (max-width: 991px) {

.ovarlay_slide_cont {
    background: rgba(5,3,0,0.63);
    position: absolute;
    width: 70%;
    margin: 0 15%;
    z-index: 1111111111;
    top: 0;
    left: 0;
    padding: 50px 60px 70px;
}

.ovarlay_slide_cont h2 {
    font-size: 45px;
}

.ovarlay_slide_cont p {
    color: #fff;
    font-weight: 300;
    margin: 0 0 30px 0;
    font-size: 19px;
    padding: 0;
    line-height: 28px;
}    

.h3, h3 {
    font-size: 30px;
}

.about_section h3 {
    font-size: 30px;
}

.about_section h4 {
    color: #4fcaff;
    font-size: 16px;
    margin: 0;
}

h3.blog_head {
    width: 100%;
    float: left;
    background: #fff;
    text-align: center;
    font-size: 18px;
    text-transform: uppercase;
    color: #090101;
    margin: 0;
    min-height: 50px;
    line-height: 50px;
}

.service_blog h3.blog_head {
    float: left;
    background: #4fcaff;
    text-align: center;
    font-size: 18px;
    text-transform: none;
    margin: 0;
    min-height: 50px;
    line-height: 50px;
    padding: 0 20px;
    color: #fff;
    position: absolute;
    bottom: 0;
    width: 65%;
    max-width: 300px;
    left: 15px;
    font-weight: 500;
}

.service_blog h3.blog_head::after {
    width: 50px;
    height: 50px;
    content: "";
    display: block;
    position: absolute;
    right: -35px;
    background: #4fcaff;
    top: 0;
    transform: skew(-30deg);
}

.contact-form {
    padding: 40px 50px;
    background: #4fcaff;
    min-height: 600px;
    margin-top: 60px;
}

.service_blog img {
    width: 100%;
}

}

@media (max-width: 767px) {

.layout_padding {
    padding: 50px 0;
}

.about_section h3 {
    font-size: 30px;
    margin: 10px 0 25px 0;
    font-weight: 700;
    line-height: 32px;
}

.h3, h3 {
    font-size: 30px;
    font-weight: 700;
    color: #3a3a3a;
    text-transform: uppercase;
    margin-bottom: 15px;
}

h3.blog_head {
    width: 100%;
    float: left;
    background: #fff;
    text-align: center;
    font-size: 20px;
    text-transform: uppercase;
    color: #090101;
    margin: 0;
    min-height: 55px;
    line-height: 55px;
}

.service_blog h3.blog_head {
    float: left;
    background: #4fcaff;
    text-align: center;
    font-size: 22px;
    text-transform: none;
    margin: 0;
    min-height: 50px;
    line-height: 50px;
    padding: 0 40px;
    color: #fff;
    position: absolute;
    bottom: 0;
    width: 70%;
    max-width: 300px;
    left: 15px;
}

.contact-form {
    padding: 35px 40px;
    background: #4fcaff;
    min-height: 600px;
    margin-top: 20px;
}

.contact-form form input {
    margin: 10px 0;
}

#contact img {
    margin-top: 30px;
}

.testimonial_blog {
    background: #a1a1a1;
    width: 100%;
    padding: 30px 30px;
    box-shadow: 10px 10px 0 0 #4fcaff;
}

.testimonial_blog p:first-child {
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 10px;
}

p {
    font-size: 17px;
    font-weight: 300;
}

.subcribe form {
    height: auto;
    background: #fff;
    margin-top: 20px;
    padding: 0;
    font-weight: 300;
    font-size: 19px;
    display: block;
}

.subcribe form input {
    margin: 0;
    padding: 20px 30px;
    width: 100%;
    border: none;
    font-size: 20px;
    font-weight: 300;
}

.subcribe form button {
    background: #fa3e19;
    color: #fff;
    width: 100%;
    border: none;
    font-size: 20px;
    padding: 12px 0;
}

.subcribe form button:hover,
.subcribe form button:focus {
    background: #111;
    color: #fff;
}

.ovarlay_slide_cont {
    display: none;
}

.service_blog img {
    width: 100%;
}

}
