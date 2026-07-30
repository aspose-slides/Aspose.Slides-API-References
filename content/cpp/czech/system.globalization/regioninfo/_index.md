---
title: RegionInfo
second_title: Aspose.Slides pro C++ API Reference
description: "Poskytuje informace o regionu. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 274
url: /cs/system.globalization/regioninfo/
---
## RegionInfo třída


Poskytuje informace o regionu. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to způsobí chyby za běhu a/nebo selhání aserce. Vždy obalte tuto třídu ukazatelem [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předání do funkcí jako argument.

```cpp
class RegionInfo : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty podle C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [String](../../system/string/) [get_CurrencyEnglishName](./get_currencyenglishname/)() const | Získá anglický název měny. |
| virtual [String](../../system/string/) [get_CurrencyNativeName](./get_currencynativename/)() const | Získá nativní název měny. |
| virtual [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Získá symbol měny. |
| static [RegionInfoPtr](../regioninfoptr/) [get_CurrentRegion](./get_currentregion/)() | Získá region nastavený v systému. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Získá úplný název regionu. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Získá anglický název regionu. |
| virtual int [get_GeoId](./get_geoid/)() const | Získá jedinečný identifikátor regionu. |
| virtual **bool** [get_IsMetric](./get_ismetric/)() const | Kontroluje, zda region používá metrický systém. |
| virtual [String](../../system/string/) [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | Získá ISO symbol měny. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Získá název regionu. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Získá nativní název regionu. |
| virtual [String](../../system/string/) [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | Získá třípísmenný ISO kód regionu. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | Získá třípísmenný [Windows](../../system.windows/) kód regionu. |
| virtual [String](../../system/string/) [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | Získá dvoupísmenný ISO kód regionu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá strukturu počitadla referencí spojenou s objektem. |
| int [GetHashCode](./gethashcode/)() const override | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [RegionInfo](./)\& [operator=](./operator_equal/)(const [RegionInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnoty s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
|  [RegionInfo](./regioninfo/)(const [String](../../system/string/)\&) |  |
|  [RegionInfo](./regioninfo/)(int) | Konstruktor. |
|  [RegionInfo](./regioninfo/)(const [RegionInfo](./)\&) |  |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel ( místo sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Globalization](../)
* Knihovna [Aspose.Slides](../../)