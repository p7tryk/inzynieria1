zwykle umowa zlecienie lub dzielu


opis procesu
     pojawienie sie potraeby zapytania ofertwoego siwz


wyklad temat

       ww jaki sposob radzic sobie ze zlozonoscia opgrowamowania
       jak organzowac prace duzych zespolow


oprogoramowania
	     twor niematerialny
	     wymagania czesto zlozone roznorodne
	     podatne na zmiany
	     koszt i czas skupiaja sie w procesie projektowania
	     projekty w duzym stopniu niepowtarzalne a techniki wytwarzania nowe
	     wiedza dziedzinowa oldegla od informatycznej


zrodla zlozonosci
       zrowznicowanie dziedzin problemowych
       duze zroznicowanie zespolu projektowego
       orgromna dynamika technologi i srodkow technicznych
       ciagla zmiennosc wymagan i niezdecydowanie uzytkowniukow


ograniczanie zlozonosci
	     zasada dekompozycji
	     zasada abstrakcji
	     zasada ponownego uzycia
	     zasada spryjania naturalnym ludzkim wlasnosciom


inzynieria oprogromaw
	   stara sie zidenfyfikowac i opisac procesy


siedem krokow
       sformulowanie wymagan dla programu lub systemu
       anazliza wymagan i sformulowanie specyfijiacji funkconalnej i strukturalnej systemu
       projekt systemu obecnie w UML
       implementacja, w jezyku wysokiego poziomu
       wreyfikacja
       wdrazanie
       wsparcie


fazy wytwarzania oprogramowanaia
     	planowanie
     	anazliza
		co budujemy
		faza definiowania/okreslenia wymagan
		wyniki dokument specyfikacji wymagani, slownik
    	projektowanie
		faza projektowaniea logicznego
		faza projektowania praktycznego
	implementacja
		tworzenie kodu, uruchamianie testowanie, tworzenie instrukcji
	testowanie i integracji
		testowanie, uzupelnianie dokumentacjo
	etap wdrozenia

	etap utrzymanie
	     support


model kaskadowy wytwarzania oprogramowania
        zalety:
		gwarancja malych zmian szybkosciu

	wady:
		problemy strukturalne zostana jezeli cos robimy na implementacje

model realizacja kierowanej dokumentami


model przyrostowy
      podzial calego produktu na fragmentu

      szczegolowe zdefiniowanie intefejsow miedzy tymi fragmentami


model V
      zespol projektowy opracowuje produkty poszczegolnych
      zespol testujacy


model pragmatyczny


model protyotypow prowizorycznych
      niejasne wymagania


model driven architecture


object managment group - platform specific model


okreslenie wymagan
aby zdefiniowac grupe docelowa szukamy odpowiedzieni na nastepujace pytania
    hajuegi oizuinu zaawansowania biznesowego nalezy oczekiwac od odbiorcow
    jaki poziom szczegolowosci jest porzebny odbiorca
    ile czasu moze grupa docelowa poswiecic na analize i interpretacje modelu
    jezyk definiowana modelu
    	  ogolnie wystepujaca termiologia
	  terminologia specjalistyczna


w okresleniu wymagan uczestniczy klient(znajacy dziedzine zastosowan) i wykonawca(aspekty informatyczne)


**wymaganie funkcjonalne i niefunkcjonalne**


definicja wymagan
	 to ogolny opis wymagan sporzadony w jezyku naturalnym(system powinien...)
specyfikacja wymagan
	 to zapis czecsio ustrukturalizowany, proste notacje tabele formularze


top-down decomposition/bottom-up decomposition


pomocnymi technikami w okdrywaniu wymagan sa
	  poznanie calosci otoczenia systemu
	  wykorzystanie instejacych systemow realizujacych podobne funkcje
	  obserwacje i wywiady z przyszlymi uzytkownikami systemu
	  	     patrzenie na rece, ankiety, organizacje burz mozgow, rozmowa z ekspertami
	  stosowanie scenariuszy wykorzystania systemu
	  modelowanie systemu


cechy dobrych wymagan
      jest kompletny oraz niesprzeczny
      opisuje zwetnetrzne zachowanie systemu z punktu widzenia uzytkownika
      uwzglednia ograniczenia, przy jakich music pracowac system
      klient nie wie w jaki sposob osiagnac zalozone cele
      cele klienta mozna osiagnac na wiele sposobow
      duze systemy wykorystywanie sa przez wielu uzytkownikow, ktore cele moga byc sprzeczne
      zleceniodawcy i uzytkownicy to inne osoby - nie zawsze sa oni w stanie wlascie przewidziec potrzeby rzeczywistych uzytkownikow


      UWZGLEDNIAC PRZYPADKI WYJATKOWE


punkt widzenia - definicja
      bezposrednie
      posrednie
      zwiazane z dziedzina


punkt widzenia sa zrodlem rozmaitych oczekiwanm wizji i konkretny wymagan w stosunku do systemu


jezyk naturalny
      latwy dla klienta, latwy do sporzadzeni


atrybut asocjacyjny


grupa docelowa
      jakiego poziomy zaawansowania biznesowego nalezy oczekiwac od obiorcow
      jaki poziom szczegolowsc jest potrzebny odbiorcom
      ile czasu moze grupa docelowa poswieci na nalize i interpretacje modulu
      jezyk definiowania modelu
      	    ogolnie wystepujaca terminologia (mniejsza precyzja ale lepszy odbior)
	    terminologia specjalistyczna(duza precyzja, zawezony krag odbiorcow)


faza ustalenia wymagan
faza specyfikacji wymagan
faza alestacji (walidacji) wymagan


*klient nie rozumie specyfikacji funkconowania programow*
wykonawca nie zna specyfiki dziedziny zastosowan


wymagania funkconalne
	  co ma realizowac jakie funkcjie jakie uslugi ja zachowywac sie w sytuacjach


wymagania niefunkconalnie
	  zgodnosc z prawem, niezawodnosc, ograniczen czasowych, wykorzysanie zasobow, bezpieczenstwa, wspolpraca z okreslonymi narzadziami, tajnosc, prywatnosc