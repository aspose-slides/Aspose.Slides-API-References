---
title: FormatterConverter
second_title: Aspose.Slides C++ API Referencia
description: "A System::Runtime::Serialization::IFormatterConverter interfész alapvető implementációját képviseli."
type: docs
weight: 14
url: /hu/system.runtime.serialization/formatterconverter/
---
## FormatterConverter osztály

A [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/) interfész alapimplementációját képviseli.

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## Metódusok

| Method | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | Átalakít egy értéket a megadott [System::TypeInfo](../../system/typeinfo/)-ba. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) override | Átalakít egy értéket a megadott [System::TypeCode](../../system/typecode/)-ba. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket bool típusúra. |
| **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **uint8_t** típusúra. |
| char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket char16_t típusúra. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket [DateTime](../../system/datetime/)-ra. |
| [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket [Decimal](../../system/decimal/)-ra. |
| **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket double típusúra. |
| **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **int16_t** típusúra. |
| **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **int32_t** típusúra. |
| **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **int64_t** típusúra. |
| **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **int8_t** típusúra. |
| **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket float típusúra. |
| [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket [String](../../system/string/)-ra. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringé alakítását. |
| **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **uint16_t** típusúra. |
| **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **uint32_t** típusúra. |
| **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Átalakít egy értéket **uint64_t** típusúra. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IFormatterConverter](../iformatterconverter/)
* Névtere [System::Runtime::Serialization](../)
* Könyvtár [Aspose.Slides](../../)