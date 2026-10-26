---
title: HebrewCalendar
second_title: Aspose.Slides pro C++ API Reference
description: "Hebrejský kalendář. Objektům této třídy by mělo být alokováno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 144
url: /cs/system.globalization/hebrewcalendar/
---
## Třída HebrewCalendar

Hebrejský kalendář. Objektům této třídy by mělo být alokováno pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class HebrewCalendar : public System::Globalization::Calendar
```

## Metody

| Method | Description |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Vytvoří kopii aktuálního objektu a vrátí na něj sdílený ukazatel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Získá typ algoritmu. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Získá index aktuální éry. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Získá hodnotu aktuální éry. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Získá seznam epoch existujících v kalendáři. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontroluje, zda je kalendář jen pro čtení. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximální časový bod podporovaný kalendářem. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimální časový bod podporovaný kalendářem. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Získá poslední rok, který lze reprezentovat dvoumístným číslem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Získá den v měsíci pro daný časový bod. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Získá den v týdnu pro daný časový bod. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Získá den v roce pro daný časový bod. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Získá počet dnů ve specifickém měsíci. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Získá počet dnů ve specifickém měsíci. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Získá počet dnů ve specifickém roce. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Získá počet dnů ve specifickém roce. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Získá éru pro daný časový bod. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Získá hodiny pro daný časový bod. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Získá přestupný měsíc pro daný rok. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Informace RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Informace RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Získá milisekundy pro daný časový bod. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Získá minuty pro daný časový bod. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Získá měsíc pro daný časový bod. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Získá počet měsíců v daném roce. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Získá počet měsíců v daném roce. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Získá počet měsíců v daném roce. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Získá sekundy pro daný časový bod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Získá týden v roce pro daný časový bod. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Získá rok pro daný časový bod. |
|  [HebrewCalendar](./hebrewcalendar/)() | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
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
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Získá verzi kalendáře jen pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Nastaví poslední rok, který lze reprezentovat dvoumístným číslem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Sestaví objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Sestaví objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Sestaví objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Převede rok na čtyřciferný rok pomocí vlastnosti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání podle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [HebrewEra](./hebrewera/) | Aktuální hebrejská éra. |

## Viz také

* Třída [Calendar](../calendar/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)