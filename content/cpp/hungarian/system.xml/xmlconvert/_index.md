---
title: XmlConvert
second_title: Aspose.Slides for C++ API-referencia
description: Kódolja és dekódolja az XML-neveket, és módszereket biztosít a futásidejű típusok és az XML Schema definíciós nyelv (XSD) típusok közötti konvertáláshoz. Az adattípusok konvertálásakor a visszaadott értékek helyfüggetlenek.
type: docs
weight: 157
url: /hu/system.xml/xmlconvert/
---
## XmlConvert osztály

Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Dekódolja a nevet. Ez a metódus a XmlConvert::EncodeName(String) és a XmlConvert::EncodeLocalName(String) metódusok ellentéte. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Átalakítja a nevet egy érvényes XML helyi névvé. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Átalakítja a nevet egy érvényes XML névvé. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Ellenőrzi, hogy a név érvényes-e az XML specifikáció szerint. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is, de ezt a C#-stílusú lebegőpontos összehasonlítást úgy emulálja, hogy a két NaN egyenlőnek tekinthető. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is, de ezt a C#-stílusú lebegőpontos összehasonlítást úgy emulálja, hogy a két NaN egyenlőnek tekinthető. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi a saját objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum példány-e a targetType által leírt típusnak. A C# 'is' operátor analógja. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Ellenőrzi, hogy a megadott karakter érvényes nem-kettőspont karakter típus-e. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Visszaadja a megadott karakter példányt, ha a argumentumban szereplő karakter érvényes publikus azonosító karakter, ellenkező esetben **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Ellenőrzi, hogy a megadott karakter érvényes Kezdő Név Karakter típus-e. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Ellenőrzi, hogy a megadott karakter érvényes XML szóköz karakter-e. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Ellenőrzi, hogy a megadott karakter érvényes XML karakter-e. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Ellenőrzi, hogy a megadott helyettesítő páros karakterek érvényes XML karakterek-e. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi a saját típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi a másoló konstrukciót az alosztályokban. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi a másoló konstrukciót az alosztályokban. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Átalakítja a [String](../../system/string/)-t egy [Boolean](../../system/boolean/) megfelelőjévé. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Byte](../../system/byte/) megfelelőjévé. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Char](../../system/char/) megfelelőjévé. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [DateTime](../../system/datetime/) megfelelőjévé. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [DateTime](../../system/datetime/) megfelelőjévé. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Átalakítja a [String](../../system/string/)-t egy [DateTime](../../system/datetime/) megfelelőjévé. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Átalakítja a [String](../../system/string/)-t egy [DateTime](../../system/datetime/)-ra a megadott XmlDateTimeSerializationMode használatával. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Átalakítja a megadott [String](../../system/string/)-t egy [DateTimeOffset](../../system/datetimeoffset/) megfelelőjévé. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Átalakítja a megadott [String](../../system/string/)-t egy [DateTimeOffset](../../system/datetimeoffset/) megfelelőjévé. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Átalakítja a megadott [String](../../system/string/)-t egy [DateTimeOffset](../../system/datetimeoffset/) megfelelőjévé. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Decimal](../../system/decimal/) megfelelőjévé. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Átalakítja a [String](../../system/string/)-t egy [Double](../../system/double/) megfelelőjévé. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Guid](../../system/guid/) megfelelőjévé. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Int16](../../system/int16/) megfelelőjévé. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Int32](../../system/int32/) megfelelőjévé. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [Int64](../../system/int64/) megfelelőjévé. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [SByte](../../system/sbyte/) megfelelőjévé. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Átalakítja a [String](../../system/string/)-t egy [Single](../../system/single/) megfelelőjévé. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Átalakítja a [Boolean](../../system/boolean/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Átalakítja a [Char](../../system/char/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Átalakítja a [Decimal](../../system/decimal/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Átalakítja a [SByte](../../system/sbyte/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Átalakítja a [Int16](../../system/int16/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Átalakítja a [Int32](../../system/int32/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Átalakítja a [Int64](../../system/int64/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Átalakítja a [Byte](../../system/byte/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Átalakítja a [UInt16](../../system/uint16/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Átalakítja a [UInt32](../../system/uint32/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Átalakítja a [UInt64](../../system/uint64/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Átalakítja a [Single](../../system/single/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Átalakítja a [Double](../../system/double/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Átalakítja a [TimeSpan](../../system/timespan/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Átalakítja a [DateTime](../../system/datetime/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Átalakítja a [DateTime](../../system/datetime/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Átalakítja a [DateTime](../../system/datetime/)-t egy [String](../../system/string/)-re a megadott XmlDateTimeSerializationMode használatával. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Átalakítja a megadott [DateTimeOffset](../../system/datetimeoffset/)-t egy [String](../../system/string/)-re. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Átalakítja a megadott [DateTimeOffset](../../system/datetimeoffset/)-t egy [String](../../system/string/)-re a megadott formátumban. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Átalakítja a [Guid](../../system/guid/)-t egy [String](../../system/string/)-re. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi a saját objektumok stringgé konvertálását. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [TimeSpan](../../system/timespan/) megfelelőjévé. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [UInt16](../../system/uint16/) megfelelőjévé. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [UInt32](../../system/uint32/) megfelelőjévé. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Átalakítja a [String](../../system/string/)-t egy [UInt64](../../system/uint64/) megfelelőjévé. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Ellenőrzi, hogy a név érvényes-e a W3C Extended Markup Language ajánlás szerint. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Ellenőrzi, hogy a név érvényes **NCName**-e a W3C Extended Markup Language ajánlás szerint. Az **NCName** olyan név, amely nem tartalmazhat kettőspontot. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Ellenőrzi, hogy a karakterlánc érvényes NMTOKEN-e a W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes ajánlás szerint. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Visszaadja a megadott karakterlánc példányt, ha a karakterlánc összes karaktere érvényes publikus azonosító karakter. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Ellenőrzi, hogy a karakterlánc érvényes token-e a W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes ajánlás szerint. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Visszaadja a megadott karakterlánc példányt, ha a karakterlánc összes karaktere érvényes szóköz karakter. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Visszaadja a megadott karakterláncot, ha a karakterek és a helyettesítő páros karakterek érvényes XML karakterek, egyébként XmlException dobódik az első hibás karakter információjával. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy álnév a megosztott mutatóhoz, amely ennek az osztálynak egy példányára mutat. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)