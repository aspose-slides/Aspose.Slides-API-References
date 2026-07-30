---
title: TimeZone
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Reprezentuje časové pásmo. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 1327
url: /cs/system/timezone/
---
## TimeZone třída

Represents a time zone. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TimeZone : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | Vrací novou instanci třídy [TimeZone](./), která představuje aktuální časové pásmo. |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | Vrací název letního času časového pásma reprezentovaného aktuálním objektem. |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | Vrací název standardního času časového pásma reprezentovaného aktuálním objektem. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získává datovou strukturu čítače referencí spojenou s objektem. |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | Vrací období letního času pro konkrétní rok. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../object/gettype/). |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | Vrací posun UTC pro zadaný místní čas. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného pomocí targetType. Analogie operátoru C# 'is'. |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | Určuje, zda hodnota data a času reprezentovaná objektem [DateTime](../datetime/) spadá do rozsahu letního času pro časové pásmo reprezentované aktuálním objektem [TimeZone](./). |
| void [Lock](../object/lock/)() | Implementuje zamykání výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogie metody C# [Object.ToString()](../object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../object/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)