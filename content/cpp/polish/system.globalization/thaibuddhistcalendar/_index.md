---
title: ThaiBuddhistCalendar
second_title: Aspose.Slides dla C++ Referencja API
description: "Kalendarz tajski buddyjski. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 378
url: /pl/system.globalization/thaibuddhistcalendar/
---
## ThaiBuddhistCalendar klasa

Thai Buddhist calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ThaiBuddhistCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Tworzy kopię bieżącego obiektu i zwraca współdzielony wskaźnik do niej. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Pobiera typ algorytmu. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Pobiera indeks bieżącej ery. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Pobiera wartość bieżącej ery. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Pobiera listę er istniejących w kalendarzu. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Sprawdza, czy kalendarz jest tylko do odczytu. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maksymalny punkt w czasie obsługiwany przez kalendarz. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimalny punkt w czasie obsługiwany przez kalendarz. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Pobiera ostatni rok, który może być reprezentowany przy użyciu dwucyfrowego formatu. |
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
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołuj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Pobiera wersję tylko do odczytu kalendarza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ustawia ostatni rok, który może być reprezentowany przy użyciu dwucyfrowego formatu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
|  [ThaiBuddhistCalendar](./thaibuddhistcalendar/)() | Konstruktor. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Tworzy obiekt [DateTime](../../system/datetime/) z komponentów. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konwertuje rok na rok czterocyfrowy przy użyciu właściwości TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołuj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [ThaiBuddhistEra](./thaibuddhistera/) | Obecna era tajskiego buddyjskiego kalendarza. |

## Zobacz także

* Klasa [Calendar](../calendar/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)