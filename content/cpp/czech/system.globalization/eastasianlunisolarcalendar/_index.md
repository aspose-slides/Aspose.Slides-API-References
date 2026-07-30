---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides pro C++ – reference API
description: "Východoasijský lunisolární kalendář. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 105
url: /cs/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar třída

East-asian lunisolar calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Metody

| Metoda | Popis |
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Vytvoří kopii aktuálního objektu a vrátí na ni sdílený ukazatel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Informace RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Získá index aktuální éry. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Získá hodnotu aktuální éry. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Získá seznam epoch existujících v kalendáři. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Získá identifikátor kalendáře. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontroluje, zda je kalendář jen pro čtení. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Maximální časový bod podporovaný kalendářem. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Minimální časový bod podporovaný kalendářem. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Získá poslední rok, který lze reprezentovat pomocí dvojciferného zápisu. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Získá nebeský kmen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Získá den v měsíci pro zadaný časový bod. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Získá den v týdnu pro zadaný časový bod. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Získá den v roce pro zadaný časový bod. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Získá počet dní ve specifickém měsíci. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Získá počet dní ve specifickém měsíci. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Získá počet dní ve specifickém roce. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Získá počet dní ve specifickém roce. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Získá epochu pro zadaný časový bod. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Získá hodiny pro zadaný časový bod. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Získá přestupný měsíc pro zadaný rok. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Získá přestupný měsíc pro zadaný rok. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Získá milisekundy pro zadaný časový bod. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Získá minuty pro zadaný časový bod. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Získá měsíc pro zadaný časový bod. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Získá počet měsíců ve zadaném roce. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Získá počet měsíců ve zadaném roce. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Získá sekundy pro zadaný časový bod. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Získá rok v šedesátičlenném cyklu. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Získá zeměpisnou větev. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Získá týden v roce pro zadaný časový bod. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Získá rok pro zadaný časový bod. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Kontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Kontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Kontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Kontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Kontroluje, zda je rok přestupný. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Kontroluje, zda je rok přestupný. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Kontroluje hodnoty roku, měsíce, dne a éry. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Získá verzi kalendáře pouze pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Nastaví poslední rok, který lze reprezentovat pomocí dvojciferného zápisu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (na rozdíl od sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu čítače sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Sestaví objekt [DateTime](../../system/datetime/) z komponent. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Sestaví objekt [DateTime](../../system/datetime/) z komponent. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Převede rok na čtyřciferný rok pomocí vlastnosti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
## Viz také

* Třída [Calendar](../calendar/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)