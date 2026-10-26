---
title: DateTimeOffset
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Zawiera datę i godzinę w ciągu dnia względem skoordynowanego czasu uniwersalnego. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 235
url: /pl/system/datetimeoffset/
---
## DateTimeOffset klasa

Zawiera datę i godzinę w ciągu dnia względem skoordynowanego czasu uniwersalnego. Obiekty tej klasy powinny być alokowane wyłącznie za pomocą funkcji [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, gdyż spowoduje to błędy czasu wykonywania i/lub awarie asercji. Zawsze umieszczaj tę klasę w wskaźniku [System::SmartPtr](../smartptr/) i używaj tego wskaźnika, aby przekazać go do funkcji jako argument.

```cpp
class DateTimeOffset
```

## Metody

| Metoda | Opis |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Dodaje określony przedział czasu do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Dodaje określoną liczbę dni do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Dodaje określoną liczbę godzin do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Dodaje określoną liczbę milisekund do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Dodaje określoną liczbę minut do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Dodaje określoną liczbę miesięcy do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Dodaje określoną liczbę sekund do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Dodaje określoną liczbę ticków do obiektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Dodaje określoną liczbę lat do obiektu [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Porównuje dwa obiekty [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Porównuje dwa obiekty [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Porównuje dwa obiekty [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Konstruktor domyślny. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Sprawdza, czy dwa obiekty [DateTimeOffset](./) reprezentują ten sam punkt w czasie. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Sprawdza, czy dwa obiekty [DateTimeOffset](./) reprezentują ten sam punkt w czasie. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Sprawdza, czy dwa obiekty [DateTimeOffset](./) reprezentują ten sam punkt w czasie. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Sprawdza, czy dwa obiekty [DateTimeOffset](./) reprezentują ten sam punkt w czasie i mają ten sam offset. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Sprawdza, czy dwa obiekty [DateTimeOffset](./) reprezentują ten sam punkt w czasie i mają ten sam offset. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) czas pliku do daty i godziny z lokalnym offsetem czasu. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time na obiekt [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time na obiekt [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Pobiera komponent daty bieżącego obiektu. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Pobiera wartość [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Pobiera dzień miesiąca bieżącego obiektu. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Pobiera dzień tygodnia bieżącego obiektu. |
| int [get_DayOfYear](./get_dayofyear/)() const | Pobiera dzień roku bieżącego obiektu. |
| int [get_Hour](./get_hour/)() const | Pobiera komponent godziny bieżącego obiektu. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Pobiera wartość [DateTime](../datetime/) reprezentującą lokalną datę i godzinę. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Pobiera komponent milisekundy bieżącego obiektu. |
| int [get_Minute](./get_minute/)() const | Pobiera komponent minuty bieżącego obiektu. |
| int [get_Month](./get_month/)() const | Pobiera komponent miesiąca bieżącego obiektu. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Pobiera [DateTimeOffset](./), którego data i godzina są ustawione na bieżący czas lokalny, a offset jest ustawiony na offset czasu lokalnego. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Pobiera offset względem UTC. |
| constexpr int [get_Second](./get_second/)() const | Pobiera komponent sekundy bieżącego obiektu. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Pobiera liczbę ticków bieżącego obiektu. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Pobiera czas dnia bieżącego obiektu. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Pobiera wartość [DateTime](../datetime/) reprezentującą datę i godzinę UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Pobiera [DateTimeOffset](./), którego data i godzina są ustawione na bieżący czas UTC, a offset jest [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Pobiera liczbę ticków bieżącego obiektu w czasie UTC. |
| int [get_Year](./get_year/)() const | Pobiera komponent roku bieżącego obiektu. |
| int [GetHashCode](./gethashcode/)() const | Pobiera kod skrótu dla bieżącego obiektu [DateTimeOffset](./). |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt i określony obiekt [DateTimeOffset](./) reprezentują odrębne wartości daty i godziny. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTimeOffset](./), która reprezentuje wartość daty i godziny będącą sumą wartości reprezentowanej przez bieżący obiekt i określonego przedziału czasu. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Zwraca nową instancję klasy [DateTimeOffset](./), reprezentującą wartość daty i godziny będącą wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Zwraca instancję klasy [TimeSpan](../timespan/), która reprezentuje przedział czasu pomiędzy wartościami daty i godziny reprezentowanymi przez bieżący i określony obiekt. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt reprezentuje wartość daty i godziny wcześniejszą niż wartość reprezentowana przez określony obiekt [DateTimeOffset](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt reprezentuje wartość daty i godziny wcześniejszą lub równą wartości reprezentowanej przez określony obiekt [DateTimeOffset](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt i określony obiekt [DateTimeOffset](./) reprezentują tę samą wartość daty i godziny. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt reprezentuje wartość daty i godziny późniejszą niż wartość reprezentowana przez określony obiekt [DateTimeOffset](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Określa, czy bieżący obiekt reprezentuje wartość daty i godziny późniejszą lub równą wartości reprezentowanej przez określony obiekt [DateTimeOffset](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków na odpowiednik [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonego dostawcy formatu i stylu formatowania. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonego formatu, dostawcy formatu i stylu formatowania. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konwertuje podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonych formatów, dostawcy formatu i stylu formatowania. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Odejmuje określony przedział czasu od bieżącego obiektu. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Odejmuje określoną wartość [DateTimeOffset](./) od bieżącego obiektu. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Konwertuje bieżący obiekt na czas pliku [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Konwertuje bieżący obiekt na obiekt, który reprezentuje czas lokalny. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Zastępuje offset bieżącego obiektu podanym offsetem. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konwertuje bieżący obiekt na string przy użyciu określonego formatu i dostawcy formatu. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konwertuje bieżący obiekt na string przy użyciu określonego dostawcy formatu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konwertuje bieżący obiekt na string przy użyciu określonego formatu. |
| [String](../string/) [ToString](./tostring/)() const | Konwertuje bieżący obiekt na string. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Konwertuje bieżący obiekt na obiekt, który reprezentuje czas UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Pobiera milisekundy upłynęły od początku epoki Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Pobiera sekundy upłynęły od początku epoki Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Próbuje przekonwertować podany ciąg znaków na obiekt [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Próbuje przekonwertować podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonego dostawcy formatu i stylu formatowania. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Próbuje przekonwertować podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonych formatów, dostawcy formatu i stylu formatowania. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Próbuje przekonwertować podany ciąg znaków na obiekt [DateTimeOffset](./) przy użyciu określonego formatu, dostawcy formatu i stylu formatowania. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca obiekt [TypeInfo](../typeinfo/), który reprezentuje strukturę [TimeSpan](../timespan/). |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Pobiera maksymalny offset w tickach. |
| static [MaxValue](./maxvalue/) | Pobiera największą wartość [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Pobiera minimalny offset w tickach. |
| static [MinValue](./minvalue/) | Pobiera najwcześniejszą wartość [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Pobiera początek epoki Unix. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)