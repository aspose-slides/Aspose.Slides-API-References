---
title: IAsyncResult
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje stav asynchronní operace. Objektům této třídy by mělo být alokováno pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 898
url: /cs/system/iasyncresult/
---
## IAsyncResult class


Representuje stav asynchronní operace. Objektům této třídy by mělo být alokováno pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class IAsyncResult : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [get_AsyncState](./get_asyncstate/)() | Vrací objekt, který obsahuje informace o asynchronní operaci. |
| virtual [SharedPtr](../sharedptr/)\<[System::Threading::WaitHandle](../../system.threading/waithandle/)\> [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Vrací instanci WaitHandle, která může být použita k čekání na dokončení asynchronní operace. |
| virtual **bool** [get_CompletedSynchronously](./get_completedsynchronously/)() | Vrací hodnotu, která indikuje, zda asynchronní operace byla dokončena synchronně. |
| virtual **bool** [get_IsCompleted](./get_iscompleted/)() | Vrací hodnotu, která indikuje, zda asynchronní operace byla dokončena. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje zamykání podle C# lock(). Volejte přímo nebo použijte strážní objekt [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog metody C# [Object.ToString()](../object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí podle C# lock(). Volejte přímo nebo použijte strážní objekt [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~IAsyncResult](./~iasyncresult/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Shared pointer to [IAsyncResult](./). |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)