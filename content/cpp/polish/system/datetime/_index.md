---
title: DateTime
second_title: Referencja API Aspose.Slides dla C++
description: "Reprezentuje określoną wartość daty i czasu na kontinuum czasowym. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 222
url: /pl/system/datetime/
---
## Klasa DateTime

Reprezentuje określoną wartość daty i czasu na kontinuum czasu. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
class DateTime
```

## Metody

| Method | Description |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, która jest wynikiem dodania określonego przedziału czasu do wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby dni. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby godzin. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby milisekund. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby minut. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby miesięcy. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby sekund. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonej liczby przedziałów 100-nanosekundowych. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu równą wartości reprezentowanej przez bieżący obiekt, ale z komponentem roku zwiększonym o określoną liczbę. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Porównuje dwie wartości reprezentowane przez określone instancje klasy [DateTime](./) i zwraca wartość wskazującą względne położenie wartości na osi czasu. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Porównuje dwie wartości daty i czasu reprezentowane przez bieżący obiekt oraz określoną instancję klasy [DateTime](./) i zwraca wartość wskazującą względne położenie wartości na osi czasu. |
| constexpr [DateTime](./datetime/)() | Tworzy instancję reprezentującą najmniejszą możliwą wartość daty i czasu równą MinValue. |
| [DateTime](./datetime/)(int, int, int) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc i dzień. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc i dzień w określonym kalendarzu. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę i sekundę w określonym kalendarzu. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę, sekundę i milisekundę. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako konkretny rok, miesiąc, dzień, godzinę, minutę, sekundę i milisekundę w określonym kalendarzu. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako liczbę tików. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Tworzy instancję reprezentującą wartość daty i czasu określoną jako liczbę tików. DO UŻYTKU WEWNĘTRZNEGO. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | Tworzy instancję metodą kopiowania. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Zwraca liczbę dni w określonym miesiącu podanego roku. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Określa, czy określone instancje klasy [DateTime](./) reprezentują tę samą wartość daty i czasu. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Określa, czy określona instancja klasy [DateTime](./) reprezentuje tę samą wartość daty i czasu co bieżący obiekt. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserializuje wartość daty i czasu z podanej nieoznaczonej 64-bitowej liczby całkowitej i ustawia nową instancję klasy [DateTime](./) na tę wartość. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Konwertuje podany czas plikowy na instancję klasy [DateTime](./) reprezentującą tę samą wartość daty i czasu w czasie lokalnym. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Konwertuje podany czas plikowy na instancję klasy [DateTime](./) reprezentującą tę samą wartość daty i czasu w czasie UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Zwraca instancję klasy [DateTime](./) reprezentującą wartość daty i czasu równą podanej dacie OLE Automation. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Konwertuje podaną wartość czasu Unix na instancję klasy [DateTime](./). DO UŻYTKU WEWNĘTRZNEGO. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Zwraca nową instancję klasy [DateTime](./) reprezentującą część daty wartości daty i czasu reprezentowanej przez bieżący obiekt, przy czym każdy komponent części czasu jest ustawiony na 0. |
| int [get_Day](./get_day/)() const | Zwraca kolejny numer dnia w miesiącu reprezentowanym przez bieżący obiekt. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Zwraca wartość reprezentującą dzień tygodnia, który jest reprezentowany przez bieżący obiekt. |
| int [get_DayOfYear](./get_dayofyear/)() const | Zwraca kolejny numer dnia w roku reprezentowanym przez bieżący obiekt. |
| constexpr int [get_Hour](./get_hour/)() const | Zwraca komponent godziny wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Zwraca wartość określającą, czy data i czas reprezentowane przez bieżący obiekt są lokalne, UTC, czy żadnym z nich. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Zwraca komponent milisekund wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| constexpr int [get_Minute](./get_minute/)() const | Zwraca komponent minut wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| int [get_Month](./get_month/)() const | Zwraca kolejny numer miesiąca w roku reprezentowanym przez bieżący obiekt. |
| static [DateTime](./) [get_Now](./get_now/)() | Zwraca instancję klasy [DateTime](./) reprezentującą bieżący czas jako czas lokalny. |
| constexpr int [get_Second](./get_second/)() const | Zwraca komponent sekund wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Zwraca liczbę przedziałów 100-nanosekundowych upłyniętych od 0:00:00 UTC, 1 stycznia 0001 r., w kalendarzu gregoriańskim, do daty i czasu reprezentowanej przez bieżący obiekt. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Zwraca wartość reprezentującą przedział czasu od początku dnia reprezentowanego przez bieżący obiekt do wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| static [DateTime](./) [get_Today](./get_today/)() | Zwraca instancję klasy [DateTime](./) reprezentującą bieżącą datę, przy czym każdy komponent części czasu wartości reprezentowanej przez obiekt jest ustawiony na 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Zwraca instancję klasy [DateTime](./) reprezentującą bieżący czas jako UTC. |
| int [get_Year](./get_year/)() const | Zwraca rok reprezentowany przez bieżący obiekt. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Pobiera części daty. DO UŻYTKU WEWNĘTRZNEGO. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Zwraca tablicę łańcuchów, w której każdy element jest reprezentacją bieżącego obiektu sformatowaną przy użyciu jednego ze standardowych specyfikatorów formatu daty i czasu. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Zwraca tablicę łańcuchów, w której każdy element jest reprezentacją bieżącego obiektu sformatowaną przy użyciu określonego standardowego specyfikatora formatu daty i czasu. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Zwraca tablicę łańcuchów, w której każdy element jest reprezentacją bieżącego obiektu sformatowaną przy użyciu jednego ze standardowych specyfikatorów formatu daty i czasu oraz określonego dostawcy formatu. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Zwraca tablicę łańcuchów, w której każdy element jest reprezentacją bieżącego obiektu sformatowaną przy użyciu określonego standardowego specyfikatora formatu daty i czasu oraz dostawcy formatu. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Określa, czy wartość daty i czasu reprezentowana przez bieżący obiekt znajduje się w zakresie czasu letniego obowiązującego w bieżącej strefie czasowej. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Określa, czy podany rok jest rokiem przestępnym. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Określa, czy bieżący obiekt oraz określony obiekt [DateTime](./) reprezentują odrębne wartości daty i czasu. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonego przedziału czasu. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Ustawia bieżący obiekt na wartość daty i czasu będącą sumą wartości reprezentowanej przez bieżący obiekt oraz określonego przedziału czasu. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTime](./) reprezentującą wartość daty i czasu, będącą wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Zwraca instancję klasy [TimeSpan](../timespan/) reprezentującą przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący oraz określony obiekt. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Ustawia bieżący obiekt na wartość daty i czasu będącą wynikiem odjęcia określonego przedziału czasu od wartości daty i czasu reprezentowanej przez bieżący obiekt. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Określa, czy bieżący obiekt reprezentuje wartość daty i czasu wcześniejszą niż wartość reprezentowana przez określony obiekt [DateTime](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Określa, czy bieżący obiekt reprezentuje wartość daty i czasu wcześniejszą lub równą wartości reprezentowanej przez określony obiekt [DateTime](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Przypisuje wartość reprezentowaną przez określoną instancję [DateTime](./) bieżącemu obiektowi. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Określa, czy bieżący obiekt oraz określony obiekt [DateTime](./) reprezentują tę samą wartość daty i czasu. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Określa, czy bieżący obiekt reprezentuje wartość daty i czasu późniejszą niż wartość reprezentowana przez określony obiekt [DateTime](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Określa, czy bieżący obiekt reprezentuje wartość daty i czasu późniejszą lub równą wartości reprezentowanej przez określony obiekt [DateTime](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./). |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu informacji o formacie zależnym od kultury. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu określonego formatu i informacji o formacie zależnym od kultury. Format tekstu musi dokładnie odpowiadać określonemu formatowi. Rzuca wyjątek, jeśli konwersja się nie powiedzie. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu określonych formatów, informacji o formacie zależnym od kultury oraz stylu. Format tekstu musi dokładnie odpowiadać jednemu lub kilku z określonych formatów. Rzuca wyjątek, jeśli konwersja się nie powiedzie. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Tworzy nowy obiekt [DateTime](./), który reprezentuje taką samą liczbę tików jak określony obiekt [DateTime](./) i reprezentuje czas lokalny, czas UTC lub żaden z nich, zgodnie z argumentem **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTime](./), reprezentującą wartość daty i czasu będącą wynikiem odjęcia określonego odstępu czasu od wartości reprezentowanej przez bieżący obiekt. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Zwraca instancję klasy [TimeSpan](../timespan/), reprezentującą przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący i określony obiekt. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializuje bieżący obiekt. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Zwraca wartość, która reprezentuje wartość daty i czasu reprezentowaną przez bieżący obiekt jako File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Konwertuje wartość daty i czasu reprezentowaną przez bieżący obiekt na File time w formacie UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Zwraca nową instancję klasy [DateTime](./), która reprezentuje wartość daty i czasu reprezentowaną przez bieżący obiekt jako czas lokalny. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Zwraca ciąg znaków zawierający długą reprezentację daty bieżącego obiektu. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Zwraca ciąg znaków zawierający długą reprezentację czasu bieżącego obiektu. |
| **double** [ToOADate](./tooadate/)() const | Zwraca wartość daty i czasu reprezentowaną przez bieżący obiekt jako OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Zwraca ciąg znaków zawierający krótką reprezentację daty bieżącego obiektu. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Zwraca ciąg znaków zawierający krótką reprezentację czasu bieżącego obiektu. |
| [String](../string/) [ToString](./tostring/)() const | Zwraca reprezentację tekstową wartości daty i czasu reprezentowanej przez bieżący obiekt, używając konwencji formatowania zdefiniowanych przez bieżącą kulturę. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Zwraca reprezentację tekstową wartości daty i czasu reprezentowanej przez bieżący obiekt, używając określonego formatu oraz konwencji formatowania zdefiniowanych przez bieżącą kulturę. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Zwraca reprezentację tekstową wartości daty i czasu reprezentowanej przez bieżący obiekt, używając określonych informacji o formacie. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Zwraca reprezentację tekstową wartości daty i czasu reprezentowanej przez bieżący obiekt, używając określonych informacji o formacie. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Zwraca nową instancję klasy [DateTime](./), która reprezentuje wartość daty i czasu reprezentowaną przez bieżący obiekt jako UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Zwraca wartość, która reprezentuje wartość daty i czasu reprezentowaną przez bieżący obiekt jako czas Unix. DO WEWNĘTRZNEGO UŻYTKU. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu określonych informacji o formacie zależnym od kultury oraz stylu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu określonego formatu, informacji o formacie zależnym od kultury oraz stylu. Format tekstu musi dokładnie odpowiadać określonemu formatowi. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konwertuje podaną reprezentację tekstową wartości daty i czasu na równoważny obiekt [DateTime](./) przy użyciu określonych formatów, informacji o formacie zależnym od kultury oraz stylu. Format tekstu musi dokładnie odpowiadać jednemu lub kilku z określonych formatów. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca obiekt [TypeInfo](../typeinfo/), który zawiera informacje o tej klasie. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Liczba 100-nanosekund w przedziale czasu pomiędzy minimalną a maksymalną możliwą wartością [DateTime](./). |
| static [MaxValue](./maxvalue/) | Instancja klasy [DateTime](./), która reprezentuje maksymalną możliwą wartość daty i czasu. |
| static constexpr [MinTicks](./minticks/) | Minimalna liczba tików, którą może reprezentować instancja klasy [DateTime](./). |
| static [MinValue](./minvalue/) | Instancja klasy [DateTime](./), która reprezentuje minimalną możliwą wartość daty i czasu. |
| static constexpr [TicksPerDay](./ticksperday/) | Liczba tików w jednym dniu. |
| static constexpr [TicksPerHour](./ticksperhour/) | Liczba tików w jednej godzinie. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Liczba tików w jednej mikrosekundzie. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Liczba tików w jednej milisekundzie. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Liczba tików w jednej minucie. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Liczba tików w jednej sekundzie. |
| static [UnixEpoch](./unixepoch/) | Instancja klasy [DateTime](./), która reprezentuje początek epoki Unix (1970-01-01 00:00:00). |

## Uwagi

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Utwórz instancję klasy 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Wydrukuj instancję w wielu formatach.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)