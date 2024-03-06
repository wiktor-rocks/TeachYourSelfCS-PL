# Naucz się Informatyki na własną rękę

[Ten dokument markdown to polskie tłumaczenie teachyourselfcs.com.](https://teachyourselfcs.com/)

[Strona internetowa polskiego tłumaczenia.](https://wiktor-rocks.github.io/TeachYourSelfCS-PL/)

Uwaga: ten przewodnik był szeroko zaktualizowany w maju 2020 roku. Do poprzedniej wersji, [kliknij tutaj](https://teachyourselfcs.com/2016/).

Jeśli jesteś samoukiem lub absolwentem bootcampu, powinieneś nauczyć się informatyki. Na szczęście możesz zdobyć światowej klasy wykształcenie w tej dziedzinie bez wieloletniego studiowania i wydawania fortuny na dyplom 💸.

Jest wiele dostępnych zasobów, ale niektóre są lepsze od innych. Nie potrzebujesz kolejnej listy "200+ darmowych kursów online". Potrzebujesz odpowiedzi na te pytania:

- **Jakich tematów** powinieneś się nauczyć i dlaczego?
- Jaka jest **najlepsza książka lub seria wykładów wideo** dla każdego tematu?

Ten poradnik jest naszą próbą udzielenia ostatecznych odpowiedzi na te pytania.

## TL;DR (Podsumowanie):

Przestudiuj wszystkie dziewięć tematów poniżej, mniej więcej w podanej kolejności, korzystając z podręcznika lub serii wykładów video, ale idealnie z obu. Poświęć około 100-200 godzin na każdy temat, a następnie powracaj do ulubionych tematów w trakcie swojej kariery 🚀.

|Temat|Dlaczego warto się go nauczyć?|Książka|Wykłady video|
|---|---|---|---|
|**[Programowanie](#programowanie)**|Nie bądź osobą, która "nigdy do końca nie zrozumiała" czegoś takiego jak rekurencja.|_Structure and Interpretation of Computer Programs_|Wykłady Briana Harveya z Berkeley CS 61A|
|**[Architektura komputerów](#architektura-komputerów)**|Jeśli nie masz solidnego modelu mentalnego tego, jak komputer faktycznie działa, wszystkie twoje wyższo poziomowe abstrakcje będą kruche.|_Computer Systems: A Programmer's Perspective_|Berkeley CS 61C|
|**[Algorytmy i struktury danych](#algorytmy-i-struktury-danych)**|Jeśli nie umiesz korzystać z powszechnych struktur danych, takich jak stosy, kolejki, drzewa i grafy, nie będziesz w stanie rozwiązywać trudnych problemów.|_The Algorithm Design Manual_|Wykłady Stevena Skieny|
|**[Matematyka dla informatyków](#matematyka-dla-informatyków)**|Informatyka to w zasadzie rozgałęzienie stosowanej matematyki, więc nauka matematyki da ci przewagę konkurencyjną.|_Mathematics for Computer Science_|Wykłady Toma Leightona z MIT 6.042J|
|**[Systemy operacyjne](#systemy-operacyjne)**|Większość pisanego przez Ciebie kodu jest egzekwowana przez system operacyjny, więc powinieneś wiedzieć, jak te elementy współdziałają ze sobą.|_Operating Systems: Three Easy Pieces_|Berkeley CS 162|
|**[Sieci komputerowe](#sieci-komputerowe)**|Internet okazał się wielką sprawą: zrozum jego działanie, aby odblokować jego pełen potencjał.|_Computer Networking: A Top-Down Approach_|Stanford CS 144|
|**[Bazy danych](#bazy-danych)**|Dane są w sercu większości ważnych programów, ale niewiele osób rozumie, jak działają systemy bazodanowe.|_Readings in Database Systems_|Wykłady Joe Hellersteina z Berkeley CS 186|
|**[Języki i kompilatory](#języki-i-kompilatory)**|Jeśli zrozumiesz, jak faktycznie działają języki i kompilatory, będziesz pisać lepszy kod i łatwiej nauczysz się nowych języków.|_Crafting Interpreters_|Kurs Alexa Aikena na edX|
|**[Systemy rozproszone](#systemy-rozproszone)**|W dzisiejszych czasach, większość systemów to systemy rozproszone.|_Designing Data-Intensive Applications_ Martina Kleppmanna|MIT 6.824|

## Wciąż za dużo?

Jeśli idea samodzielnego studiowania 9 tematów w ciągu kilku lat wydaje ci się przytłaczająca, sugerujemy skupienie się na dwóch książkach: _Computer Systems: A Programmer's Perspective_ i _Designing Data-Intensive Applications_. Naszym zdaniem, te dwie książki zapewniają niezwykle wysoki zwrot z zainwestowanego czasu, szczególnie dla samouków i absolwentów bootcampów pracujących nad aplikacjami sieciowymi. Mogą również służyć jako "wprowadzenie" do pozostałych wymienionych tematów i zasobów.

## Dlaczego warto uczyć się informatyki?

Istnieją 2 typy inżynierów oprogramowania: tacy, którzy rozumieją informatykę na tyle dobrze, by pracować nad trudnymi, innowacyjnymi zagadnieniami, oraz tacy, którzy radzą sobie, ponieważ znają kilka narzędzi wysokiego poziomu.

Obie grupy nazywają siebie inżynierami oprogramowania i na początku kariery zarabiają podobne kwoty. Jednak inżynierowie typu 1 z czasem przechodzą do bardziej satysfakcjonującej i lepiej płatnej pracy, czy to komercyjnej, czy przełomowych projektów open source, obejmują stanowiska liderskie lub dokonują wysokiej jakości indywidualnych wkładów.

Inżynierowie typu 1 znajdują sposoby na dogłębne poznanie informatyki, czy to tradycyjnymi metodami, czy przez nieustanne uczenie się w trakcie kariery. Inżynierowie typu 2 zwykle pozostają na powierzchni, ucząc się konkretnych narzędzi i technologii, a nie ich podstawowych założeń, i przyswajają nowe umiejętności tylko gdy zmienia się technologiczna moda.

Aktualnie liczba osób wkraczających do branży szybko rośnie, podczas gdy liczba absolwentów informatyki jest względnie stała. Nadmiar inżynierów typu 2 zaczyna ograniczać ich szanse zatrudnienia i trzymać z dala od najciekawszych zajęć w branży. Niezależnie od tego, czy dążysz do bycia inżynierem typu 1, czy po prostu szukasz większego bezpieczeństwa pracy, nauka informatyki jest jedyną niezawodną ścieżką.

> Globalny system SMS obsługuje około 20 mld wiadomości dziennie. WhatsApp obsługuje 42 mld. Z 57 inżynierami. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)
> 
> – Benedict Evans (@BenedictEvans) [2 luty 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

[![](https://pfst.cf2.poecdn.net/base/image/0c0e45dafd1ebc8187ec04c3b7496fdee6c7420059c382b155009c09b769f000?w=635&h=557&pmaid=49959650)](https://twitter.com/jenna/status/838161631662092289)

## Przewodniki tematyczne

### Programowanie

Większość studiów informatycznych licencjackich zaczyna się od "wprowadzenia" do programowania komputerów. Najlepsze wersje tych kursów skierowane są nie tylko do początkujących, ale także do tych, którzy przegapili przydatne koncepcje i modele programowania, ucząc się kodowania po raz pierwszy.

Nasz standardowy wybór do nauki tej tematyki, to klasyczna pozycja _Structure and Interpretation of Computer Programs_, dostępna za darmo online zarówno jako [książka](https://sarabander.github.io/sicp/html/index.xhtml), jak i [zbiór wykładów wideo z MIT](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video_galleries/video-lectures/). Choć te wykłady są świetne, zamiast nich sugerujemy obejrzeć [wykłady Briana Harveya dot. SICP](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (dla kursu 61A na Berkeley). Są one bardziej dopracowane i lepiej skierowane do nowych studentów niż wykłady z MIT.

Polecamy przerobienie przynajmniej trzech pierwszych rozdziałów SICP i wykonanie ćwiczeń. Dodatkową praktykę zapewni rozwiązywanie zestawu małych zadań programistycznych, takich jak te z serwisu [exercism](http://exercism.io/).

Odkąd ten poradnik został opublikowany po raz pierwszy w 2016 roku, jedno z najczęściej zadawanych pytań dotyczy tego, czy rekomendujemy nowsze nagrania kursu 61A prowadzonego przez Johna DeNero i/lub odpowiadającą im książkę _[Composing Programs](https://composingprograms.com/)_, która podąża "w ślady SICP", ale używa Pythona. Uważamy, że materiały DeNero są również świetne i niektórzy studenci mogą je preferować, ale wciąż sugerujemy najpierw spróbować SICP, Scheme i wykładów Briana Harveya.

Dlaczego? Ponieważ SICP jest wyjątkowy w swojej zdolności - przynajmniej potencjalnie - do zmiany twoich fundamentalnych przekonań na temat komputerów i programowania. Nie każdy doświadczy tego. Niektórzy znienawidzą tę książkę, inni nie przebrną dalej niż przez pierwsze kilka stron. Ale potencjalne korzyści sprawiają, że warto spróbować.

Jeśli SICP ci się nie spodoba, wypróbuj _Composing Programs_. Jeśli to ciągle nie pasuje, spróbuj _[How to Design Programs](http://www.htdp.org/)_. Jeśli żadna z tych pozycji nie wydaje się proporcjonalnie nagradzać twojego wysiłku, być może jest to znak, że powinieneś na jakiś czas skupić się na innych tematach i wrócić do programowania za rok czy dwa.

Na koniec wyjaśnienie: ten poradnik NIE jest przeznaczony dla całkowitych początkujących w programowaniu. Zakładamy, że jesteś kompetentnym programistą bez wykształcenia informatycznego, który chce uzupełnić braki w wiedzy. Fakt, że uwzględniliśmy sekcję o "programowaniu" jest po prostu przypomnieniem, że może być więcej do nauczenia się w tej dziedzinie. Dla osób, które nigdy wcześniej nie programowały, ale chciałyby się tego nauczyć, lepszy może być taki poradnik jak [ten](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

[![Structure and Interpretation of Computer Programs](https://pfst.cf2.poecdn.net/base/image/5daae9b7e356f6e95e6a11240aad9e2b0eb15dab0cd9941132c9fe636166efb9?w=207&h=300&pmaid=49960236)](https://sarabander.github.io/sicp/html/index.xhtml)

### Architektura komputerów

Architektura komputerów - czasem nazywana "systemami komputerowymi" lub "organizacją komputera" - stanowi ważne spojrzenie na obliczenia poniżej powierzchni oprogramowania. Naszym zdaniem, jest to najbardziej zaniedbywany obszar wśród samouków-programistów.

Nasz ulubiony podręcznik to _[Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html)_, a typowy kurs wprowadzający do architektury komputerów z tej książki [obejmowałby](http://csapp.cs.cmu.edu/3e/courses.html) większość rozdziałów 1-6.

Uwielbiamy CS:APP za praktyczne, zorientowane na programistów podejście. Choć w architekturze komputerów jest o wiele więcej niż to, co pokrywa książka, stanowi ona świetny punkt startu dla tych, którzy chcieliby zrozumieć systemy komputerowe przede wszystkim po to, aby pisać szybsze, wydajniejsze i niezawodne _oprogramowanie_.

Dla osób, które wolałyby łagodniejsze wprowadzenie w temat i równowagę między sprzętem a oprogramowaniem, polecamy _The Elements of Computing Systems_, znane również jako „Nand2Tetris”. To ambitna książka, która stara się dać spójne zrozumienie tego, jak działa komputer. Każdy rozdział obejmuje budowanie małego fragmentu całego systemu - od pisania elementarnych bramek logicznych w HDL, przez CPU i asemblery, aż do aplikacji wielkości gry Tetris.

Polecamy przeczytanie pierwszych sześciu rozdziałów książki i wykonanie towarzyszących im projektów. Rozwinie to twoje rozumienie relacji między architekturą maszyny a działającym na niej oprogramowaniem.

Pierwsza połowa książki (i wszystkie projekty) jest dostępna za darmo na stronie [Nand2Tetris](http://www.nand2tetris.org/). Jest też dostępna jako [kurs na Courserze z materiałami wideo](https://www.coursera.org/learn/build-a-computer).

Dążąc do prostoty i spójności, Nand2Tetris poświęca głębię tematu. W szczególności, dwa bardzo ważne koncepty nowoczesnej architektury komputerów - potokowanie i hierarchia pamięci - są prawie całkowicie nieobecne w tekście.

Gdy poczujesz się komfortowo z treścią Nand2Tetris, sugerujemy albo powrót do CS:APP, albo sięgnięcie po doskonały i już klasyczny podręcznik Pattersona i Hennessy'ego _[Computer Organization and Design](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269)_. Nie wszystkie sekcje w książce są niezbędne; sugerujemy podążanie za kursem Berkeley CS61C "Great Ideas in Computer Architecture" aby wybrać konkretne fragmenty do przeczytania. Notatki i laboratoria są dostępne online, a nagrania dawnych wykładów można znaleźć [w Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

[![Computer Systems: A Programmer's Perspective](https://pfst.cf2.poecdn.net/base/image/10acba8462df44d602229f29fdb9aadd90a1b8cbd6fd6dd9449e99040d2cfac0?w=389&h=499&pmaid=49960532)](http://csapp.cs.cmu.edu/3e/home.html)

> Sprzęt jest platformą

– Mike Acton, dyrektor silnika w Insomniac Games  
([obejrzyj jego wykład z CppCon](https://www.youtube.com/watch?v=rX0ItVEVjHc))

### Algorytmy i struktury danych

Zgadzamy się z wieloletnią powszechną mądrością, że zaznajomienie się z typowymi algorytmami i strukturami danych jest jednym z najbardziej wartościowych aspektów edukacji w informatyce. To także świetne miejsce do trenowania ogólnych zdolności rozwiązywania problemów, co przyniesie korzyści w każdym innym obszarze studiów.

Jest dostępnych setki książek, ale nasz ulubiony to _[The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)_ Stevena Skieny. On wyraźnie kocha algorytmiczne rozwiązywanie problemów i zwykle udaje mu się zaszczepić podobny entuzjazm w swoich studentach i czytelnikach. Naszym zdaniem, dwa bardziej popularne podręczniki (CLRS i Sedgewick) mają tendencję do zbytniego skupiania się na dowodach dla osób uczących się głównie w celu poprawienia praktycznych umiejętności rozwiązywania problemów.

Dla preferujących wykłady wideo, [Skiena hojnie udostępnia swoje online](https://www3.cs.stonybrook.edu/~skiena/373/videos/). Podobają nam się również wykłady Tima Roughgardena, dostępne [na Courserze](https://www.coursera.org/specializations/algorithms) oraz [gdzie indziej](http://timroughgarden.org/videos.html). Który styl wykładu bardziej ci odpowiada - Skieny czy Roughgardena - będzie kwestią osobistych preferencji. W rzeczywistości istnieje kilkanaście dobrych alternatyw, więc jeśli znajdziesz inną, która ci odpowiada, zachęcamy do trzymania się jej!

Do ćwiczeń polecamy rozwiązywanie zadań na stronie [Leetcode](http://leetcode.com/). Zwykle są to interesujące problemy z dołączonymi rozwiązaniami i dyskusjami. Pomogą również sprawdzić twój postęp na pytaniach często wykorzystywanych na rozmowach technicznych w bardziej konkurencyjnych firmach programistycznych. Sugerujemy rozwiązanie około 100 losowych zadań z Leetcode w ramach nauki.

Na koniec, mocno polecamy _[How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)_ jako świetny i wyjątkowy przewodnik po ogólnym rozwiązywaniu problemów; jest równie zastosowalny w informatyce, co w matematyce.

[![The Algorithm Design Manual](https://pfst.cf2.poecdn.net/base/image/8fef1931c7b51d0e19995e64629aa26452ad0db28354f73572c3ca43cee90948?w=216&h=300&pmaid=49960801)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![How to Solve It](https://pfst.cf2.poecdn.net/base/image/b4224931d49f1f245f8807c5bfb9e6a08768374a0a15c1402388a9e35a9661b8?w=194&h=300&pmaid=49960817)](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)

> Mam tylko jedną metodę, którą gorąco polecam - nazywa się pomyśl zanim zaczniesz pisać.

— Richard Hamming

### Matematyka dla informatyków

W pewnym sensie informatyka jest przerośniętą gałęzią matematyki stosowanej. Podczas gdy wielu programistów próbuje - z różnym skutkiem - to zignorować, my zachęcamy, żebyś zgłębił ten temat bezpośrednio. Pomyślne zrobienie tego zapewni ci ogromną przewagę nad tymi, którzy tego nie zrobią.

Najbardziej istotnym obszarem matematyki dla informatyki jest szeroko pojęta "matematyka dyskretna", gdzie "dyskretny" jest przeciwieństwem "ciągły" i jest luźnym zbiorem interesujących zagadnień matematyki stosowanej poza rachunkiem różniczkowym i całkowym. Ze względu na niejasną definicję, nie ma sensu próbować objąć całą szerokość "matematyki dyskretnej". Bardziej realistycznym celem jest zbudowanie działającego zrozumienia logiki, kombinatoryki i rachunku prawdopodobieństwa, teorii mnogości, teorii grafów oraz odrobiny teorii liczb przydatnej w kryptografii. Algebra liniowa to dodatkowy warty zgłębienia obszar ze względu na jej znaczenie w grafice komputerowej i machine learning.

Nasz sugerowany punkt startu dla matematyki dyskretnej, to zestaw [notatek wykładowych László Lovásza](https://cims.nyu.edu/~regev/teaching/discrete_math_fall_2005/dmbook.pdf). Profesor Lovász dobrze sobie poradził z uczyinieniem treści przystępnej i intuicyjnej, więc stanowią one lepszy punkt startu niż bardziej formalne podręczniki.

Do bardziej zaawansowanego studiowania polecamy _[Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)_, notatki wielkości książki z kursu MIT o tej samej nazwie. Wykłady wideo z tego kursu są również [dostępne za darmo](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/video_galleries/video-lectures/) i stanowią naszą rekomendowaną serie wykładów video z matematyki dyskretnej.

Jeśli chodzi o algebrę liniową, sugerujemy rozpoczęcie od serii filmów [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), a następnie książki i wykładów [Gilberta Stranga](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

> Jeśli ludzie nie wierzą, że matematyka jest prosta, to tylko dlatego, że nie zdają sobie sprawy, jak skomplikowane jest życie.

— John von Neumann

### Systemy operacyjne

_[Operating System Concepts](https://www.amazon.com/dp/1118063333/)_ (potocznie "Książka o dinozaurach") oraz _[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_ to "klasyczne" książki o systemach operacyjnych. Obie zebrały krytykę za brak przejrzystości i ogólną niechęć studentów do korzystania z nich.

_Operating Systems: Three Easy Pieces_ to dobra alternatywa, [dostępna za darmo online](http://pages.cs.wisc.edu/~remzi/OSTEP/). Szczególnie podoba nam się struktura i czytelność tej książki, a także uważamy, że zawarte w niej ćwiczenia są warte uwagi.

Po lekturze OSTEP, zachęcamy do zgłębienia decyzji projektowych konkretnych systemów operacyjnych, sięgając po książki w stylu "XYZ OS Internals", takie jak _[Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_ oraz _[Mac OS X Internals](https://www.amazon.com/Mac-OS-X-Internals-Systems-Approach/dp/0321278542/)_. Jeśli chodzi o Linuksa, polecamy fantastyczną książkę Roberta Love, [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468).

Świetnym sposobem na utrwalenie wiedzy o systemach operacyjnych jest przeczytanie kodu małego jądra systemowego i dodanie do niego własnych funkcji. Jednym z wyborów jest [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), port Unixa V6 na ANSI C i x86, utrzymywany na potrzeby kursu na MIT. Na końcu OSTEP znajduje się appendix z pomysłami na [laboratoria xv6](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) wypełnione świetnymi pomysłami na projekty.

[![Operating Systems: Three Easy Pieces](https://teachyourselfcs.com/ostep.jpeg)](http://pages.cs.wisc.edu/~remzi/OSTEP/)

### Sieci komputerowe

Biorąc pod uwagę, jak duża część inżynierii oprogramowania dotyczy serwerów i klientów sieciowych, jednym z najbardziej wartościowych obszarów informatyki są sieci komputerowe. Nasi studenci samoucy, którzy metodycznie studiują sieci, zauważają, że nareszcie rozumieją terminy, koncepcje i protokoły, którymi byli otoczeni od lat.

Nasz ulubiony podręcznik do tego tematu, to _[Computer Networking: A Top-Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)_. Zawarte w książce małe projekty i ćwiczenia są warte wykonania, a szczególnie polecamy "Laboratoria Wireshark", które autorzy hojnie udostępnili [online](http://www-net.cs.umass.edu/wireshark-labs/).

Dla preferujących wykłady video, polecamy [_Introduction to Computer Networking_](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS) ze Stanfordu, wcześniej dostępny na platformie Lagunita tej uczelni, ale niestety obecnie dostępny tylko jako nieoficjalne playlisty na YouTube.

> Nie możesz spojrzeć w kryształową kulę i przewidzieć przyszłości. Tym, czym Internet będzie w przyszłości, jest to, czym społeczeństwo go uczyni.

— Bob Kahn

[![Computer Networking: A Top-Down Approach](https://teachyourselfcs.com/top-down.jpg)](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)

### Bazy danych

Samodzielne uczenie się o systemach bazodanowych wymaga więcej pracy niż w przypadku większości innych tematów. To stosunkowo nowa (tzn. powstała po 1970 r.) dziedzina badań, w której istnieją silne komercyjne zachęty, aby pomysły pozostały za zamkniętymi drzwiami. Dodatkowo, wielu potencjalnie znakomitych autorów podręczników woli zakładać firmy lub do nich dołączać, zamiast pisać książki.

W tych okolicznościach, zachęcamy do ogólnego unikania podręczników i rozpoczęcia nauki od [nagrań z kursu CS 186](https://www.youtube.com/user/CS186Berkeley/videos) prowadzonego przez Joe Hellersteina na Berkeley, a następnie przejścia do czytania artykułów naukowych.

Jeden artykuł szczególnie wart polecenia nowym studentom to "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)", który w unikalny sposób dostarcza wysokopoziomowy przegląd działania relacyjnych systemów zarządzania bazami danych. Posłuży on jako przydatny szkielet do dalszej nauki.

_Readings in Database Systems_, lepiej znana jako [baza danych "Czerwona Księga"](http://www.redbook.io/), to zbiór artykułów zebranych i zredagowanych przez Petera Bailisa, Joe Hellersteina oraz Michaela Stonebrakera. Ci, którzy posunęli się dalej niż materiał z CS 186, powinni sięgnąć po Czerwoną Księgę.

Jeśli koniecznie chcesz korzystać z podręcznika, polecamy _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_ autorstwa Ramakrishnana i Gehrke. Bardziej zaawansowanym studentom polecamy klasyczne dzieło Jima Graya _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_, ale nie zachęcamy do traktowania tej pozycji jako materiału do rozpoczęcia nauki.

Na koniec, modelowanie danych to zaniedbywany i źle nauczany aspekt pracy z bazami danych. Nasz sugerowany podręcznik do tego tematu, to _[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_.

[![Readings in Database Systems](https://teachyourselfcs.com/redbook.jpg)](http://www.redbook.io/)[![Data and Reality](https://teachyourselfcs.com/data-reality.jpg)](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)

### Języki programowania i kompilatory

Większość programistów uczy się języków programowania, podczas gdy informatycy uczą się _o_ językach programowania. Daje to informatykowi wyraźną przewagę nad programistą, nawet w dziedzinie programowania! Ich wiedza uogólnia się; są w stanie głębiej i szybciej zrozumieć działanie nowego języka, niż ci, którzy po prostu nauczyli się konkretnych języków.

Nasz sugerowany podręcznik to świetna pozycja _[Crafting Interpreters](https://craftinginterpreters.com/contents.html)_ autorstwa Boba Nystroma, dostępna za darmo online. Jest dobrze zorganizowana, niezwykle interesująca i świetnie nadaje się dla tych, których głównym celem jest po prostu lepsze zrozumienie ich języków programowania i narzędzi do nich. Sugerujemy poświęcenie czasu na przerobienie całości, podejmując wyzwania, które Was zainteresują.

Bardziej tradycyjną rekomendacją jest _[Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)_, potocznie nazywana "Księgą Smoków". Niestety, nie jest ona zaprojektowana do samodzielnej nauki, ale raczej jako materiał dla wykładowców, którzy wybierają z niej tematy na 1-2 semestry swoich kursów.

Jeśli zdecydujecie się korzystać z Księgi Smoków, kluczowe jest, abyście wybierali interesujące Was tematy, idealnie przy wsparciu mentora. W rzeczywistości, nasz sugerowany sposób wykorzystania Księgi Smoków, jeśli zdecydujecie się na nią, to jako dodatkowe źródło referencyjne do serii wykładów wideo. Nasz polecany wybór to [kurs Alexa Aikena na edX](https://www.edx.org/course/compilers).

[![Compilers: Principles, Techniques & Tools](https://teachyourselfcs.com/dragon.jpg)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)

> Nie bądź programistą szablonowym. Zamiast tego, buduj narzędzia dla użytkowników i innych programistów. Weź przykład z przemysłu włókienniczego i stalowego: czy chcesz budować maszyny i narzędzia, czy chcesz obsługiwać te maszyny?

— Ras Bodik na początku swojego kursu o kompilatorach

### Systemy rozproszone

W miarę jak komputery stawały się liczniejsze, także się _rozprzestrzeniły_. Podczas gdy wcześniej firmy kupowały coraz większe mainframe'y, dzisiaj typowe jest, że nawet bardzo małe aplikacje działają na wielu maszynach. Systemy rozproszone zajmują się badaniem, jak rozumować o kompromisach związanych z takim podejściem.

Nasz sugerowany podręcznik do samodzielnej nauki, to _[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)_ autorstwa Martina Kleppmanna. Znacznie lepszy niż tradycyjny podręcznik, DDIA to niezwykle czytelna książka stworzona dla praktyków, która w jakiś sposób unika poświęcenia głębi tematu czy rzetelności.

Ci, którzy szukają bardziej tradycyjnego podręcznika, lub wolą taki, który jest dostępny za darmo online, mogą sięgnąć po _[Distributed Systems, 3rd Edition](https://www.distributed-systems.net/index.php/books/ds3/)_ autorstwa Maartena van Steena i Andrew Tanenbauma.

Preferującym wykłady video polecamy świetny kurs [MIT 6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) prowadzony przez Roberta Morrisa, którego materiały dostępne są [tutaj](https://pdos.csail.mit.edu/6.824/schedule.html).

Niezależnie od wyboru podręcznika czy innych materiałów, nauka systemów rozproszonych absolutnie wymaga czytania artykułów naukowych. Dobry zbiór znajduje się [tutaj](http://dsrg.pdos.csail.mit.edu/papers/), a także gorąco zachęcamy do uczestniczenia w lokalnym rozdziale [Papers We Love](http://paperswelove.org/).

[![Designing Data-Intensive Applications](https://teachyourselfcs.com/ddia.jpg)](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)

## Często zadawane pytania

#### Kto jest docelową grupą odbiorców tego poradnika?

Zakładamy, że jesteś samoukiem-programistą, absolwentem bootcampu, ambitnym uczniem szkoły średniej lub studentem szukającym materiałów do samodzielnej nauki, uzupełniających formalną edukację. Kiedy zacząć tę podróż, to całkowicie osobista decyzja, ale większość osób odnosi korzyści z posiadania doświadczenia zawodowego przed zanurzeniem się zbyt głęboko w teorię informatyki. Na przykład, zauważyliśmy, że studenci _uwielbiają_ uczyć się o systemach bazodanowych, jeśli wcześniej pracowali zawodowo z bazami danych lub o sieciach komputerowych, jeśli pracowali nad projektami webowymi.

#### A co z SI/grafiką/ulubionym tematem X?

Staraliśmy się ograniczyć listę do tematów informatycznych, które uważamy za obowiązkową wiedzę dla _każdego praktykującego inżyniera oprogramowania_, niezależnie od specjalizacji czy branży, ale z naciskiem na systemy. Naszym zdaniem, będą to tematy o najwyższej stopie zwrotu dla zdecydowanej większości samouków i absolwentów bootcampów, dostarczając solidny fundament do dalszej nauki. W rezultacie, znajdziesz się w znacznie lepszej pozycji, aby samodzielnie sięgnąć po podręczniki czy artykuły i poznać kluczowe koncepcje bez specjalnego wsparcia. Oto nasze proponowane punkty startu dla kilku popularnych "zajęć dodatkowych":

- Wprowadzenie do SI: Obiejrzyj [kurs Berkeley AI](http://ai.berkeley.edu/), oglądając nagrania wykładów i wykonując znakomite projekty Pacman. Jako podręcznik, użyj _Artificial Intelligence: A Modern Approach_ autorstwa Russella i Norviga.
- Uczenie maszynowe: Zrób kurs Andrew Ng na Courserze. Bądź cierpliwy i upewnij się, że rozumiesz podstawy zanim rzucisz się w błyszczące nowe tematy takie jak deep learning.
- Grafika komputerowa: Przerób materiały z [Berkeley CS 184](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), używając jako podręcznika _[Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528)_.

#### Jak rygorystyczna jest sugerowana kolejność?

Realistycznie patrząc, wszystkie te tematy mają ze sobą znaczące nachodzenie na siebie i odnoszą się do siebie cyklicznie. Weźmy na przykład relację między matematyką dyskretną a algorytmami: nauka matematyki najpierw pozwoliłaby Ci głębiej analizować i rozumieć Twoje algorytmy, ale nauka algorytmów najpierw dostarczyłaby większej motywacji i kontekstu dla matematyki dyskretnej. Idealnie, wracałbyś do obu tych tematów wiele razy w trakcie kariery.

Dlatego nasza sugerowana kolejność ma przede wszystkim pomóc Ci _w ogóle zacząć_... jeśli masz przekonujący powód, aby preferować inną sekwencję, to śmiało, realizuj swój plan. Naszym zdaniem, najważniejsze "wymagania wstępne" to: architektura komputerów przed systemami operacyjnymi lub bazami danych oraz sieci i systemy operacyjne przed systemami rozproszonymi.

#### Jak to się ma do programów Open Source Society lub freeCodeCamp?

Kiedy ten poradnik powstawał w 2016 r., program [OSS](https://github.com/open-source-society/computer-science) zawierał zbyt wiele tematów, sugerował gorsze materiały do wielu z nich i nie dostarczał żadnego uzasadnienia czy wskazówek, które aspekty poszczególnych kursów są wartościowe. Staraliśmy się ograniczyć listę kursów do tych, które Twoim zdaniem _naprawdę powinien znać_ każdy inżynier oprogramowania, niezależnie od specjalizacji i pomóc Ci zrozumieć, dlaczego każdy kurs został uwzględniony. W kolejnych latach, program OSS poprawił się, ale wciąż uważamy, że ten poradnik dostarcza jaśniejszą, spójniejszą ścieżkę.

freeCodeCamp koncentruje się głównie na programowaniu, nie informatyce. Dlaczego warto uczyć się informatyki, zobacz [powyżej](#dlaczego-warto-uczyć-się-informatyki). Jeśli jesteś nowy w programowaniu, sugerujemy skupienie się na nim najpierw i powrót do tego poradnika za rok czy dwa.

#### A co z językiem X?

Nauka konkretnego języka programowania i uczenie się dziedziny informatyki to zupełnie inna płaszczyzna — nauka języka jest znacznie _łatwiejsza_ i znacznie _mniej wartościowa_. Jeśli znasz już kilka języków, mocno sugerujemy po prostu podążanie za naszym poradnikiem i dopasowywanie nauki języków w lukach lub zostawienie jej na później. Jeśli nauczyłeś się programowania dobrze (np. przez _Structure and Interpretation of Computer Programs_), a zwłaszcza jeśli poznałeś kompilatory, powinno Ci zająć nie więcej niż weekend, żeby przyswoić podstawy nowego języka, a następnie możesz uczyć się o bibliotekach/narzędziach/ekosystemie w pracy.

#### A co z modną technologią X?

Żadna pojedyncza technologia nie jest na tyle istotna, że nauka jej używania powinna być rdzeniem Twojej edukacji. Z drugiej strony, świetnie, że jesteś podekscytowany jej nauką. Kluczem jest praca wstecz od konkretnej technologii do leżącej u jej podstaw dziedziny czy koncepcji i nauka jej dogłębnie zanim zobaczysz, jak Twoja modna technologia pasuje do większego obrazu.

#### Dlaczego wciąż polecasz SICP?

Posłuchaj, po prostu spróbuj. Niektórzy ludzie uważają SICP za zmieniającą życie pozycję, cechę wspólną z bardzo niewieloma innymi książkami. Jeśli Ci się nie spodoba, zawsze możesz spróbować czegoś innego i być może wrócić do SICP później.

#### Dlaczego wciąż polecasz Księgę Smoków?

Księga Smoków wciąż jest najbardziej kompletnym pojedynczym źródłem dot. kompilatorów. Źle się o niej mówi, zwykle za zbytnie skupianie się na pewnych tematach, które dziś uważa się za mniej warte szczegółowego omawiania, takich jak analiza składni. Rzecz w tym, że książka nigdy nie była przeznaczona do czytania od deski do deski, tylko do dostarczenia wystarczającego materiału, z którego wykładowca może złożyć kurs. Podobnie, osoba ucząca się samodzielnie może wybrać własną ścieżkę przez książkę lub lepiej podążyć za sugestiami, które prowadzący publiczne kursy zawarli w planach swoich zajęć.

#### Jak mogę tanio kupić podręczniki?

Wiele podręczników, które polecamy jest dostępnych za darmo online, dzięki hojności ich autorów. W przypadku pozostałych, sugerujemy kupowanie używanych egzemplarzy starszych wydań. Generalnie, jeśli od premiery podręcznika minęło kilka wydań, jest całkiem prawdopodobne, że starsze wydanie będzie w pełni wystarczające. Na pewno nowsza wersja nie jest 10 razy lepsza od starszej, nawet jeśli różnica w cenie na to wskazuje!

#### Kto stworzył ten poradnik?

Pierwotnie poradnik został napisany przez [Oz Novę](https://twitter.com/oznova_) i [Mylesa Byrne'a](https://twitter.com/quackingduck), a aktualizacja z 2020 r. jest autorstwa Oza. Powstał on w oparciu o nasze doświadczenie w nauczaniu podstaw informatyki grup ponad 1000 głównie samouczących się inżynierów i absolwentów bootcampów w małych grupach w San Francisco i online. Dziękujemy wszystkim naszym studentom za nieustanną informację zwrotną na temat materiałów do samodzielnej nauki.

Jesteśmy głęboko przekonani, że przy odpowiedniej ilości czasu i motywacji, mógłbyś samodzielnie nauczyć się wszystkiego powyżej. Ale jeśli wolałbyś intensywny, ustrukturyzowany program z instruktorem, może Cię zainteresować nasz [Computer Science Intensive](https://bradfieldcs.com/csi/). [NIE](https://ozwrites.com/masters/) polecamy studiów magisterskich.
