---
title: IDisposable
second_title: Aspose.Slides pro C++ API Reference
description: "Definuje metodu, která uvolňuje prostředky vlastněné aktuálním objektem. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 963
url: /cs/system/idisposable/
---
## IDisposable třída

Definuje metodu, která uvolňuje prostředky vlastněné aktuálním objektem. Objektům této třídy by mělo být alokováno pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class IDisposable : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Dispose](./dispose/)() | Nedělá nic. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty podle sémantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hašování uživatelských objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získá aktuální typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený počet referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožní přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../object/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)