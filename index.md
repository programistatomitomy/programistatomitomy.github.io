<!-- Wszelkie nazwy, imiona i nazwiska są przykładowymi danymi. Strona ma charakter edukacyjny. -->
<!DOCTYPE html>
<html lang="pl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://kit.fontawesome.com/732a285ee6.js" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (min-width: 579px)" href="css/small.css">
    <link rel="stylesheet" media="screen and (min-width: 768px)" href="css/medium.css">
    <link rel="stylesheet" media="screen and (min-width: 992px)" href="css/large.css">
</head>

<body>
    <header id="up">
        <div class="header-img">
            <div class="header-logo">
                <p>Car<span>Perfect</span></p>
                <div class="header-logo-line"></div>
            </div>
            <div class="header-text">
                <h1>mechanika pojazdowa nie ma przed nami tajemnic...</h1>
            </div>
            <a href=""><button>umów wizytę</button></a>
            <nav class="mobile">
                <div class="nav-mobile">
                    <button><i class="fas fa-bars"></i></button>
                </div>
            </nav>
            <div class="header-hero-bg"></div>
        </div>
    </header>
    <nav class="desktop">
        <ul>
            <li><a href="#up">o nas</a></li>
            <li><a href="#service">usługi</a></li>
            <li><a href="#team">team</a></li>
            <li><a href="#contact">kontakt</a></li>
        </ul>
    </nav>
    <main>
        <section class="container about-us">
            <h2>o nas</h2>
            <div class="section-h2-line"></div>
            <p>Do CarPerfect przystąpiło już ponad 1900 serwisów samochodowych w Polsce, Czechach i na Słowacji,
                w których sprawdzeni mechanicy każdego dnia obsługują i naprawiają setki samochodów. Sieć stale się
                rozwija, a jej główne założenia to intensywne wsparcie biznesowe, technologiczne, informatyczne,
                promocyjne i szkoleniowe dla zrzeszonych warsztatów.</p>
            <p>Sieć CarPerfect wspiera przede wszystkim obsługę samochodów osobowych, flotowych oraz dostawczych
                i
                w tych kierunkach pomaga rozwijać się zrzeszonym serwisom samochodowym.
                W CarPerfect wspólnie osiągamy efekt skali, którego znakomita większość warsztatów nie byłaby w
                stanie wypracować w pojedynkę oraz wzmacniamy przedstawicieli sieci w obszarach tego wymagających, nie
                tłumiąc przy tym ich niezależności.</p>
        </section>
        <section id="service">
            <h2>usługi</h2>
            <div class="section-h2-line"></div>
            <div class="section-two-bgc">
                <div class="container">
                    <div class="services">
                        <img src="img/checklist.png" alt="checklist">
                        <div class="services-paragraphy">
                            <p><i class="far fa-check-circle"></i>Wymiana oleju i płynów</p>
                            <p><i class="far fa-check-circle"></i>Pełen serwis klimatyzacji</p>
                            <p><i class="far fa-check-circle"></i>Naprawa układu wydechowego</p>
                            <p><i class="far fa-check-circle"></i>Naprawa układu hamulcowego</p>
                            <p><i class="far fa-check-circle"></i>Diagnostyka komputerowa</p>
                            <p><i class="far fa-check-circle"></i>Remonty silników samochodowych</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="team" class="container">
            <h2>team</h2>
            <div class="section-h2-line"></div>
            <article>
                <div class="avatar img-avatar img-zenon"></div>
                <div class="position">
                    <h4>Zenon Balcerzak</h4>
                    <p>Prezes CarPerfect</p>
                </div>
            </article>
            <article>
                <div class="avatar img-avatar img-czarek"></div>
                <div class="position">
                    <h4>Cezary Bolesławicz</h4>
                    <p>Główny mechanik</p>
                </div>
            </article>
            <article>
                <div class="avatar img-avatar img-marcin"></div>
                <div class="position">
                    <h4>Marcin Zagórski</h4>
                    <p>Pomocnik mechanika</p>
                </div>
            </article>
        </section>
        <section id="contact">
            <h2>kontakt</h2>
            <div class="section-h2-line"></div>
            <div class="section-contact-bgc">
                <div class="container">
                    <div class="contact">
                        <p><i class="phone fas fa-phone"></i> +48 000 000 000</p>
                        <p><i class="email fas fa-at"></i> adres@mailowy.pl</p>
                        <h3>adres</h3>
                        <p>ul. Waniliowa 1</p>
                        <p>05-500 Białystok</p>
                    </div>
                </div>
            </div>
        </section>
        <footer>
            <p>Copyright &copy;2020 CarPerfect. All rights reserved.</p>
            <div class="up">
                <a href="#up"><i class="fas fa-angle-double-up"></i></a>
            </div>

        </footer>
    </main>
</body>

</html>
