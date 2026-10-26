---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Kalendarz lunarny-słoneczny wschodnioazjatycki. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 105
url: /pl/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar klasa


Kalendarz lunarny-słoneczny wschodnioazjatycki. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Dodaje dni do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Dodaje godziny do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Dodaje milisekundy do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Dodaje minuty do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Dodaje miesiące do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Dodaje sekundy do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Dodaje tygodnie do punktu czasowego. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Dodaje lata do punktu czasowego. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informacje RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Tworzy kopię bieżącego obiektu i zwraca do niego wskaźnik współdzielony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Informacje RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Pobiera indeks bieżącej ery. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Pobiera wartość bieżącej ery. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Pobiera listę er istniejących w kalendarzu. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Pobiera identyfikator kalendarza. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Sprawdza, czy kalendarz jest tylko do odczytu. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Maksymalny punkt w czasie obsługiwany przez kalendarz. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Minimalny punkt w czasie obsługiwany przez kalendarz. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Pobiera ostatni rok, który może być reprezentowany dwucyfrowo. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Pobiera niebiański pęd (celestial stem). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Pobiera dzień miesiąca dla określonego punktu czasowego. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Pobiera dzień tygodnia dla określonego punktu czasowego. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Pobiera dzień roku dla określonego punktu czasowego. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Pobiera liczbę dni w określonym roku. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Pobiera liczbę dni w określonym roku. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Pobiera erę dla określonego punktu czasowego. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Pobiera godziny dla określonego punktu czasowego. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Pobiera miesiąc przestępny dla określonego roku. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Pobiera miesiąc przestępny dla określonego roku. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Pobiera milisekundy dla określonego punktu czasowego. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Pobiera minuty dla określonego punktu czasowego. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Pobiera miesiąc dla określonego punktu czasowego. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Pobiera liczbę miesięcy w określonym roku. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Pobiera liczbę miesięcy w określonym roku. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Pobiera sekundy dla określonego punktu czasowego. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Pobiera rok w cyklu sześćdziesięcioletnim. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Pobiera gałąź ziemską. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Pobiera tydzień roku dla określonego punktu czasowego. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Pobiera rok dla określonego punktu czasowego. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Sprawdza, czy rok jest przestępny. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Sprawdza, czy rok jest przestępny. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Sprawdza wartości roku, miesiąca, dnia i ery. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statement lock() z C#. Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Pobiera wersję tylko do odczytu kalendarza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty według referencji. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ustawia ostatni rok, który może być reprezentowany dwucyfrowo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruktor obiektu [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruktor obiektu [DateTime](../../system/datetime/) z komponentów. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konwertuje rok na czterocyfrowy przy użyciu właściwości TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Calendar](../calendar/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)