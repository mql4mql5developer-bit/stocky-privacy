# Polityka Prywatności / Privacy Policy — Stocky

---

# 🇵🇱 Polityka Prywatności

**Ostatnia aktualizacja:** 12.05.2026

## 1. Kto jest administratorem danych?

Aplikacja Stocky jest tworzona i utrzymywana przez:
**[mql4mql5developer]**
Kontakt: [mql4mql5developer@gmail.com]

## 2. Jakie dane zbiera aplikacja?

**Dane wprowadzone bezpośrednio przez użytkownika** — w tym nazwy przedmiotów, ich ilości, komentarze w dzienniku, nazwy paneli, własne linki oraz konfiguracja powiadomień — są przechowywane **wyłącznie lokalnie na urządzeniu użytkownika** w bazie danych aplikacji (Room/SQLite). Twórca aplikacji nie ma do nich dostępu i nie są one przesyłane na żadne serwery.

Aplikacja korzysta jednak z **usług zewnętrznych firmy Google** (Firebase oraz Google AdMob), które — niezależnie od działań użytkownika — mogą gromadzić pewne dane techniczne i analityczne na potrzeby działania reklam, statystyk użytkowania oraz zdalnej konfiguracji aplikacji. Szczegóły opisano w sekcji 6.

## 3. Dane zdrowotne

Aplikacja umożliwia przechowywanie informacji dotyczących materiałów medycznych stosowanych w terapii cukrzycy (np. wkłucia, sensory, insulina, paski testowe). Dane te:

* są przechowywane wyłącznie na urządzeniu użytkownika,
* nie są wysyłane do żadnych serwerów,
* nie są udostępniane stronom trzecim,
* nie są przetwarzane przez twórcę aplikacji,
* **nie są przekazywane do usług Firebase ani AdMob** — usługi te nie mają dostępu do treści wprowadzanych przez użytkownika.

## 4. Uprawnienia systemowe

Aplikacja może korzystać z następujących uprawnień systemu Android:

| Uprawnienie | Cel |
|---|---|
| `POST_NOTIFICATIONS` | Wysyłanie powiadomień o niskim stanie zapasów |
| `RECEIVE_BOOT_COMPLETED` | Przywrócenie zaplanowanych powiadomień po restarcie urządzenia |
| `SCHEDULE_EXACT_ALARM` | Planowanie dokładnych powiadomień (Android 12+) |
| `INTERNET` | Pobieranie zdalnej konfiguracji (Firebase) oraz wyświetlanie reklam (AdMob) |
| `ACCESS_NETWORK_STATE` | Sprawdzanie dostępności sieci przed pobraniem konfiguracji i reklam |

Żadne z powyższych uprawnień nie jest wykorzystywane do zbierania danych osobowych wprowadzanych w aplikacji.

## 5. Pliki CSV

Funkcja eksportu CSV tworzy pliki na urządzeniu użytkownika. Pliki te zawierają dane wprowadzone przez użytkownika i są zapisywane w wybranej przez niego lokalizacji. Twórca aplikacji nie ma dostępu do tych plików.

## 6. Usługi zewnętrzne

Aplikacja integruje następujące usługi zewnętrzne dostarczane przez firmę **Google LLC**:

### 6.1. Google AdMob (reklamy)

Aplikacja wyświetla baner reklamowy za pośrednictwem usługi Google AdMob. AdMob może zbierać dane urządzenia, w tym:

* **identyfikator reklamowy** (Advertising ID),
* **model i wersję urządzenia**, wersję systemu operacyjnego,
* **przybliżoną lokalizację** (na podstawie adresu IP),
* informacje o wyświetleniach i kliknięciach reklam,
* dane potrzebne do mierzenia zasięgu i skuteczności reklam.

Dzięki temu **Google może zliczać uruchomienia aplikacji, wyświetlenia reklam i interakcje z nimi** — niezależnie od działań twórcy aplikacji. Użytkownik może zrezygnować z reklam spersonalizowanych w ustawieniach urządzenia: **Ustawienia → Prywatność → Reklamy**.

### 6.2. Firebase Remote Config (zdalna konfiguracja)

Aplikacja korzysta z usługi Firebase Remote Config do **zdalnego zarządzania treścią ekranów „Polecane sklepy" oraz „Sklep"** (lista linków do zewnętrznych sklepów). Dzięki temu twórca może aktualizować polecane linki bez konieczności wydawania nowej wersji aplikacji. W ramach tej usługi Firebase może gromadzić:

* **identyfikator instalacji Firebase** (Firebase Installation ID),
* dane techniczne urządzenia niezbędne do dostarczenia konfiguracji,
* informacje o liczbie pobrań konfiguracji.

### 6.3. Firebase Analytics (statystyki użytkowania)

Wraz z Firebase Remote Config aplikacja automatycznie korzysta z usługi Firebase Analytics, która gromadzi **anonimowe dane statystyczne** o korzystaniu z aplikacji, m.in.:

* liczbę uruchomień aplikacji i czas trwania sesji,
* informacje o otwieranych ekranach,
* model urządzenia, wersję systemu, język, kraj (przybliżona lokalizacja na podstawie IP),
* identyfikator instalacji Firebase oraz identyfikator reklamowy (jeśli udostępniony),
* zdarzenia związane z aktualizacjami i awariami aplikacji.

Dane te są wykorzystywane wyłącznie w formie zagregowanej, w celu zrozumienia sposobu korzystania z aplikacji i poprawy jej działania. **Nie zawierają one treści wprowadzanych przez użytkownika** (nazw przedmiotów, stanów zapasów, wpisów w dzienniku, danych zdrowotnych).

### 6.4. Polityka Google

Wszystkie powyższe usługi podlegają polityce prywatności firmy Google, dostępnej pod adresem:
**[policies.google.com/privacy](https://policies.google.com/privacy)**

### 6.5. Linki zewnętrzne

Ekran „Linki" oraz „Sklep" mogą zawierać odnośniki do zewnętrznych stron internetowych (np. sklepów). Kliknięcie w te linki spowoduje otwarcie strony w przeglądarce lub WebView — polityka prywatności tych stron jest odrębna i regulowana przez ich właścicieli.

## 7. Dzieci

Aplikacja nie jest skierowana do dzieci poniżej 13. roku życia i nie zbiera świadomie danych od dzieci.

## 8. Zmiany w polityce prywatności

Wszelkie zmiany w niniejszej polityce będą publikowane pod tym samym adresem URL. W przypadku istotnych zmian użytkownicy mogą zostać poinformowani za pośrednictwem aktualizacji aplikacji.

## 9. Kontakt

W sprawach dotyczących prywatności prosimy o kontakt pod adresem:
**[mql4mql5developer@gmail.com]**

---

---

# 🇬🇧 Privacy Policy

**Last updated:** 2026-05-12

## 1. Who is the data controller?

The Stocky app is developed and maintained by:
**[mql4mql5developer]**
Contact: [mql4mql5developer@gmail.com]

## 2. What data does the app collect?

**Data entered directly by the user** — including item names, quantities, journal comments, panel names, custom links, and notification settings — is stored **exclusively on the user's device** in the app's local database (Room/SQLite). The app developer has no access to this data, and it is never transmitted to any server.

However, the app uses **third-party services provided by Google** (Firebase and Google AdMob), which — independently of the user's actions — may collect certain technical and analytical data for the purpose of serving ads, gathering usage statistics, and delivering remote configuration. Details are described in Section 6.

## 3. Health-related data

The app allows users to store information about medical supplies used in diabetes management (e.g. infusion sets, sensors, insulin, test strips). This data:

* is stored solely on the user's device,
* is never sent to any server,
* is never shared with third parties,
* is never processed by the app developer,
* **is never transmitted to Firebase or AdMob** — these services do not have access to user-entered content.

## 4. System permissions

The app may use the following Android system permissions:

| Permission | Purpose |
|---|---|
| `POST_NOTIFICATIONS` | Sending low-stock reminder notifications |
| `RECEIVE_BOOT_COMPLETED` | Restoring scheduled notifications after device restart |
| `SCHEDULE_EXACT_ALARM` | Scheduling precise notifications (Android 12+) |
| `INTERNET` | Fetching remote configuration (Firebase) and serving ads (AdMob) |
| `ACCESS_NETWORK_STATE` | Checking network availability before fetching configuration and ads |

None of these permissions are used to collect personal data entered into the app.

## 5. CSV files

The CSV export feature creates files on the user's device. These files contain user-entered data and are saved to a location chosen by the user. The app developer has no access to these files.

## 6. Third-party services

The app integrates the following third-party services provided by **Google LLC**:

### 6.1. Google AdMob (advertising)

The app displays a banner advertisement through Google AdMob. AdMob may collect device data, including:

* **advertising ID**,
* **device model and version**, operating system version,
* **approximate location** (based on IP address),
* information about ad impressions and clicks,
* data needed to measure ad reach and effectiveness.

As a result, **Google may count app launches, ad impressions, and user interactions with ads** — independently of the app developer's actions. You can opt out of personalized ads in your device settings: **Settings → Privacy → Ads**.

### 6.2. Firebase Remote Config (remote configuration)

The app uses Firebase Remote Config to **remotely manage the content of the "Recommended shops" and "Shop" screens** (list of external shop links). This allows the developer to update recommended links without releasing a new app version. As part of this service, Firebase may collect:

* **Firebase Installation ID**,
* technical device data required to deliver the configuration,
* information about the number of configuration fetches.

### 6.3. Firebase Analytics (usage statistics)

Together with Firebase Remote Config, the app automatically uses Firebase Analytics, which collects **anonymous statistical data** about app usage, including:

* number of app launches and session duration,
* information about screens opened,
* device model, OS version, language, country (approximate location based on IP),
* Firebase Installation ID and advertising ID (if available),
* events related to app updates and crashes.

This data is used only in aggregated form, for the purpose of understanding how the app is used and improving its functionality. **It does not contain content entered by the user** (item names, stock levels, journal entries, or health-related data).

### 6.4. Google's policy

All of the above services are subject to Google's privacy policy, available at:
**[policies.google.com/privacy](https://policies.google.com/privacy)**

### 6.5. External links

The "Links" and "Shop" screens may contain links to external websites (e.g. online shops). Clicking these links will open the site in a browser or WebView — the privacy practices of those sites are governed by their own privacy policies.

## 7. Children

The app is not directed at children under the age of 13 and does not knowingly collect data from children.

## 8. Changes to this policy

Any changes to this policy will be published at the same URL. Users may be notified of significant changes through an app update.

## 9. Contact

For any privacy-related inquiries, please contact us at:
**[mql4mql5developer@gmail.com]**

