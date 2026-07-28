---
title: ResultValueTask
second_title: Aspose.Slides C++ API hivatkozás
description: Olyan hibrid feladat-szerű típust képvisel, amely közvetlen eredményértéket vagy egy ResultTask<T>-t is képes becsomagolni.
type: docs
weight: 53
url: /hu/system.threading.tasks/resultvaluetask/
---
## ResultValueTask osztály

Representál egy hibrid feladat-szerű típust, amely közvetlen eredményértéket vagy egy ResultTask<T>-t is képes becsomagolni.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A feladat által előállított eredmény típusa. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Átalakítja ezt a [ResultValueTask](./)-t egy megosztott mutatóvá a ResultTask<T>-hez. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Konfigurál egy awaitert ehhez a feladathoz. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Megállapítja, hogy ez a példány egyenlő-e egy másik [ResultValueTask](./) példánnyal. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Megállapítja, hogy ez a példány egyenlő-e egy másik objektummal. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Megállapítja, hogy a jelenlegi és a megadott objektum egyenlőek-e. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Lekéri azt az értéket, amely jelzi, hogy a feladat a megszakítás miatt fejeződött be. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Lekéri azt az értéket, amely jelzi, hogy a feladat befejeződött. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Lekéri azt az értéket, amely jelzi, hogy a feladat sikeresen fejeződött be. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Lekéri azt az értéket, amely jelzi, hogy a feladat nem kezelt kivétel miatt fejeződött be. |
| T [get_Result](./get_result/)() | Lekéri a befejezett feladat eredményét. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Lekéri az awaitert ehhez a feladathoz az await kifejezések támogatásához. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás szerinti konstrukcióját. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Nem egyenlőség operátor a [ResultValueTask](./)-hez. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás szerinti konstrukcióját. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Egyenlőség operátor a [ResultValueTask](./)-hez. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [ResultValueTask](./resultvaluetask/)() | Egy üres, inicializálatlan [ResultValueTask](./)-t hoz létre. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | Létrehoz egy befejezett [ResultValueTask](./)-t a megadott eredménnyel. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Létrehoz egy [ResultValueTask](./)-t egy ResultTask<T>-re mutató megosztott mutatóból. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi, hogy a tárolók mutatóit gyenge módba állítsuk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

[ResultValueTask](./) kombinálja a [ValueTask](../valuetask/) (szinkron eredmények csökkentett memóriafoglalása) előnyeit a meglévő ResultTask<T> objektumok becsomagolásának lehetőségével. Awaitelhető interfészt és különféle feladatállapot-ellenőrző metódusokat biztosít.

## Lásd még

* Osztály [IEquatable](../../system/iequatable/)
* Névtér [System::Threading::Tasks](../)
* Könyvtár [Aspose.Slides](../../)