---
title: Object
second_title: Aspose.Slides pro C++ API Reference
description: Základní třída, která umožňuje používat metody dostupné pro třídu System.Object v C#. Všechny ne-triviální třídy použité v přeloženém prostředí by měly tuto třídu dědit.
type: docs
weight: 1132
url: /cs/system/object/
---
## Třída objektu

Základní třída, která umožňuje používat metody dostupné pro třídu [System.Object](./) v C#. Všechny ne-triviální třídy použité v přeloženém prostředí by měly tuto třídu dědit.

```cpp
class Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compares objects using C# [Object.Equals](./equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analog of C# [Object.GetHashCode()](./gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](./gettype/) call. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](./lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](./memberwiseclone/) method. Enables cloning custom types. |
|  [Object](./object/)() | Creates object. Initializes all internal data structures. |
|  [Object](./object/)([Object](./) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](./sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog of C# [Object.ToString()](./tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implements C# typeof([System.Object](./)) construct. |
| void [Unlock](./unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](./~object/)() | Destroys object. Frees all internal data structures. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ptr](./ptr/) | Alias for smart pointer type. |

## Poznámky

Spolu s metodami dostupnými ve třídě C# [System.Object](./) poskytuje také podporu některých konceptů specifických pro přeložené prostředí kódu. To zahrnuje počítání referencí používané třídami inteligentních ukazatelů ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) a další služby související s řízením paměti, laděním atd.

Každý [Object](./) má dva čítače referencí: sdílený čítač referencí a slabý čítač referencí. Slabý čítač referencí je vždy uložen v oddělené datové struktuře, nikoli přímo v [Object](./), což umožňuje slabým ukazatelům přežít odkazovaný objekt. Inteligentní čítač referencí je uložen buď v samotném objektu, nebo ve stejné oddělené struktuře, v závislosti na stavu makra ENABLE_EXTERNAL_REFCOUNT. Ve výchozím nastavení je povolen v ladicích sestaveních a zakázán v vydaných sestaveních. Pokud je čítač inteligentních ukazatelů uložen v samotném objektu, oddělená datová struktura je vytvořena pouze v případě, že existují slabé ukazatele na objekt. V opačném případě je vytvořena spolu s objektem.

Všechny inteligentní ukazatele používají tyto dva čítače referencí a přispívají do jediné vlastnící skupiny.

Pokud je podtřída [Object](./) vytvořena na zásobníku, nesmí být k ní vytvořeny žádné inteligentní ukazatele, jinak dochází k problému s mazáním ze zásobníku.

Tento typ může být alokován buď na zásobníku jako hodnotový typ, nebo v haldě pomocí funkce [System::MakeObject()](../makeobject/). Po alokaci objektu nikdy nepleťte tyto dva případy použití: mít [SmartPtr](../smartptr/) ukazatele na objekty alokované na zásobníku je přísně zakázáno.

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)