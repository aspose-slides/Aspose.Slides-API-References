---
title: WeakReference< T >
second_title: Aspose.Slides C++ API-referencia
description: Gyenge referenciát képvisel, amely egy objektumra hivatkozik, miközben lehetővé teszi, hogy az objektum törlésre kerüljön.
type: docs
weight: 1509
url: /hu/system/weakreference_tmpl_t__end_tmpl/
---
## WeakReference< T > osztály

Gyenge referenciát képvisel, amely egy objektumra hivatkozik, miközben lehetővé teszi, hogy az objektum törlésre kerüljön.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A hivatkozott objektum típusa. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacs számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódusának megfelelője. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívásának megfelelője. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátorának megfelelője. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentry objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódusának megfelelője. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a hivatkozott objektum nem null. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | A hivatkozott objektumot összehasonlítja egy másik WeakReference osztálypéldánnyal. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Átadás operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a hivatkozott objektum null. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | A hivatkozott objektumot összehasonlítja egy másik WeakReference osztálypéldánnyal. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze referenciaként nullptr-tel. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Beállítja a jelenlegi WeakReference objektum által hivatkozott objektumot (a célt). |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | A C# [Object.ToString()](../object/tostring/) metódusának megfelelője. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Lekéri a jelenlegi WeakReference objektum által hivatkozott objektumot (a célt). |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) szerkezetet. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [WeakReference](./weakreference/)() | Alapértelmezett konstruktor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor nullptr-ból. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Inicializál egy új WeakReference osztálypéldányt, amely a megadott objektumra hivatkozik. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Inicializál egy új WeakReference osztálypéldányt, amely a megadott objektumra hivatkozik. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../object/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)