---
title: XmlConvert
second_title: Aspose.Slides voor C++ API-referentie
description: Encodeert en decodeert XML-namen, en biedt methoden voor het converteren tussen runtime-typen en XML Schema definitietaal (XSD)-typen. Bij het converteren van gegevenstypen zijn de geretourneerde waarden locale-onafhankelijk.
type: docs
weight: 157
url: /nl/system.xml/xmlconvert/
---
## XmlConvert klasse


Encodeert en decodeert XML-namen, en biedt methoden voor het converteren tussen runtime-typen en XML [Schema](../../system.xml.schema/) definitietaal (XSD)-typen. Bij het converteren van gegevenstypen zijn de geretourneerde waarden locale-onafhankelijk.

```cpp
class XmlConvert : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Decodeert een naam. Deze methode doet het omgekeerde van de XmlConvert::EncodeName(String)- en XmlConvert::EncodeLocalName(String)-methoden. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Converteert de naam naar een geldige XML-localenaam. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Converteert de naam naar een geldige XML-naam. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Verifieert dat de naam geldig is volgens de XML-specificatie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Hiermee kan men hashcodes genereren voor aangepaste objecten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van de C# 'is'-operator. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Controleert of het opgegeven teken een geldig niet-dubbele-punt-teken is. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Retourneert het opgegeven teken als het teken in het argument een geldig public-id-teken is, anders **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Controleert of het opgegeven teken een geldig Start Name Character-type is. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Controleert of het opgegeven teken een geldig XML-witruimte-teken is. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Controleert of het opgegeven teken een geldig XML-teken is. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Controleert of het opgegeven surrogate-tekenpaar een geldig XML-teken is. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Hiermee kan men aangepaste types klonen. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets echt, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-templatesargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kan men pointers in containers naar zwakke modus schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Converteert de [String](../../system/string/) naar een [Boolean](../../system/boolean/)-equivalent. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Byte](../../system/byte/)-equivalent. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Char](../../system/char/)-equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [DateTime](../../system/datetime/)-equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [DateTime](../../system/datetime/)-equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converteert de [String](../../system/string/) naar een [DateTime](../../system/datetime/)-equivalent. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converteert de [String](../../system/string/) naar een [DateTime](../../system/datetime/) met de opgegeven XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Converteert de geleverde [String](../../system/string/) naar een [DateTimeOffset](../../system/datetimeoffset/)-equivalent. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Converteert de geleverde [String](../../system/string/) naar een [DateTimeOffset](../../system/datetimeoffset/)-equivalent. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Converteert de geleverde [String](../../system/string/) naar een [DateTimeOffset](../../system/datetimeoffset/)-equivalent. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Decimal](../../system/decimal/)-equivalent. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Converteert de [String](../../system/string/) naar een [Double](../../system/double/)-equivalent. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Guid](../../system/guid/)-equivalent. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Int16](../../system/int16/)-equivalent. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Int32](../../system/int32/)-equivalent. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [Int64](../../system/int64/)-equivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [SByte](../../system/sbyte/)-equivalent. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Converteert de [String](../../system/string/) naar een [Single](../../system/single/)-equivalent. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Converteert de [Boolean](../../system/boolean/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Converteert de [Char](../../system/char/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Converteert de [Decimal](../../system/decimal/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Converteert de [SByte](../../system/sbyte/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Converteert de [Int16](../../system/int16/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Converteert de [Int32](../../system/int32/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Converteert de [Int64](../../system/int64/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Converteert de [Byte](../../system/byte/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Converteert de [UInt16](../../system/uint16/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Converteert de [UInt32](../../system/uint32/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Converteert de [UInt64](../../system/uint64/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Converteert de [Single](../../system/single/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Converteert de [Double](../../system/double/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Converteert de [TimeSpan](../../system/timespan/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Converteert de [DateTime](../../system/datetime/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Converteert de [DateTime](../../system/datetime/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Converteert de [DateTime](../../system/datetime/) naar een [String](../../system/string/) met de opgegeven XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Converteert de geleverde [DateTimeOffset](../../system/datetimeoffset/) naar een [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Converteert de geleverde [DateTimeOffset](../../system/datetimeoffset/) naar een [String](../../system/string/) in het opgegeven formaat. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Converteert de [Guid](../../system/guid/) naar een [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Hiermee kan men aangepaste objecten naar string converteren. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [TimeSpan](../../system/timespan/)-equivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [UInt16](../../system/uint16/)-equivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [UInt32](../../system/uint32/)-equivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Converteert de [String](../../system/string/) naar een [UInt64](../../system/uint64/)-equivalent. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Verifieert dat de naam een geldige naam is volgens de W3C Extended Markup Language-aanbeveling. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Verifieert dat de naam een geldige **NCName** is volgens de W3C Extended Markup Language-aanbeveling. Een **NCName** is een naam die geen dubbele punt mag bevatten. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Verifieert dat de string een geldig NMTOKEN is volgens de W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-aanbeveling. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Retourneert de opgegeven string-instantie als alle tekens in het string-argument geldige public-id-tekens zijn. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Verifieert dat de string een geldig token is volgens de W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-aanbeveling. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Retourneert de opgegeven string-instantie als alle tekens in het string-argument geldige witruimte-tekens zijn. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Retourneert de opgegeven string als alle tekens en surrogate-tekenparen in het string-argument geldige XML-tekens zijn; anders wordt een XmlException gegooid met informatie over het eerste ongeldige teken dat is aangetroffen. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar een instantie van deze klasse. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)