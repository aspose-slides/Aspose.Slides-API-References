---
title: HijriCalendar
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Kalendarz hijri. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to powodować błędy czasu wykonania i/lub awarie asercji. Zawsze opakowuj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 157
url: /pl/system.globalization/hijricalendar/
---
## Klasa HijriCalendar

Hijri calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Dodaje dni do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Dodaje godziny do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Dodaje milisekundy do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Dodaje minuty do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Dodaje miesiące do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Dodaje sekundy do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Dodaje tygodnie do punktu czasu. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Dodaje lata do punktu czasu. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informacje RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Tworzy kopię bieżącego obiektu i zwraca wskaźnik współdzielony do niego. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Pobiera typ algorytmu. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Pobiera indeks bieżącej ery. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Pobiera wartość bieżącej ery. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Pobiera listę er istniejących w kalendarzu. |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | Pobiera korektę hijri. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Sprawdza, czy kalendarz jest tylko do odczytu. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maksymalny punkt w czasie obsługiwany przez kalendarz. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimalny punkt w czasie obsługiwany przez kalendarz. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Pobiera ostatni rok, który może być reprezentowany jako dwucyfrowy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Pobiera dzień miesiąca dla określonego punktu czasu. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Pobiera dzień tygodnia dla określonego punktu czasu. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Pobiera dzień roku dla określonego punktu czasu. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Pobiera liczbę dni w określonym miesiącu. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Pobiera liczbę dni w określonym roku. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Pobiera liczbę dni w określonym roku. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Pobiera erę dla określonego punktu czasu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Pobiera godziny dla określonego punktu czasu. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Pobiera miesiąc przestępny dla określonego roku. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Informacje RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Informacje RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Pobiera milisekundy dla określonego punktu czasu. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Pobiera minuty dla określonego punktu czasu. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Pobiera miesiąc dla określonego punktu czasu. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Pobiera liczbę miesięcy w określonym roku. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Pobiera liczbę miesięcy w określonym roku. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Pobiera sekundy dla określonego punktu czasu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Pobiera tydzień roku dla określonego punktu czasu. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Pobiera rok dla określonego punktu czasu. |
|  [HijriCalendar](./hijricalendar/)() | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) override | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Sprawdza, czy dzień jest przestępny. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) override | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Sprawdza, czy miesiąc jest przestępny. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) override | Sprawdza, czy rok jest przestępny. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Sprawdza, czy rok jest przestępny. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Sprawdza, czy rok jest przestępny. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Sprawdza wartości roku, miesiąca, dnia i ery. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Pobiera wersję tylko do odczytu kalendarza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | Ustawia korektę hijri. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ustawia ostatni rok, który może być reprezentowany jako dwucyfrowy. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruktor obiektu [DateTime](../../system/datetime/) z komponentów. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruktor obiektu [DateTime](../../system/datetime/) z komponentów. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konwertuje rok do czterocyfrowego przy użyciu właściwości TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | Bieżąca era hijri. |

## Zobacz także

* Klasa [Calendar](../calendar/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)