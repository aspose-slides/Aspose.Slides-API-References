---
title: HijriCalendar
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Hijri kalendář. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předávání jako argument funkcím."
type: docs
weight: 157
url: /cs/system.globalization/hijricalendar/
---
## HijriCalendar třída

Hijri kalendář. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předávání jako argument funkcím.

```cpp
class HijriCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Vytvoří kopii aktuálního objektu a vrátí na něj sdílený ukazatel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Získá typ algoritmu. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Získá index aktuální éry. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Získá hodnotu aktuální éry. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Získá seznam epoch existujících v kalendáři. |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | Získá hijri úpravu. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Zkontroluje, zda je kalendář jen pro čtení. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximální časový bod podporovaný kalendářem. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimální časový bod podporovaný kalendářem. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Získá poslední rok, který lze vyjádřit dvoumístným číslem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Získá den v měsíci pro zadaný časový bod. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Získá den v týdnu pro zadaný časový bod. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Získá den v roce pro zadaný časový bod. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Získá počet dní ve specifickém měsíci. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Získá počet dní ve specifickém měsíci. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Získá počet dní ve specifickém roce. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Získá počet dní ve specifickém roce. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Získá éru pro zadaný časový bod. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Získá hodiny pro zadaný časový bod. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Získá přestupný měsíc pro zadaný rok. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Informace RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Informace RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Získá milisekundy pro zadaný časový bod. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Získá minuty pro zadaný časový bod. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Získá měsíc pro zadaný časový bod. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Získá počet měsíců ve specifikovaném roce. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Získá počet měsíců ve specifikovaném roce. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Získá sekundy pro zadaný časový bod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Získá týden v roce pro zadaný časový bod. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Získá rok pro zadaný časový bod. |
|  [HijriCalendar](./hijricalendar/)() | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) override | Zkontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Zkontroluje, zda je den přestupný. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Zkontroluje, zda je den přestupný. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) override | Zkontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Zkontroluje, zda je měsíc přestupný. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Zkontroluje, zda je měsíc přestupný. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) override | Zkontroluje, zda je rok přestupný. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Zkontroluje, zda je rok přestupný. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Zkontroluje, zda je rok přestupný. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Zkontroluje hodnoty roku, měsíce, dne a éry. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání dle C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Získá verzi kalendáře jen pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referenčně hodnotový typ s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | Nastaví hijri úpravu. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Nastaví poslední rok, který lze vyjádřit dvoumístným číslem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Nastaví objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Nastaví objekt [DateTime](../../system/datetime/) ze součástí. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Převede rok na čtyřciferný pomocí vlastnosti TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí dle C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | Aktuální hijri éra. |

## Viz také

* Třída [Calendar](../calendar/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)