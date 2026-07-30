---
title: CultureInfo
second_title: Aspose.Slides pro C++ API Reference
description: "Sbírka hodnot a algoritmů specifických pro kulturu. Operace nastavování jsou povoleny pouze u objektů, které nejsou jen pro čtení. Objektů této třídy by měly být alokovány výhradně pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 53
url: /cs/system.globalization/cultureinfo/
---
## CultureInfo třída

Sbírka hodnot a algoritmů specifických pro kulturu. Operace nastavení jsou povoleny pouze u objektů, které nejsou pouze pro čtení. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání objektu funkcím jako argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Metody

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Obnoví uložené informace o kultuře. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje informace o kultuře. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Vytvoří kulturu podle názvu. |
| explicit  [CultureInfo](./cultureinfo/)(int) | Informace RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Konstruktor. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Vždy vyhodí ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porovnává objekty. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Získá kalendář používaný kulturou. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Získá porovnávač řetězců, který dodržuje pravidla kultury. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Získá bitový součet typů kultur, který popisuje aktuální kulturu. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Získá kulturu nastavenou pro aktuální vlákno. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Získá UI kulturu aktuálního vlákna. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Získá informace o formátu data. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Získá výchozí kulturu v aktuální aplikační doméně. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Získá výchozí UI kulturu v aktuální aplikační doméně. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Získá zobrazovaný název kultury. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Získá anglický název kultury. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Získá název podle RFC 4646 pro jazyk. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Získá kulturu nainstalovanou v operačním systému. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Získá invariantní kulturu. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Kontroluje, zda je kultura neutrální. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kontroluje, zda je objekt kultury pouze pro čtení. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Získá identifikátor aktivního vstupního národního prostředí. |
| virtual int [get_LCID](./get_lcid/)() const | Získá identifikátor kultury. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Získá název kultury. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Získá nativní název kultury. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Získá informace o formátu čísel. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Seznam kalendářů, které lze použít s kulturou. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Získá nadřazenou kulturu. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Získá textové parametry používané kulturou. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Získá třípísmenný kód jazyka ISO 639-2. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Získá třípísmenný kód jazyka podle definice v API [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Získá dvojpísmenný název jazyka ISO spjatý s kulturou. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Získá příznak indikující, zda [CultureInfo](./) používá uživatelem vybraná nastavení kultury. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Získá alternativní kulturu vhodnou pro konzolové aplikace. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Získá kulturu podle jejího názvu. Stejné jako CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Získá kulturu podle jejího názvu. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Získá kulturu podle ID. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Zastaralé. Získá objekt [CultureInfo](./) pouze pro čtení podle zadané značky jazyka RFC 4646. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Získá kultury, které spadají do specifikovaných typů. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Získá objekt formátu pro konkrétní typ. |
| int [GetHashCode](./gethashcode/)() const override | Vrací hash kód objektu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analogie operátoru C# 'is'. |
| **bool** [IsInherited](./isinherited/)() const | Získá příznak zděděnosti. PRO INTERNÍ POUŽITÍ. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Porovnává parametry kultury. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Získá verzi kultury pouze pro čtení. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Nastaví kulturu pro aktuální vlákno. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Nastaví UI kulturu aktuálního vlákna. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Nastaví informace o formátu data. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Nastaví výchozí kulturu v aktuální aplikační doméně. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Nastaví výchozí UI kulturu v aktuální aplikační doméně. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Získá informace o formátu čísel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Převede kulturu na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání příkazu C# lock(). Volat přímo nebo použít objekt watchdog [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Třída [IFormatProvider](../../system/iformatprovider/)
* Třída [ICloneable](../../system/icloneable/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)