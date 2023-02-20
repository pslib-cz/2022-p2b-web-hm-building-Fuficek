
https://pslib-cz.github.io/2022-p2b-web-hm-building-Fuficek/

* [ ] HTML není validní— překontrolujte ve validátoru a vyřešte chyby (a doporučení) 
* [ ] Navigaci strukturovat jako **nav menu li a** viz výklad ve výuce 
* [ ] Správný **h1** hlavní stránky je celý řetězec „HM Building.cz s.r.o. liberecká stavební společnost", ne jen jeho část 
* [ ] **h1** může být na stránce pouze jednou 
* [ ] Namísto **div** lépe strukturovat obsah stránky třeba do **section**, ideálně bloky obsahu (služby, kontejner s <a target="blank" href="https://www.terapie-autismu.cz/">CTA</a>) 
* [ ] Atribut alt u <img> by měl obsahem vypovídat o obrázku, viz Koderovo desatero 
* [ ] Nepojmenovávejte obrázky s diakritikou a nepoužívejte v názvech mezery (nahraďte - nebo _). Dělá to jen problémy. 
* [ ] V kontejneru .page--header je **section** použit nesprávně, text by měl obalovat **p**
* [ ] Konkrétní reference na hlavní stránce musí být proklikávatelné — odkaz vede na detail reference 
* [ ] V kontakt.html jsou kontaktní údaje (tel., mobil, adresa) klikatelné odkazy. 
* [ ] font nastavujte v jednotkách em/rem a ne v px namísto px používejte em/rem i mimo text 
* [ ] Na webu používáte nadbytečně flexbox, viz například „.pagecontent", „.pag--header", „.services", na index stránce. Respektujte přirozený tok obsahu stránky (content flow). Do sloupce to není vždy potřeba „cpát" flexboxem — zkuste je povypínat a zjistíte, že to dělá totéž. Pracujte s box modelem. 
* [ ] Chybí ikona hamburger menu v navigaci + navigace není na mobilu funkční. 
* [X] Kontejner .main--header by neměl být přes celou výšku obrazovky (100vh), ale třeba max. 80vh. Viz grafický návrh. 
