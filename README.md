# documentation
Documentation
Wprowadzenie

Wspólnie z firmą Smartbear realizujemy projekt, którego celem jest stworzenie aplikacji do integracji uwierzytelniania SSO. Pierwszym krokiem jest podział obowiązków oraz ustalenie harmonogramu prac. Następnie decydujemy o środowiskach i technologiach, które wykorzystamy w projekcie, a członkowie zespołu przygotowują się do jego realizacji, zapoznając się ze środowiskami i zdobywając niezbędną wiedzę. W kolejnym etapie tworzymy odpowiednie środowiska, umożliwiające opracowanie projektu oraz śledzenie postępów prac, w tym zgodność z harmonogramem. Realizacja projektu obejmuje opracowanie Frontendu oraz Backendu, przy użyciu odpowiednich podzespołów, które pozwalają na osiągnięcie założonych celów. Na cotygodniowych spotkaniach omawiamy postępy prac oraz konsultujemy się z firmą w kwestii rozwiązań technicznych. Kolejnym etapem jest testowanie pierwszej wersji aplikacji, lokalizowanie błędów oraz wprowadzenie koniecznych poprawek. Finalnym krokiem jest złożenie gotowego projektu, w tym finalnej wersji aplikacji oraz dokumentacji projektowej.

Rozdział 1. Wstęp teoretyczny 

Nasz zespół studentów pracuje nad stworzeniem aplikacji dla SSO (Single Sign-On) przy użyciu platformy AWS Amplify.

SSO to mechanizm uwierzytelniania, który umożliwia użytkownikom korzystanie z różnych usług i aplikacji za pomocą jednego zestawu poświadczeń. Oznacza to, że użytkownik może zalogować się raz, a następnie uzyskać dostęp do wielu usług bez potrzeby ponownego logowania.

AWS (Amazon Web Services) to platforma chmurowa, która umożliwia dostęp do różnych zasobów, takich jak serwery, bazy danych i narzędzia deweloperskie. Amplify to usługa AWS, która ułatwia tworzenie aplikacji mobilnych i webowych.

W ramach naszego projektu chcemy wykorzystać różne zasoby AWS, które będą przydatne dla naszej aplikacji SSO. Jednym z takich zasobów jest AWS Cognito, który pozwala na łatwe zarządzanie tożsamościami użytkowników, uwierzytelnianie i autoryzację.

Innym zasobem, który będzie przydatny dla naszej aplikacji, jest AWS Lambda, która umożliwia uruchamianie kodu bez konieczności zarządzania serwerami. Dzięki temu możemy skoncentrować się na tworzeniu funkcjonalności aplikacji, a nie na infrastrukturze.

Oprócz tego, chcemy wykorzystać API Gateway, usługę, która umożliwia tworzenie, publikowanie i zarządzanie API. To pozwoli nam na udostępnianie naszej aplikacji przez różne platformy i urządzenia.

Dzięki wykorzystaniu zasobów AWS i platformy Amplify, nasza aplikacja SSO będzie łatwa do skalowania, bezpieczna i łatwa do zarządzania. 
 Rozdział 2. Założenia projektowe

Nasz projekt ma na celu stworzenie aplikacji SSO opartej na platformie AWS Amplify. Główne cele, które chcemy osiągnąć to:

•	umożliwienie użytkownikom logowania się do różnych aplikacji za pomocą jednego zestawu poświadczeń,

•	zapewnienie bezpiecznego uwierzytelniania i autoryzacji użytkowników,

•	łatwość w zarządzaniu tożsamościami użytkowników i aplikacji,

•	możliwość łatwego dodawania nowych funkcji do systemu SSO.

W ramach projektu planujemy stworzyć prototyp naszej aplikacji, który będziemy mogli przetestować i udoskonalić na podstawie feedbacku od użytkowników (Pracownicy SmartBear, członkowie grupy studentów, chętni do testowania programowania). Głównym założeniem jest  jest stworzenie aplikacji, która spełni wymagania użytkowników i zapewni im łatwość i wygodę w korzystaniu.

Rozdział 3. Projekt „Amplify Application”
Planowanie projektu

Zespół podejmując się realizacji projektu stworzenia szablonu infrastruktury AWS oraz mikroaplikacji webowych, które umożliwią skonfigurowanie AWS Cognito i przetestowanie działania stworzonego połączenia bez udziału inżyniera DevOps, powinien przejść przez kilka etapów, takich jak analiza wymagań projektowych, planowanie projektu, implementacja projektu, testowanie i wdrożenie projektu, dokumentacja projektu oraz prezentacja projektu. 
Etap 1: Analiza wymagań projektu
W ramach tego etapu zespół skupi się na zrozumieniu wymagań projektowych oraz wymagań stawianych przez firmę SmartBear. Wszyscy członkowie zespołu będą mieli dostęp do materiałów projektowych oraz do specyfikacji wymagań, aby lepiej zrozumieć zakres projektu. W wyniku tego etapu, zespół powinien być w stanie stworzyć plan projektu oraz określić zasoby i czas potrzebny do realizacji projektu.
Etap 2: Planowanie projektu
W ramach tego etapu zespół powinien stworzyć plan projektu, który uwzględnia kroki potrzebne do zrealizowania projektu, a także określenie zasobów, które będą potrzebne do realizacji projektu. W planie projektu powinny znaleźć się etapy, które będą wykonywane przez cały zespół, a także zadania, które będą przypisane poszczególnym członkom zespołu. Plan powinien także określać terminy, w których poszczególne etapy projektu mają zostać ukończone, aby projekt został zrealizowany na czas.
Etap 3: Implementacja projektu
W ramach tego etapu zespół rozpocznie pracę nad implementacją projektu. Każdy z członków zespołu będzie odpowiedzialny za wykonanie swojego zadania w ramach projektu zgodnie z planem projektu. Zespół będzie wykorzystywał różne narzędzia programistyczne, takie jak AWS Lambda, DynamoDB, CDK i Amplify.
Etap 4: Testowanie i wdrożenie projektu
W ramach tego etapu zespół przeprowadzi testy aplikacji, aby upewnić się, że działa ona zgodnie z wymaganiami projektowymi oraz oczekiwaniami firmy SmartBear. Po przeprowadzeniu testów aplikacja zostanie wdrożona, a zespół będzie monitorował jej działanie, aby zapewnić, że wszystko działa prawidłowo.
Etap 5: Prezentacja projektu
Ostatnim etapem projektu będzie prezentacja przedstawiająca realizację projektu oraz wyniki testów. Członkowie zespołu będą mieli okazję zaprezentować swoje rozwiązanie przed firmą SmartBear, aby zaprezentować jak wiele udało się osiągnąć w ramach projektu. Prezentacja będzie okazją do uzyskania informacji zwrotnej od pracowników firmy SmartBear oraz do ewentualnych poprawek i ulepszeń projektu

Rozpoczęcie prac technicznych
Ten etap można nazwać pierwszą techniczną częścią naszego projektu. W ramach etapu "Rozpoczęcie prac technicznych" nasz zespół zacznie prace nad projektem polegającym na zapoznaniu się z usługami AWS, takimi jak Lambda, IAM, Amplify i API Gateway. Naszym pierwszym zadaniem będzie utworzenie konta AWS i skonfigurowanie dostępu do wymienionych usług, aby móc wdrożyć projekt na platformie AWS.

Kolejnym krokiem będzie zapoznanie się z dokumentacją każdej z usług, aby zdobyć wiedzę na temat ich działania i zrozumieć, jak najlepiej wykorzystać je w kontekście projektu. Po zrozumieniu, jak działają te usługi, będziemy mogli zacząć prace nad naszym projektem.

Aby przejść do dalszych kroków, musimy utworzymy repozytorium GitHub, na którym będziemy przechowywać nasz kod źródłowy projektu. Zadbamy o odpowiednie skonfigurowanie repozytorium, stosując najlepsze praktyki GitHub, takie jak korzystanie z gałęzi (branches), pull requestów (pull requests) i code review.

W kolejnym kroku połączymy kod źródłowy projektu z usługą Amplify. To pozwoli nam na łatwe wdrożenie aplikacji, a także automatyczne przeprowadzanie testów i wdrażanie zmian. Będziemy korzystać z AWS API Gateway, aby udostępnić naszą aplikację użytkownikom i umożliwić im korzystanie z niej poprzez interfejs webowy.

W etapie "Rozpoczęcie prac technicznych" zrealizujemy również wiele innych zadań, takich jak konfiguracja usługi IAM, ustawienie uprawnień dostępu do usług, utworzenie infrastruktury mikro serwisowej w oparciu o AWS Lambda i DynamoDB, a także wiele innych.

Tworzenia okna logowania w Amplify
Główną ideą naszego projektu jest koncepcja logowania przez SSO, ale niezależnie od tego, jak ironicznie to brzmi na początku, logowanie do naszej aplikacji powinniśmy wdrożyć sami.

W pierwszej kolejności utworzymy interfejs użytkownika (UI) dla naszej aplikacji w oparciu o framework Amplify. Będziemy korzystać z gotowych komponentów, takich jak moduł uwierzytelniania, który pozwoli nam na łatwe i szybkie dodanie funkcjonalności logowania do naszej aplikacji.

Następnie, skonfigurujemy usługę uwierzytelniania w Amplify. Zdefiniujemy sposób uwierzytelniania użytkowników (np. poprzez e-mail i hasło), a także ustalimy polityki bezpieczeństwa i dostępności, takie jak wymagane minimalne hasło czy wymagane potwierdzenie adresu e-mail.

W kolejnym kroku połączymy nasze okno logowania z usługą uwierzytelniania, aby użytkownicy mogli bezpiecznie logować się do aplikacji i korzystać z jej funkcjonalności. 
Można zobaczyć, że istnieje opcja utworzenia nowego użytkownika z GUI, ale ponieważ nie jest to potrzebne, okno zostało zmodyfikowano tak, aby użytkownika na tym etapie można było stworzyć wyłącznie ręcznie w Cognito User Pool



Tworzenie pierwszych funkcji Lambda

Rozpoczynamy etap tworzenia pierwszych funkcji Lambda dla naszego projektu. Zdecydowaliśmy, że będziemy korzystać z języka Python w wersji 3.8.

Pierwszą funkcją, którą będziemy tworzyć, jest CreateUserPool.py. Funkcja ta ma na celu stworzenie puli użytkowników w usłudze Cognito. Następnie, zaimplementujemy funkcję StartNewProject.py, będzie pełnić rolę głównej funkcji i będzie mógł aktywować inne Lambda.

Kolejną funkcją, którą stworzymy, jest CreateUser.py. Ta funkcja będzie służyć do dodawania nowych użytkowników do puli użytkowników w usłudze Cognito.

Po tym, stworzymy funkcję AddUserToGroup.py, która pozwoli na dodanie nowego użytkownika do grupy użytkowników w usłudze Cognito. Ostatnią funkcją, którą stworzymy, będzie CreateGroup.py, umożliwiająca utworzenie nowej grupy użytkowników w usłudze Cognito.

Wszystkie te funkcje będą wykorzystywane do zarządzania pulą użytkowników oraz grup użytkowników w usłudze Cognito. W tym celu wykorzystamy serwisy Lambda i IAM.




Na tym etapie nasze Lambdy są jeszcze oddzielone od głównego projektu i dołączą nieco później. Możemy podsumować, że teraz opracowujemy funkcjonalność tak, jak powinna wyglądać w przyszłości.


 
Rysunek 4 Obecna lista Lambd
W kolejnych krokach zwiększyliśmy i znormalizowaliśmy funkcjonalność wszystkich Lambd (rys. 4) oraz dołączyliśmy do nich ścieżki (rys.5).

 
Rysunek 5 Ścieżki użyte do Lambd
Główna Lambdą jest StartNewProject, która przyjmuje wszystkie parametry, przetwarza je oraz tworzy user poole. Na niej oparte są pozostałe Lambdy. Składa się ona z następujących elementów.

 
Rysunek 6 Kod funkcji handler, będący częścią Lambdy StartNewProject
Ten kod to funkcja obsługi zdarzeń (event handler) dla funkcji AWS Lambda w języku Python, która jest wywoływana przez wydarzenia, np. przez żądania HTTP.
Funkcja ta przyjmuje dwa parametry wejściowe, "event" i "context", gdzie "event" zawiera informacje o żądaniu HTTP, takie jak nagłówki, ciało żądania i parametry ścieżki, a "context" zawiera informacje o środowisku uruchomieniowym Lambda, takie jak identyfikator funkcji i informacje o wersji funkcji. 
Głównym celem tej funkcji jest tworzenie użytkownika w puli użytkowników AWS Cognito, dodanie go do grupy "techuser", utworzenie klienta OAuth2.0 dla tej puli użytkowników, utworzenie nazwy domeny dla puli użytkowników i dodanie informacji o nowym użytkowniku do bazy danych. Na końcu funkcja zwraca odpowiedź HTTP z kodem stanu 200 oraz nagłówkami "Access-Control-Allow" i ciałem odpowiedzi w formacie JSON.
 
Rysunek 7 Kod funkcji CreateUserPool, będący częścią Lambdy StartNewProject
Ten kod to funkcja w języku Python, która tworzy nową pulę użytkowników AWS Cognito za pomocą AWS SDK dla Python (boto3).Funkcja przyjmuje jedno wejściowe parametr "user_pool_name", który określa nazwę nowej puli użytkowników. Wewnątrz funkcji definiuje się politykę hasła dla puli użytkowników, która wymusza minimalną długość hasła oraz wymaga, aby hasło zawierało przynajmniej jedną małą literę, jedną dużą literę, jedną cyfrę i jeden znak specjalny. Następnie funkcja tworzy klienta AWS Cognito, używając metody "create_user_pool" i przekazując odpowiednie parametry, takie jak nazwa puli użytkowników, polityki hasła, konfiguracja tworzenia użytkowników przez administratorów, atrybuty zweryfikowane automatycznie i atrybuty użytkownika, MFA configuration. Po utworzeniu puli użytkowników funkcja zwraca jej identyfikator (ID) i zasób Amazon Resource Name (ARN) w formacie słownika (dictionary) zawierającego "id" i "arn".W trakcie wykonywania funkcji, wywołania print() służą do wypisania na konsoli informacji o odpowiedzi z serwisu AWS po utworzeniu nowej puli użytkowników.
 
Rysunek 8 Kod funkcji CreateUser, będący częścią Lambdy StartNewProject
Ten kod to funkcja w języku Python, która tworzy nowego użytkownika w puli użytkowników AWS Cognito za pomocą AWS SDK dla Python (boto3). Funkcja przyjmuje dwa parametry wejściowe: identyfikator puli użytkowników i adres e-mail nowego użytkownika. Następnie tworzony jest nowy użytkownik w puli, a funkcja zwraca jego nazwę użytkownika. Wywołania print() są używane do wypisania informacji o odpowiedzi z serwisu AWS po utworzeniu nowego użytkownika.

 
Rysunek 9 Kod funkcji AddUserToGroup oraz AddItemToDB, będący częścią Lambdy StartNewProject
Ten kod zawiera dwie funkcje. Pierwsza funkcja AddUserToGroup dodaje istniejącego użytkownika do grupy użytkowników w puli AWS Cognito. Przyjmuje ona trzy parametry wejściowe: identyfikator puli użytkowników, nazwę użytkownika i nazwę grupy.

Druga funkcja AddItemToDB dodaje nowy rekord do tabeli w usłudze AWS DynamoDB. Przyjmuje ona siedem parametrów wejściowych, w tym nazwę tabeli i wartości pól, które mają zostać zapisane w nowym rekordzie. Wywołania print() są używane do wypisania informacji o odpowiedzi z serwisu AWS po zapisaniu nowego rekordu.
Rysunek 10 Kod funkcji CreateDomain oraz CreateClient, będący częścią Lambdy StartNewProject
Ten fragment kodu zawiera dwie funkcje CreateDomain oraz CreateClient. Funkcja CreateDomain tworzy domenę dla nowego użytkownika w bazie danych Amazon Cognito. Na wejściu przyjmuje id puli użytkowników (user_pool_id) oraz nazwę projektu (project_name). Domena jest tworzona na podstawie nazwy projektu i dodatkowej stałej ciągu znaków. Funkcja zwraca nazwę utworzonej domeny. Funkcja CreateClient tworzy klienta OAuth 2.0 dla puli użytkowników Amazon Cognito. Na wejściu przyjmuje id puli użytkowników (user_pool_id), nazwę klienta (client_name) oraz adres URL zwrotny (callback_url). Funkcja generuje również tajny klucz klienta. Zwraca ona ClientId, który jest identyfikatorem klienta.

Rozdział 4. Frontend
Rozpoczynamy etap tworzenia oprawy graficznej korzystając z CSS. Obecne efekty przedstawione są na rys. 7 i 8. Nie jest to jednak końcowy efekt. 
 
Rysunek 11 Przykładowy ekran końcowy od strony Superadmina

 
Rysunek 12 Przykładowy ekran końcowy od strony Techusera


Rozdział 5. Badania i wnioski

Sekcja zostanie wypełniona podczas fazy testowania programu
