Allegro Marketplace Clone 🛒

Prosta, nowoczesna i w pełni responsywna aplikacja webowa typu Marketplace (wzorowana na interfejsie Allegro), stworzona w całości w jednym pliku HTML przy użyciu Tailwind CSS oraz JavaScript. Projekt nie wymaga skomplikowanej konfiguracji środowiska backendowego ani instalacji paczek npm – działa bezpośrednio w przeglądarce!

🌟 Główne Funkcje

🛍️ Katalog Produktów i Wyszukiwarka: Dynamiczny podział na kategorie (Elektronika, Moda, Dom i Ogród, Sport, Supermarket) oraz płynna wyszukiwarka w czasie rzeczywistym.

🔐 Bezpieczny System Logowania: Dostęp do panelu zarządzania ofertami po wpisaniu hasła 7777 (z funkcją ukrywania/pokazywania znaku hasła).

✍️ Zarządzanie Ofertami (CRUD):

Dodawanie: Użytkownik po zalogowaniu może wystawić nowy przedmiot z własnym zdjęciem, ceną i opisem.

Edycja: Możliwość modyfikacji istniejących ofert.

Usuwanie: Trwałe usuwanie ofert z poziomu karty produktu lub listy.

Zabezpieczenie: Niezalogowani użytkownicy nie mają dostępu do przycisków dodawania, edycji ani usuwania.

🔗 Unikalne Podstrony Produktowe (24-znaki): Każdy produkt (zarówno domyślny, jak i nowo dodany) otrzymuje unikalny link z losowym 24-znakowym ciągiem alfanumerycznym w hashu (np. #p/AbC123XyZ...), symulujący dedykowaną podstronę.

🛒 Interaktywny Koszyk: Dodawanie produktów, zmiana ilości sztuk, podgląd kwoty łącznej oraz symulacja składania zamówienia.

📱 Responsywny Design: Stylowy interfejs zoptymalizowany pod urządzenia mobilne oraz komputery stacjonarne.

🚀 Jak uruchomić projekt?

Projekt jest zawarty w jednym pliku (index.html), dzięki czemu uruchomienie go jest niezwykle proste:

Pobierz lub sklonuj repozytorium na swój komputer:

git clone https://github.com/twoja-nazwa/allegro-marketplace.git


Otwórz plik index.html w dowolnej współczesnej przeglądarce internetowej (Google Chrome, Firefox, Edge, Safari).

🔑 Instrukcja Logowania dla Sprzedawcy

Kliknij przycisk "Zaloguj się" w prawym górnym rogu strony.

Wpisz hasło administratora/sprzedawcy: 7777.

Po pomyślnym zalogowaniu odblokują się opcje "Wystaw przedmiot" oraz przyciski Edycji i Usuwania przy ofertach.

Aby się wylogować, kliknij ikonę wylogowania w prawym górnym rogu.

🛠️ Technologie

HTML5 – struktura dokumentu.

Tailwind CSS (CDN) – nowoczesny i responsywny design.

Vanilla JavaScript (ES6+) – logika aplikacji, routingu hashowego, generator 24-znakowych unikalnych ID oraz stan koszyka.

FontAwesome & Inter Font – ikony oraz czytelna typografia.

📄 Licencja

Ten projekt jest udostępniony na licencji MIT. Możesz go swobodnie modyfikować i wykorzystywać do własnych celów.
