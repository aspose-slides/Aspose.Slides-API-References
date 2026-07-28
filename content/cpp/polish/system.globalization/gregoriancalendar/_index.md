---
title: GregorianCalendar
second_title: Aspose.Slides dla API C++
description: "Kalendarz gregoriański. Obiekty tej klasy powinny być alokowane wyłącznie za pomocą funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 131
url: /pl/system.globalization/gregoriancalendar/
---
## GregorianCalendar klasa

Kalendarz gregoriański. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Dodaje dni do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Dodaje godziny do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Dodaje milisekundy do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Dodaje minuty do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Dodaje miesiące do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Dodaje sekundy do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Dodaje tygodnie do punktu w czasie. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Dodaje lata do punktu w czasie. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informacje RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Tworzy kopię bieżącego obiektu i zwraca wskaźnik współdzielony do niej. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Pobiera typ algorytmu. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | Pobiera typ kalendarza gregoriańskiego. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Pobiera indeks bieżącej ery. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Pobiera wartość bieżącej ery. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Pobiera listę er istniejących w kalendarzu. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Sprawdza, czy kalendarz jest tylko do odczytu. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maksymalny punkt w czasie obsługiwany przez kalendarz. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimalny punkt w czasie obsługiwany przez kalendarz. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Pobiera ostatni rok, który może być reprezentowany dwucyfrowo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Pobiera dzień miesiąca dla określonego punktu w czasie. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Pobiera dzień tygodnia dla określonego punktu w czasie. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Pobiera dzień roku dla określonego punktu w czasie. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Pobiera liczbę dni w określonym roku. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Pobiera liczbę dni w określonym roku. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Pobiera liczbę dni w określonym roku. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | Pobiera domyślną instancję kalendarza gregoriańskiego. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Pobiera erę dla określonego punktu w czasie. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Pobiera godziny dla określonego punktu w czasie. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Pobiera miesiąc przestępny dla określonego roku. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Pobiera miesiąc przestępny dla określonego roku. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Pobiera miesiąc przestępny dla określonego roku. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Pobiera milisekundy dla określonego punktu w czasie. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Pobiera minuty dla określonego punktu w czasie. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Pobiera miesiąc dla określonego punktu w czasie. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Pobiera liczbę miesięcy w określonym roku. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Informacje RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Informacje RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Pobiera sekundy dla określonego punktu w czasie. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Pobiera tydzień roku dla określonego punktu w czasie. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Pobiera rok dla określonego punktu w czasie. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Tworzy konkretny kalendarz gregoriański. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Sprawdza, czy rok jest przestępny. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Sprawdza, czy rok jest przestępny. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Sprawdza, czy rok jest przestępny. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Sprawdza wartości roku, miesiąca, dnia i ery. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Pobiera wersję tylko do odczytu kalendarza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Ustawia typ kalendarza gregoriańskiego. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ustawia ostatni rok, który może być reprezentowany dwucyfrowo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączenie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konwertuje rok na 4-cyfrowy przy użyciu właściwości TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [ADEra](./adera/) | Bieżąca era. |

## Zobacz również

* Klasa [Calendar](../calendar/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)