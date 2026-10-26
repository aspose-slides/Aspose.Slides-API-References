---
title: XmlConvert
second_title: Aspose.Slides för C++ API-referens
description: Kodar och avkodar XML-namn samt tillhandahåller metoder för att konvertera mellan runtime-typer och XML-schema definitionsspråk (XSD)-typer. Vid konvertering av datatyper är de returnerade värdena språkoberoende.
type: docs
weight: 157
url: /sv/system.xml/xmlconvert/
---
## XmlConvert klass

Kodar och avkodar XML-namn, och tillhandahåller metoder för att konvertera mellan runtime-typer och XML [Schema](../../system.xml.schema/) definitionsspråk (XSD) typer. Vid konvertering av datatyper är de returnerade värdena språkoberoende.

```cpp
class XmlConvert : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Avkodar ett namn. Denna metod utför det omvända av metoderna XmlConvert::EncodeName(String) och XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Konverterar namnet till ett giltigt XML lokalt namn. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Konverterar namnet till ett giltigt XML-namn. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Verifierar att namnet är giltigt enligt XML-specifikationen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknare-datstrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Kontrollerar om det inmatade tecknet är en giltig icke-kolon-teckentyp. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Returnerar den inmatade teckeninstansen om tecknet i argumentet är ett giltigt public-id-tecken, annars **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Kontrollerar om det inmatade tecknet är en giltig Start-Name-Character-typ. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Kontrollerar om det inmatade tecknet är ett giltigt XML-mellanslagstecken. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Kontrollerar om det inmatade tecknet är ett giltigt XML-tecken. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Kontrollerar om det inmatade surrogatparet av tecken är ett giltigt XML-tecken. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) sentinel-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te templatargument till en svag pekare (istället för en delad). Tillåter att byta pekare i samlingar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementerar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Konverterar [String](../../system/string/) till en motsvarande [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konverterar [String](../../system/string/) till en motsvarande [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konverterar [String](../../system/string/) till en [DateTime](../../system/datetime/) med den specificerade XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Konverterar den angivna [String](../../system/string/) till en motsvarande [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konverterar den angivna [String](../../system/string/) till en motsvarande [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konverterar den angivna [String](../../system/string/) till en motsvarande [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Konverterar [String](../../system/string/) till en motsvarande [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Konverterar [String](../../system/string/) till en motsvarande [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Konverterar [Boolean](../../system/boolean/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Konverterar [Char](../../system/char/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Konverterar [Decimal](../../system/decimal/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Konverterar [SByte](../../system/sbyte/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Konverterar [Int16](../../system/int16/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Konverterar [Int32](../../system/int32/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Konverterar [Int64](../../system/int64/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Konverterar [Byte](../../system/byte/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Konverterar [UInt16](../../system/uint16/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Konverterar [UInt32](../../system/uint32/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Konverterar [UInt64](../../system/uint64/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Konverterar [Single](../../system/single/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Konverterar [Double](../../system/double/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Konverterar [TimeSpan](../../system/timespan/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konverterar [DateTime](../../system/datetime/) till en [String](../../system/string/) med den specificerade XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Konverterar den angivna [DateTimeOffset](../../system/datetimeoffset/) till en [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Konverterar den angivna [DateTimeOffset](../../system/datetimeoffset/) till en [String](../../system/string/) i det specificerade formatet. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Konverterar [Guid](../../system/guid/) till en [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Konverterar [String](../../system/string/) till en motsvarande [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) sentinel-objekt. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Verifierar att namnet är ett giltigt namn enligt W3C:s rekommendation för Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Verifierar att namnet är en giltig **NCName** enligt W3C:s rekommendation för Extended Markup Language. En **NCName** är ett namn som inte kan innehålla ett kolon. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Verifierar att strängen är en giltig NMTOKEN enligt W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-rekommendationen. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Returnerar den inmatade stränginstansen om alla tecken i strängargumentet är giltiga public-id-tecken. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Verifierar att strängen är ett giltigt token enligt W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes-rekommendationen. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Returnerar den inmatade stränginstansen om alla tecken i strängargumentet är giltiga mellanslagstecken. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Returnerar den inmatade strängen om alla tecken och surrogatpar i strängargumentet är giltiga XML-tecken, annars kastas ett XmlException med information om det första ogiltiga tecknet som påträffas. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementerar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementerar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | En alias för delad pekare till en instans av denna klass. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)