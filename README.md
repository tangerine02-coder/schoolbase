# Panel kontaktów ze szkołami

Panel do prowadzenia kontaktów fundacji ze szkołami. Działa w przeglądarce, bez instalacji i bez zakładania kont. Pozwala zapisywać:

- z kim i kiedy był kontakt,
- jakie oferty zostały wysłane i do kogo,
- jakie szkolenia są umówione: dla uczniów, nauczycieli lub dyrekcji i kadry.

W panelu jest **23 722 szkół z całej Polski**: podstawowe, licea, technika, branżowe i artystyczne. Ma ich dane kontaktowe:

- dyrektor/ka,
- e-mail ze sprawdzeniem poprawności,
- telefon,
- strona www,
- adres.

Dane pochodzą z Rejestru Szkół i Placówek Oświatowych (RSPO) i są aktualne na 29.10.2026. E-maile zostały sprawdzone 22.11.2026.

## Pobranie

1. Pobierz paczkę: **[schoolbase-main.zip](https://github.com/tangerine02-coder/schoolbase/archive/refs/heads/main.zip)**. Możesz też na stronie repozytorium kliknąć zielony przycisk **Code → Download ZIP**.
2. **Rozpakuj** ZIP, np. do folderu *Dokumenty*. Nie otwieraj pliku bezpośrednio ze środka ZIP-a.
3. Otwórz **`Panel_kontaktow_szkol.html`** w przeglądarce **Chrome** albo **Edge**. Na starcie panel pokazuje szkoły z Torunia.

## Zapisywanie danych (ważne)

Wszystko, co zaznaczysz w panelu, zapisuje się automatycznie w tej przeglądarce na tym komputerze. Dane **nie trafiają do internetu ani na GitHuba**.

Żeby ich nie stracić, na przykład po wyczyszczeniu historii przeglądarki:

1. Przy pierwszym uruchomieniu kliknij na żółtym pasku **„Włącz zapis do pliku”**.
2. Zapisz plik **`Dane_panelu_szkol.json`**, np. w *Dokumentach*. Od tej chwili każda zmiana zapisuje się w nim automatycznie. U góry pojawi się napis „Zapisano na dysku”.
3. Po ponownym otwarciu panelu przeglądarka może poprosić o zgodę. Wtedy kliknij **„Wznów zapis do pliku”**.

W przeglądarkach bez tej funkcji, np. Firefox i Safari, panel przypomina o pobraniu kopii zapasowej.

**Przeniesienie danych na inny komputer albo odtworzenie po wyczyszczeniu przeglądarki:**
1. Wybierz **Eksport i import → Import** i wskaż plik `Dane_panelu_szkol.json` lub kopię zapasową.
2. Potem ponownie włącz zapis do pliku.

## Co jest w panelu

- **Szkoły.** Filtry, w które można wpisywać wiele wartości naraz, np. Toruń + Bydgoszcz albo licea + technika. Po kliknięciu szkoły otwiera się jej karta z pełnymi danymi. Można w niej ustawić status kontaktu, osobę kontaktową, następny krok i notatki, prowadzić historię kontaktów, zapisywać wysłane oferty i szkolenia.
- **Pulpit.** Liczba szkół z kontaktem, lejek statusów, wyniki ofert.
- **Do zrobienia.** Zaległe kroki, oferty bez odpowiedzi, nadchodzące szkolenia.
- **Oferty.** Lista ofert z grupą uczestników: uczniowie, nauczyciele / rada pedagogiczna, dyrekcja i kadra.
- **Eksport i import.** Excel (szkoły z wpisami albo aktualna lista), kopia zapasowa, import.

## Aktualizacja panelu

Pobierz nowy ZIP i otwórz nowy plik `Panel_kontaktow_szkol.html` w tej samej przeglądarce. Wpisy zostają, bo są zapisane w przeglądarce i w pliku danych.
