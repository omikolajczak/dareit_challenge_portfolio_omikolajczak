# dareit_challenge_portfolio_omikolajczak


## Task 1: Testy eksploracyjne


### Subtask 1 - Wyciągamy karteczki…

👩🏼‍🏫 Podczas [egzaminu](https://docs.google.com/forms/d/15-pQoZ1t2wG5sz2KdrX1RlhCrJkGDw-ZF3XSoGhNvcQ) stworzonego przez DareIT udało mi się uzyskać 8 punktów na 10 możliwych.

✏️ Edit: Jest to moje drugie podejście do Challeng'u i za drugim razem uzyskałam 10 punktów! 😎

---

### Subtask 3 - Formatowanie README file w GitHub

📝 **Dlaczego zdecydował_ś się na udział w challenge portfolio?**

Cześć 🤍 

Mam na imię Oliwia i mam już za sobą ponad rok doświadczenia w testowaniu. Pomimo przebranżowienia się na UX/UI Designera, testowanie nadal jest mi bliskie. Ten challenge chcę wykorzystać do uporzadkowania sobie wiedzy, poszerzenia kontaktów oraz stworzenia portfolio, który potwierdzi moje kompetencje. 

Zdecydowałam się na kurs DareIT, ponieważ od dłuższego czasu mogę nazwać się członkinią społeczność DareIT i obserować ile dobra dziewczyny tworzą wokół siebie 🔥 Brałam udział już w kilku wydarzeniach dziewczyn i zawsze jestem zachwycona jakością! Dlatego nie wachałam się długo, jak tylko wyświetliła mi się informacja o challengu portfolio "Zostań Testerem Manualnym" 😁 

***Oliwia***

---

### Subtask 4 - Testy eksploracyjne – poznaj aplikację

📝 **Na czym polega [aplikacja Scouts](https://scouts-test.futbolkolektyw.pl/pl)? Do czego służy?**

Aplikacja **Scouts** umożliwa:
  * przeglądanie wskaźników, umiejętności i pozycji graczy
  * zarządzanie graczami oraz meczami 
  * tworzenie i zarządzanie raportami.


📝 **Jakie funkcjonalności znajdują się w aplikacji? Do czego służą? Czy są intuicyjne, czy może byś coś zmienił_a?**

Funkcjonalności aplikacji:
  * logowanie oraz wylogowywanie do/z aplikacji 
  * zmiana języka aplikacji (polski, angielski)
  * przegląd ilości zawodników, meczy, raportów oraz akcji
  * przegląd ostatnich aktywności
  * dodawanie zawodników
  * edycja danych zawodników
  * filtrowanie oraz sortowanie listy zawodników
  * zarządzanie listą zawodników poprzez zaznaczanie (dodawanie/wyświetlanie) oraz odznaczanie (usuwanie/chowanie) poszczególnych kolumn
  * drukowanie listy zawodników
  * tworzenie raportów CVS listy zawodników
  * wyszukiwanie zawodników
  * dodawanie meczy przypisanych do konkretnego zawodnika
  * edycja meczy
  * tworzenie zdarzeń/akcji do danego meczu (dokładny czas, czy udany, typ, dane, komentarz)
  * tworzenie raportów zawodników do danego meczu
  * edycja raportów

Niestety nie wszystkie z wymienionych przeze mnie funkcjonalności są intuicyjne. Edycja zawodników byłaby bardziej intuicyjny, gdyby odbywała się po kliknięciu button'a "Edytuj" w postaci icon'y ołówka jak w przypadku edycji meczy (obecnie jest to kliknięcie w gracza). Kliknięcie w danego zawodnika mogłoby wywołać podgląd tego zawodnika. 

Przegląd zawodników, meczy oraz raportów powinnien być ujednolicony, oznacza to, że w panelu powinna znajdować się zakładka z meczami oraz raportami. Możliwość zarządzaniem meczami oraz raportami powinna być dostępna bez konieczności wyboru zawodnika (dane mecze oraz raporty są przypisane do konkretnego zawodnika, obecny jednak sposób zarządzania meczami oraz raportami jest ukryty; do danych meczy oraz raportów warto dodać dane o przypisanym użytkowniku; umożliwiłoby to wyszukiwanie wszystkich meczy oraz raportów, które byłby dostępne jak lista graczy, poprzez dane zawodnika).

**------------------------------------------------**

_**Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**_

Interfejs aplikacji jest prosty. Nie zawiera nie potrzebnych elementów graficznych, które mogłyby przeszkodzić w analizowaniu danych oraz zarządzaniu zaowdnikami czy raportami. Wizualnie spełenia swoją podstawową funkcję i uważam, że jest to wystarczające do takiego typu aplikacji. Jednak niektóre elementy są nieklikalne, a sprawiają wrażenie elementów klikalnych. Piszę tutaj o 4 informacjach na stronie głównej u góry strony. 
![dareit_tester](https://user-images.githubusercontent.com/56199380/213307051-f6c06f48-5f73-42dd-add6-e85c957373ef.png)

Jak już wczesniej napisałam dostęp do zarządzania meczami oraz raportami powinnien być dostępny od razu w bocznym menu, a nie po przejściu do zakładki Zawodnicy. Takie bugi niestety sprawiają, że pomimo prostego i czytelnego interfejsu staje się on dość skomplikowany.

**------------------------------------------------**

**Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).**

Już powyżej wymieniłam kilka elementów nieintuicyjnych. Poniżej cała lista:
 * Edycja zawodników byłaby bardziej intuicyjny, gdyby odbywała się po kliknięciu button'a "Edytuj" w postaci icon'y ołówka jak w przypadku edycji meczy (obecnie jest to kliknięcie w gracza). Kliknięcie w danego zawodnika mogłoby wywołać podgląd tego zawodnika. ![dareit_tester1](https://user-images.githubusercontent.com/56199380/213309130-d7ac3708-ca4a-48cd-a721-91275b57cf15.png)
 * Przegląd zawodników, meczy oraz raportów powinnien być ujednolicony, oznacza to, że w panelu powinna znajdować się zakładka z meczami oraz raportami. Możliwość zarządzaniem meczami oraz raportami powinna być dostępna bez konieczności wyboru zawodnika. ![dareit_tester2](https://user-images.githubusercontent.com/56199380/213309276-0f83d49b-98c8-49e6-a73b-cb09295f168d.png)
 * Do danych meczy oraz raportów warto dodać dane o przypisanym użytkowniku. Umożliwiłoby to wyszukiwanie wszystkich meczy oraz raportów, które byłby dostępne jak lista graczy, poprzez dane zawodnika.
 * Niektóre elementy są nieklikalne, a sprawiają wrażenie elementów klikalnych. Piszę tutaj o 4 informacjach na stronie głównej u góry strony. ![dareit_tester](https://user-images.githubusercontent.com/56199380/213307051-f6c06f48-5f73-42dd-add6-e85c957373ef.png)
 * Brak zasygnalizowania możliwośći sortowania w zakładce Zawodnicy. ![dareit_tester3](https://user-images.githubusercontent.com/56199380/213309716-85e19ea5-bd96-4f60-98a8-95854bc48938.png)


**------------------------------------------------**

**Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?**

Niestety (albo stety, bo jak uczyć się na aplikacji, która jest bezbłędna 🧐 a przecież takich nie ma) w aplikacji można znaleźć kilka błędów:

 * Możliwość dodania ujemnych oraz nieprawidłowych wartości (jak litery, czy wartości nielożliwe do osiągnięcia dla człowieka, np. 1000000 cm) dla wagi oraz wzrostu karcie zawodnika. ![dareit_tester4](https://user-images.githubusercontent.com/56199380/213310899-dc9f2479-e719-48ea-be74-2c86231a2d15.png)
 * Możliwość dodania daty z wyprzedzeniem w karcie zawodnika. ![dareit_tester6](https://user-images.githubusercontent.com/56199380/213312923-9d44f37b-4fc1-43e8-b7dc-19ab97c77fd0.png)
 * Po kliknięciu w "Dodaj raport" aplikacja przekierowuje mnie do zakładki Mecze. Niestety w takim wypadku dodawanie reportów jest niemożliwe.
 * Jest możliwość tłumaczenia strony na polski lub angielski. Niestety na polski nie są przetłumaczone wszystkie teskty, jak "search" w wyszukiwarce lub na stronie głównej "Dev team contact". 
 * Literówki w słowie "Aktywność" oraz "zaktualizowany". 

   ![dareit_tester5](https://user-images.githubusercontent.com/56199380/213312154-b425d050-37d2-469d-b335-54f681da8a5f.png)


## Task 3


### Subtask 1
Link: https://docs.google.com/spreadsheets/d/1qHqaF7e2Y9qbkceXO6gIpf-RIlUGQxaM9w0-x0L9mjI/edit?usp=sharing


### Subtask 2
Link: https://docs.google.com/spreadsheets/d/1o7X_KxkY8e-0W8gAdOaPO_RpuuSmBZepUlh_sBF2XBA/edit?usp=sharing


### Subtask 3
Link: https://docs.google.com/spreadsheets/d/1oicgMEF2GVj3EaSkblde6prYIbHwb0Os3lnzq6vpPZM/edit?usp=sharing

---

## Task 4: Testowanie aplikacji mobilnej [Focusly](https://focusly.co/)


### Subtask 1 - Utworzenie formatki do zgłaszania błędów systemu

Link: https://docs.google.com/spreadsheets/d/1FntW_EOexcr0Gf-0sP7NCZb7lBPrxjSey-bGCmA46TE/edit?usp=sharing

---

### Subtask 2 - Testowanie eksploracyjne i raportowanie błędów

Link: https://docs.google.com/spreadsheets/d/13SQTfePuOpjRnRd07Ko9EYmtvUPfGgLDwI1vPJw4jEI/edit?usp=sharing

---

### Subtask 3 - Do czego służy ta aplikacja?

_**Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?**_

Aplikacja służy do prowadzenia medytacji, afirmacji oraz relaksacji. Jest możliwość kontrolowania oddechu aby zrelaksować się przed snem, wyciszyć, czy skoncentrować. Możliwe jest również zaczęcie kursu z dziedzin takich jak: uważność, medytacja czy kursy dotyczące oddechu. Applikacja zawiera artykuły oraz porady jak na przykład radzić sobie ze stresem, jak poprawić i przyjrzeć się swojemu oddechowi. Aplikacja ma na celu pomóc ludziom zwiększyć swoją świadomość oraz pomóc radzić sobie ze stresem.


_**Kto ma być użytkownikiem końcowym aplikacji?**_

Użytkownikiem końcowym jest osoba, która chce pracować nad oddechem, jest zainteresowana medytacją, odczuwa potrzebę polepszenia swojego samopoczucia oraz chcę doszkalać się oraz poszerzać swoją wiedzę w dziedzinie dbania o siebie i swoje zdrowie psychiczne. Jest to aplikacja dla osób na każdym poziomie zaawansowania.


_**Czy według Ciebie aplikacja jest user friendly?**_

Aplikacja jest przyjazna użytkownikowi. W aplikacji wystepują poradniki, które pomagają użytkownikowi poznać aplikację oraz tłumaczy jak ją najlepiej wykorzystać do własnych celów. Użytkownik nie powinnien odczywać żadnych trudności przy kolejnych wejściach do aplikacji, dzięki dobrze opisanym button'om, przejrzystemu interfejsowi oraz spójnemu design.


_**Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?**_

- Dodałabym możliwość logowania się za pomocą konto Google.
- Dodałabym możliowść wyszukiwania soudtrack'ów.
- Dodałabym jasny podział na artykuły, wyzwania oraz programy w sekcji "Odkryj".
- Zamieniłabym kartę "Twórcy" na "Profil", aby było to jeszcze bardziej dostepne dla użytkownika.
- Dodałabym opcję rejestru pracy nad oddechem (w które dni zostały one wykonane).


_**Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?**_

- Przy testowaniu aplikacji natywnych jest możliwość przetestowania aplikacji na większej ilości urządzeń. Można testować nie tylko na telefonie, ale również na tablecie z podziałem na systemu.
- W przypadku testowania aplikacji internetowej ważny jest adres strony. Przy tesotwaniu aplikacji natywnej ważny jest pobranie aplikacji oraz numer Build.
- Po aplikacji internetowej poruszamy się za pomocą myszki czy trackpada. Po aplikacji natywnej poruszamy się palcem.

---

## Task 5: SQL part 1


### Subtask 1 - Krótki kurs podstaw SQL


📝 **Przedstawiam poniżej listę operatorów/zapytań, które poznałam w trakcie kursów https://www.kursysql.pl/szkolenie-sql-w-120-minut/ oraz https://www.w3schools.com/sql/:**

- **```SELECT```** zwraca listę pól zawierających wskazane dane
- **```FROM```** zwraca listę tabel zawierających pola wymienione w klauzuli SELECT
- **```ORDER BY```** jest wykorzystywane do sortowania wyników
- **```ASC```** używane do sortowania rosnącego
- **```DESC```** używane do sortowania malejacego
- **```WHERE```** określa kryteria pól, które musi spełnić rekord, aby został uwzględniony w wynikach
- **```AND```** zwraca wynik prawda, gdy wyrażenia po obu stronach operatora są prawdziwe - jeżeli choć jedno z nich jest nieprawdziwe, wtedy całe wyrażenie zwraca jako wynik wartość fałsz
- **```OR```** zwraca wynik prawda, gdy jedno z wyrażen po prawej lub po lewej stronie operatora jest prawdziwe - gdy oba wyrażenia są prawdziwe, wynik też przyjmuje wartość prawda
- **```NOT```** używane do zaprzeczenia wartości wyrażenia
- **```IN```** określa, czy wartość testowana jest identyczna z przynajmniej jedną z wartości z listy
- **```LIKE```** służy do sprawdzenia, czy wartość należy do podanego zakresu z uwzględnieniem wartości granicznych
- **```BETWEEN```** służy do sprawdzenia, czy wartość należy do podanego zakresu z uwzględnieniem wartości granicznych
- **```IS NULL```** wskazuje, że dana nie istnieje w bazie danych
- **```IS NOT NULL```** nie pozwala na wprowadzenie wartości NULL w kolumnie
- **```GROUP BY```** łączy rekordy o identycznych wartościach pól wymienionych na liście w jeden rekord
- **```JOIN```** wykorzystywane do łączenia danych znajdujących się w różnych tabelach.

---

### Subtask 3 - Kilka zadań na rozgrzewkę z SQL

📝 **1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM actors

ORDER BY surname
```

🖼️ **Screenshot prt:**

![dareit_sql_1](https://user-images.githubusercontent.com/56199380/220362822-4c22fa04-01e9-4f58-b451-8232308f9365.png)


📝 **2. Wyświetl film, który powstał w 2019 roku.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM movies

WHERE year_of_production = 2019
```

🖼️ **Screenshot prt:**

![dareit_sql_2](https://user-images.githubusercontent.com/56199380/220362856-3eb10544-a18b-46ed-878f-67b240614bef.png)


📝 **3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM movies

WHERE year_of_production BETWEEN 1900 AND 1999
```

🖼️ **Screenshot prt:**

![dareit_sql_3](https://user-images.githubusercontent.com/56199380/220362888-4702c08e-74d3-4ee8-8790-d8f619adaa02.png)


📝 **4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.**

💡 **Użyte zapytania:**

```sql
SELECT title, price 

FROM movies

WHERE price < 7
```

🖼️ **Screenshot prt:**

![dareit_sql_4](https://user-images.githubusercontent.com/56199380/220362941-981ba081-e31d-47d9-9111-1a3661eb0ea6.png)


📝 **5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM actors

WHERE actor_id >= 4 AND actor_id <=7
```

🖼️ **Screenshot prt:**

![dareit_sql_5](https://user-images.githubusercontent.com/56199380/220363298-d401a243-91ca-42a3-b9ca-039484d9cc75.png)


📝 **6. Wyświetl klientów o id 2, 4, 6. Wykorzystaj do tego warunek logiczny.**_

💡 **Użyte zapytania:**

```sql
SELECT * FROM customers

WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6
```

🖼️ **Screenshot prt:**

![dareit_sql_6](https://user-images.githubusercontent.com/56199380/220365415-42123643-4710-4085-89d5-d379105731b5.png)


📝 **7. Wyświetl klientów o id 1, 3, 5. Wykorzystaj do tego operator IN.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM customers

WHERE customer_id IN (1,3,5)
```

🖼️ **Screenshot prt:**

![dareit_sql_7](https://user-images.githubusercontent.com/56199380/220366071-f4054e58-1277-4f09-bb3c-df72a63e1153.png)


📝 **8. Wyświetl dane wszystkich osób z tabeli actors, których imię zaczyna się od ciągu “An”.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM actors

WHERE name LIKE 'An%'
```

🖼️ **Screenshot prt:**

![dareit_sql_8](https://user-images.githubusercontent.com/56199380/220366863-ee16b6c0-745f-4a96-9ae4-fae4dd260d8e.png)


📝 **9. Wyświetl dane klienta, który nie ma podanego adresu email.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM customers

WHERE email IS NULL
```

🖼️ **Screenshot prt:**

![dareit_sql_9](https://user-images.githubusercontent.com/56199380/220366897-e0416a3f-f9f6-457f-ba0c-e070ea15fe10.png)


📝 **10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich id mieści się pomiędzy 2 i 8.**

💡 **Użyte zapytania:**

```sql
SELECT * FROM movies

WHERE price >9 AND movie_id BETWEEN 2 AND 8
```

🖼️ **Screenshot prt:**

![dareit_sql_10](https://user-images.githubusercontent.com/56199380/220366921-aa65f567-97b1-44d8-986a-33eaa818f0bf.png)


---

## Task 6: SQL part 2


### Subtask 1 - Krótki kurs podstaw SQL


📝 **11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd.**

💡 **Użyte zapytania:**

```sql
UPDATE customers

SET surname = "Miler"

WHERE customer_id = 3
```

🖼️ **Screenshot prt:**

![dareit_sql_11](https://user-images.githubusercontent.com/56199380/220301238-aff41520-4f2c-4dff-b6f8-8550b4c609d2.png)


📝 **12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji JOIN sprawdź, jak ma na imię klient i jakiego ma maila.**

💡 **Użyte zapytania:**

```sql
SELECT customers.name, customers.email

FROM customers

JOIN sale

ON customers.customer_id = sale.customer_id

WHERE sale.movie_id = 4
```

🖼️ **Screenshot prt:**

![dareit_sql_12](https://user-images.githubusercontent.com/56199380/220301091-eb3cceab-0ce3-4f62-9899-7e5ed8146d21.png)


📝 **13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com.**

💡 **Użyte zapytania:**

```sql
UPDATE customers

SET email = "pati@mail.com"

WHERE customer_id = 4
```

🖼️ **Screenshot prt:**

![dareit_sql_13](https://user-images.githubusercontent.com/56199380/220300937-7cc18360-9422-450f-af08-4de186014120.png)


📝 **14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję INNER JOIN, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**

💡 **Użyte zapytania:**

```sql
SELECT customers.name, customers.surname, movies.title

FROM customers

INNER JOIN sale

ON customers.customer_id = sale.customer_id

INNER JOIN movies

ON sale.movie_id = movies.movie_id
```

🖼️ **Screenshot prt:**

![dareit_sql_14](https://user-images.githubusercontent.com/56199380/220300771-f5653e8a-27a1-42f9-b86a-a8a746f91943.png)


📝 **15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer. Następnie wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag.**

💡 **Użyte zapytania:**

```sql
ALTER TABLE customers

ADD pseudonym VARCHAR (3);

UPDATE customers 

SET pseudonym = (SELECT CONCAT(LEFT (name,2), RIGHT(surname,1)))
```

🖼️ **Screenshot prt:**

![dareit_sql_15](https://user-images.githubusercontent.com/56199380/220300615-c5095c0b-052b-4f66-a8df-0d8d630da262.png)


📝 **16. Wyświetl tytuły filmów, które zostały zakupione. Wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**

💡 **Użyte zapytania:**

```sql
SELECT DISTINCT movies.title

FROM movies

JOIN sale

ON movies.movie_id=sale.movie_id;
```

🖼️ **Screenshot prt:**

![dareit_sql_16](https://user-images.githubusercontent.com/56199380/220302078-ad429bf6-7d64-4c29-922e-3232d148e1b8.png)


📝 **17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION).**

💡 **Użyte zapytania:**

```sql
SELECT name FROM actors

UNION

SELECT name FROM customers

ORDER BY name
```

🖼️ **Screenshot prt:**

![dareit_sql_17](https://user-images.githubusercontent.com/56199380/220295237-49a0ad11-54c2-4d3b-a325-f0ff4dfae52c.png)


📝 **18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $.**

💡 **Użyte zapytania:**

```sql
UPDATE movies

SET price = price + 2.5

WHERE year_of_production > 2000
```

🖼️ **Screenshot prt:**

![dareit_sql_18](https://user-images.githubusercontent.com/56199380/220295021-8c0ee4bd-17da-40dd-95c5-f4d3fa7066ac.png)


📝 **19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.**

💡 **Użyte zapytania:**

```sql
SELECT actors.name, actors.surname, movies.title

FROM actors

JOIN cast

ON actors.actor_id=cast.actor_id

JOIN movies

ON movies.movie_id=cast.movie_id

WHERE actors.actor_id = 4;
```

🖼️ **Screenshot prt:**

![dareit_sql_19](https://user-images.githubusercontent.com/56199380/220294004-e968a631-a98a-4c1c-9d67-a623bffd7ee4.png)


📝 **20. Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa.**

💡 **Użyte zapytania:**

```sql
INSERT INTO customers (customer_id, name, surname, email, pseudonym)

VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')
```

🖼️ **Screenshot prt:**

![dareit_sql_20](https://user-images.githubusercontent.com/56199380/220293903-16ef384f-bbee-4000-8781-797682e377e7.png)

---

### Subtask 2 - Test

👩🏼‍🏫 Uzyskałam 14/15 punktów z zestawu pytań ECRU na stronie http://getistqb.com/. 

![dareit_wyniktestu](https://user-images.githubusercontent.com/56199380/220329809-8f60b0c9-901b-470b-916b-673db3e8c59f.png)

---

### Subtask 3 - Tworzymy portfolio



---
