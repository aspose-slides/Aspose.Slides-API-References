---
title: XmlConvert
second_title: Aspose.Slides for C++ API संदर्भ
description: XML नामों को एन्कोड और डिकोड करता है, और रनटाइम प्रकारों तथा XML स्कीमा परिभाषा भाषा (XSD) प्रकारों के बीच रूपांतरण के लिए विधियों को प्रदान करता है। डेटा प्रकारों को बदलते समय, लौटाए गए मान स्थानीय-निर्भर नहीं होते।
type: docs
weight: 157
url: /hi/system.xml/xmlconvert/
---
## XmlConvert क्लास

XML नामों को एन्कोड और डिकोड करता है, और रनटाइम प्रकारों और XML [Schema](../../system.xml.schema/) परिभाषा भाषा (XSD) प्रकारों के बीच परिवर्तन के लिए विधियाँ प्रदान करता है। डेटा प्रकारों को बदलते समय, लौटाए गए मान स्थानीय-निर्भर नहीं होते।

```cpp
class XmlConvert : public System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | नाम को डिकोड करता है। यह मेथड XmlConvert::EncodeName(String) और XmlConvert::EncodeLocalName(String) विधियों के विपरीत कार्य करता है। |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | नाम को वैध XML स्थानीय नाम में बदलता है। |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | नाम को वैध XML नाम में बदलता है। |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | नाम को XML विशिष्टीकरण के अनुसार वैध है या नहीं, सत्यापित करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफरेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान। |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | जाँचता है कि दिया गया अक्षर वैध गैर-कोलन अक्षर प्रकार है या नहीं। |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | यदि तर्क में दिया गया अक्षर वैध सार्वजनिक id अक्षर है तो वह अक्षर इंस्टेंस लौटाता है, अन्यथा **nullptr** देता है। |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | जाँचता है कि दिया गया अक्षर वैध स्टार्ट नेम कैरेक्टर प्रकार है या नहीं। |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | जाँचता है कि दिया गया अक्षर वैध XML व्हाइटस्पेस कैरेक्टर है या नहीं। |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | जाँचता है कि दिया गया अक्षर वैध XML कैरेक्टर है या नहीं। |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | जाँचता है कि दिया गया सरोगेट कैरेक्टर जोड़ी वैध XML कैरेक्टर है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफरेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफरेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफरेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | [String](../../system/string/) को [Boolean](../../system/boolean/) समतुल्य में बदलता है। |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Byte](../../system/byte/) समतुल्य में बदलता है। |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Char](../../system/char/) समतुल्य में बदलता है। |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [DateTime](../../system/datetime/) समतुल्य में बदलता है। |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/) को [DateTime](../../system/datetime/) समतुल्य में बदलता है। |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/) को [DateTime](../../system/datetime/) समतुल्य में बदलता है। |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [String](../../system/string/) को निर्दिष्ट XmlDateTimeSerializationMode का उपयोग करके [DateTime](../../system/datetime/) में बदलता है। |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | प्रदान किए गए [String](../../system/string/) को [DateTimeOffset](../../system/datetimeoffset/) समतुल्य में बदलता है। |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | प्रदान किए गए [String](../../system/string/) को [DateTimeOffset](../../system/datetimeoffset/) समतुल्य में बदलता है। |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | प्रदान किए गए [String](../../system/string/) को [DateTimeOffset](../../system/datetimeoffset/) समतुल्य में बदलता है। |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Decimal](../../system/decimal/) समतुल्य में बदलता है। |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | [String](../../system/string/) को [Double](../../system/double/) समतुल्य में बदलता है। |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Guid](../../system/guid/) समतुल्य में बदलता है। |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Int16](../../system/int16/) समतुल्य में बदलता है। |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Int32](../../system/int32/) समतुल्य में बदलता है। |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [Int64](../../system/int64/) समतुल्य में बदलता है। |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [SByte](../../system/sbyte/) समतुल्य में बदलता है। |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | [String](../../system/string/) को [Single](../../system/single/) समतुल्य में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | [Boolean](../../system/boolean/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | [Char](../../system/char/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | [SByte](../../system/sbyte/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | [Int16](../../system/int16/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | [Int32](../../system/int32/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | [Int64](../../system/int64/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | [Byte](../../system/byte/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | [UInt16](../../system/uint16/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | [UInt32](../../system/uint32/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | [UInt64](../../system/uint64/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | [Single](../../system/single/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | [Double](../../system/double/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | [TimeSpan](../../system/timespan/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | [DateTime](../../system/datetime/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [DateTime](../../system/datetime/) को निर्दिष्ट XmlDateTimeSerializationMode का उपयोग करके [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | प्रदान किए गए [DateTimeOffset](../../system/datetimeoffset/) को [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | प्रदान किए गए [DateTimeOffset](../../system/datetimeoffset/) को निर्दिष्ट प्रारूप में [String](../../system/string/) में बदलता है। |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | [Guid](../../system/guid/) को [String](../../system/string/) में बदलता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [TimeSpan](../../system/timespan/) समतुल्य में बदलता है। |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [UInt16](../../system/uint16/) समतुल्य में बदलता है। |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [UInt32](../../system/uint32/) समतुल्य में बदलता है। |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) को [UInt64](../../system/uint64/) समतुल्य में बदलता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | W3C Extended Markup Language सिफारिश के अनुसार नाम वैध है या नहीं, सत्यापित करता है। |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | W3C Extended Markup Language सिफारिश के अनुसार नाम वैध **NCName** है या नहीं, सत्यापित करता है। **NCName** वह नाम है जिसमें कोलन नहीं हो सकता। |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes सिफारिश के अनुसार स्ट्रिंग वैध NMTOKEN है या नहीं, सत्यापित करता है। |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | यदि स्ट्रिंग तर्क के सभी अक्षर वैध सार्वजनिक id अक्षर हैं तो पास किया गया स्ट्रिंग इंस्टेंस लौटाता है। |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes सिफारिश के अनुसार स्ट्रिंग वैध टोकन है या नहीं, सत्यापित करता है। |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | यदि स्ट्रिंग तर्क के सभी अक्षर वैध व्हाइटस्पेस हैं तो पास किया गया स्ट्रिंग इंस्टेंस लौटाता है। |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | यदि स्ट्रिंग तर्क के सभी अक्षर और सरोगेट पेयर अक्षर वैध XML अक्षर हैं तो पास किया गया स्ट्रिंग लौटाता है, अन्यथा पहला अवैध अक्षर मिलने पर जानकारी सहित XmlException फेंका जाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)