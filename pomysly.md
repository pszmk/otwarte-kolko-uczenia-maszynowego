### Komponenty OKUM
DISCLAIMER: każdy materiał powinien być warstwowy czyli w kolejnych tygodniach grupy robią z grubsza te same zagadnienia, ale bardziej zaawansowane grupy mają więcej wyprowadzeń i więcej modyfikacji vanillla wersji (więcej własnego czytania i szukania)
## Kurs
- pytorch

Z boku bardziej standardowy ML i statystyka w różnych odsłonach
- scikit learn, xgboost ipt.
- scipy
- statsmodels
- matplotlib + seaborn
- darts

### Teoria
- materiał wykładowy (gotowy filmik z internetu np.)
- skrypt pdf (może być gotowy z internetu podlinkowany póki co, ale do zrobienia od podstaw z cytacjami) + bazowana na nim skracająca prezentacja (ze skryptem do prezentowania) + nagranie mini wykładu z tą prezentacją
- lista ćwiczeń pdf do zrobienia na kartce - tu też nowa teria może się pojawiać jak to bywa w ćwiczeniach
- ANKI - fiszki do kluczowych elementów (czyli powiedzmy wyprowadzeń ważniejszych i pojęć) około 5-10 na zajęcia ~ 150 na semestr
## Praktyka
- notatnik laboratoryjny z TODO + odpowiedzi udostępnianie na następnych zajęciach (zadanie to przejść zapisane testy czy sprawdzenia)
- Zadania główne - po prostu większe notebooki z TODO do zrobienia - mają być dobrze przygotowane, aby robić je dla własnego zrozumienia, bo będą recyclowane (może figurować kilka wersji bazowanych na tym samym source codzie) - muszą być dobrze zrevievowane, tak aby było wiadomo o co chodzi w zadaniu + podane źródła do kopiowania ewentualnego
- mniejsze zadania dodatkowe do prezentacji indywidualnej na zajęciach (wprowadzają mini pomysły do sprawdzenia i poszerzenia wiedzy) (prowadzący do kogoś podchodzi, jak inni chcą posłuchać to mogą podejść) + zadania przygotowuje się w osobnym notatniku
## Challenge Kaggle
- (co 2-4 tygodnie, zależy od kalibru) mniejsze skopiowane konkursy założone na Kaggle dla uczestników kółka z udostępnianiem całego kodu z wyjaśnieniami po konkursie (ze zróżnicowanymi typami danych i zastosowaniami ML (tak samo warstwowo dla różnych poziomów zaawansowania))
## Projekty
- najpierw zbierana jest baza pomysłów rozwiązania a później robiony jest reasearch
- praca indywidualna lub drużynowa, ale całe kółko się tym zajmuje wspólnie poniekąt i wgryza w jeden temat (ale można też robić wybrany przez siebie projekt, lub nie robić wgl), któś musi nadzorować postęp projektu i pomagać uczestnikom
- rezultat = wytrenowany i zapisany model do ewaluacji
- generowanie pixelartów (+mnist jako first stage - mały raczej nie 28x28 tylko mniejszy)
- klasyfikacja audio - gra z zaklęciami, uruchamianie głosem tych zaklęć i uodpornienie na różne mikrofony i dźwięki w tle (rozpisanie całego grafu/drzewa podejść i podlinkowanie zasobów)
- praktyczne np.CrewAI
- researchowe - implementacje
## Punkty
## Feedback loop
- Zgłaszanie Issues na repo dot. jakości materiałów oraz modyfikacji
## Motywacja dla każdego uczestnika/Retencja mówiąc brzydko
- Dlaczego warto robić rzeczy?
- Dlaczego te konkretne zajęcia mogą być rozwijające?
- Jak podchodzić do trudności?
- Jak zacząć własne poszukiwania wartości?
- Jak można defiiować szerzeej zanczenie w życiu? Dlaczego praca na kółku może przynosić znaczenie przy różnych systemach wartości? Uczciwie - dlaczego może nie przynosić -> indywidualna przestrzeń na refleksję. Bez narzucanej agendy, ale poruszenie ważnego i pomijanego tematu w kontekście podejmowania trudu poszerzania wiedzy. Wylistowac motywacje: do rywalizacji po "tzw ulepszanie świata"
- Zbijanie argumentów typu: to mi się nie przyda, to jest za trudne, z tego nie będzie chleba -> podstawy matematyczne i statystyczne przydatne w każdej dziedzinie z przykładami (+ zaznaczenie, że w tych dziedzinach można robić inne rzeczy, aby do nich nie zrazić zrozpaczonej osoby, która nie lubi tematu kółka)
- O ulepszaniu siebie, a nie swojej percepcji w grupie. O porównywaniu siebie do siebie a nie "lepszych" i umniejszaniu siebie. O uczeniu się od "lepszych". Jak uznam, że nie robię bo są lepsi to będę gorszy od siebie gdybym zrobił :)
## Jak się uczyć czegokolwiek
- Podlinkowanie gradacji materiałów opartych o naukowe przesłanki lub badania o tym co wpływa na kondycję mentalną (umysł = ciało itp, psychologia -> procesy mentalne)
## Baza implementacji paperów - można robić contribute

- handout, pierwsza warstwa to liniowa kombinacja (weight decay zjada inicjalizację) podpunkt (a) bez weight decay (b) z weight decay
- Convolucja powinna robić position agnostic featury, ale padding pozwala uczyć się gdzie jest współrzędna. jak?
- Baza przetrenowanych modeli jako kułkowe projekty:
- vae do różnych modalności zdj, audio, video, 
- ortogonalna dekompozycja macierzy kowariancji i pokazanie, że to są kierunki zmienności
- softmax a routing gradientu, max i routing gradientu (mimo nieróżniczkowalności)

- segmentacja: założenie o niezależności na końcu, jak wziąć maskę najprawdpobodobniejszą z jioint pdf? threhs = 0.5

- Do nauki tokenów i transformerów stworzyć kilka kafelków głowa z nogami, tułów, koniec dla różnych zwierząt i robione są szlaczki z poskładanymi zwierzami, urządzeniami miastami itd (algo ma nie mieszać aut ze zwierzakami i rozciągać prawidłow odpowiedni kafelki) (mało tokenów + ładne wizualnie), kafelki -> tokeny -> kofelki

- przesyłanie obrazka przez AE wielokrotnie i wrzucanie rekonstrukcji, aż zbiegnie i wytłumaczenie czemu tak się stało