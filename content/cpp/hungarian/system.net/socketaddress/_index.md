---
title: SocketAddress
second_title: Aspose.Slides C++ API referencia
description: "Az EndPoint osztály példányairól szerializált információk tárolására használják. Az osztály objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen a típuson a stacken vagy az operator new használatával, mert ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 443
url: /hu/system.net/socketaddress/
---
## SocketAddress osztály


Used to store serialized information about the [EndPoint](../endpoint/) osztály instances. Objects of this osztály should only be allocated using [System::MakeObject()](../../system/makeobject/) függvény. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this osztály into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SocketAddress : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_Family](./get_family/)() | Visszaadja a címcsaládot. |
| **int32_t** [get_Size](./get_size/)() | Visszaadja az alapszintű puffer méretét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsounter adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| **uint8_t** [idx_get](./idx_get/)(**int32_t**) | Lekéri az alapszintű puffer egy értékét a megadott indexen. |
| void [idx_set](./idx_set/)(**int32_t**, **uint8_t**) | Beállítja az alapszintű puffer egy értékét a megadott indexen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrizze, hogy az objektum a targetType által leírt típuspéldány-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciák számát a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge pointerre (a megosztott helyett). Lehetővé teszi a konténerekben lévő pointerek gyenge módba váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsounter jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsounter értékét. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsounter értékét. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
|  [SocketAddress](./socketaddress/)([Sockets::AddressFamily](../../system.net.sockets/addressfamily/)) | Új példányt hoz létre. |
|  [SocketAddress](./socketaddress/)([Sockets::AddressFamily](../../system.net.sockets/addressfamily/), **int32_t**) | Új példányt hoz létre. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsounter értékét. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsounter értékét. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Net](../)
* Könyvtár [Aspose.Slides](../../)