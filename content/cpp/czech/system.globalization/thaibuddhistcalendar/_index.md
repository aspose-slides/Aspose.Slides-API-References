---
title: ThaiBuddhistCalendar
second_title: Aspose.Slides pro C++ API
description: "Thajský buddhistický kalendář. Objektům této třídy by se mělo alokovat pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to způsobí chyby za běhu a/nebo selhání aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 378
url: /cs/system.globalization/thaibuddhistcalendar/
---
## ThaiBuddhistCalendar třída

Thai Buddhist calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ThaiBuddhistCalendar : public System::Globalization::Calendar
```

## Metody

| Method | Popis |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Přidá dny k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Přidá hodiny k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Přidá milisekundy k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Přidá minuty k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Přidá měsíce k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Přidá sekundy k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Přidá týdny k časovému bodu. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Přidá roky k časovému bodu. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informace RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Vytvoří kopii aktuálního objektu a vrátí na ni sdílený ukazatel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Získá typ algoritmu. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Získá index aktuální éry. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Získá hodnotu aktuální éry. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Získá seznam epoch existujících v kalendáři. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontroluje, zda je kalendář jen pro čtení. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximální časový bod, který kalendář podporuje. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimální časový bod, který kalendář podporuje. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Získá poslední rok, který lze představit jako dvoumístný. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Získá den v měsíci pro daný časový bod. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Získá den v týdnu pro daný časový bod. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Získá den v roce pro daný časový bod. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Získá počet dnů ve specifickém měsíci. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Získá počet dnů ve specifickém měsíci. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Získá počet dnů ve specifickém měsíci. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Získá počet dnů ve specifickém roce. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Získá počet dnů ve specifickém roce. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Získá počet dnů ve specifickém roce. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Získá éru pro daný časový bod. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Získá hodiny pro daný časový bod. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Získá přestupný měsíc pro daný rok. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Získá přestupný měsíc pro daný rok. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Získá přestupný měsíc pro daný rok. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Získá milisekundy pro daný časový bod. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Získá minuty pro daný časový bod. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Získá měsíc pro daný časový bod. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Získá počet měsíců ve specifikovaném roce. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Informace RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Informace RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Získá sekundy pro daný časový bod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Získá týden v roce pro daný časový bod. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Získá rok pro daný časový bod. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Kontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Kontroluje, zda je den přestupný. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Kontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Kontroluje, zda je měsíc přestupný. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Kontroluje, zda je rok přestupný. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Kontroluje, zda je rok přestupný. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Kontroluje, zda je rok přestupný. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Kontroluje hodnoty roku, měsíce, dne a éry. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Získá verzi kalendáře jen pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží čítač sdílených odkazů o zadanou hodnotu. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Nastaví poslední rok, který lze představit jako dvoumístný. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu čítače sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší čítač sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí čítač sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [ThaiBuddhistCalendar](./thaibuddhistcalendar/)() | Konstruktor. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Vytvoří objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Vytvoří objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Vytvoří objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Převede rok na čtyřciferný rok pomocí vlastnosti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí dle C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší čítač slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží čítač slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [ThaiBuddhistEra](./thaibuddhistera/) | Aktuální thajská buddhistická éra. |

## Viz také

* Třída [Calendar](../calendar/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)