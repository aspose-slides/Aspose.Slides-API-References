---
title: TimeZoneInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "किसी विशिष्ट समय क्षेत्र का विवरण देने वाली जानकारी का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 1340
url: /hi/system/timezoneinfo/
---
## TimeZoneInfo वर्ग

किसी विशिष्ट समय क्षेत्र का वर्णन करने वाली जानकारी का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार की उदाहरण को स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन त्रुटियों का कारण बन सकता है। हमेशा इस वर्ग को [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | कैश्ड समय क्षेत्र डेटा को साफ़ करे। |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) समय को एक समय क्षेत्र से दूसरे में परिवर्तित करता है। |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | UTC समय को निर्दिष्ट समय क्षेत्र में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | समय को UTC समय में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | समय को UTC समय में बदलता है। |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | समय को UTC समय में बदलता है। आंतरिक उपयोग के लिए। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | एक कस्टम समय क्षेत्र बनाता है। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | एक कस्टम समय क्षेत्र बनाता है। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | एक कस्टम समय क्षेत्र बनाता है। |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | निर्धारित करता है कि वर्तमान और निर्दिष्ट वस्तु समान हैं या नहीं। |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सिमैंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | निर्दिष्ट पहचानकर्ता वाला समय क्षेत्र प्राप्त करता है। |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | [TimeSpan](../timespan/) का एक उदाहरण लौटाता है जो वर्तमान समय क्षेत्र के मानक समय और UTC समय के बीच अंतराल दर्शाता है। |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | वर्तमान समय क्षेत्र के डेलाइट सेविंग टाइम के नाम को प्राप्त करता है। |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | वर्तमान समय क्षेत्र का नाम प्राप्त करता है। |
| [String](../string/) [get_Id](./get_id/)() const | वर्तमान वस्तु द्वारा प्रदर्शित समय क्षेत्र की पहचानकर्ता लौटाता है। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | [TimeZoneInfo](./) का एक उदाहरण लौटाता है जो स्थानीय समय क्षेत्र का प्रतिनिधित्व करता है। |
| [String](../string/) [get_StandardName](./get_standardname/)() const | वर्तमान समय क्षेत्र के मानक समय का नाम प्राप्त करता है। |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | समय क्षेत्र में डेलाइट सेविंग टाइम नियम हैं या नहीं, यह संकेतक प्राप्त करता है। |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | [TimeZoneInfo](./) का एक उदाहरण लौटाता है जो UTC समय क्षेत्र का प्रतिनिधित्व करता है। |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | एक एरे लौटाता है जिसमें **AdjustmentRule** वस्तुएँ होती हैं जो वर्तमान [TimeZoneInfo](./) वस्तु पर लागू समायोजन नियमों का प्रतिनिधित्व करती हैं। |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | निर्दिष्ट तिथि और समय को मैप किए जा सकने वाले UTC तिथियों और समयों को प्राप्त करता है। |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | निर्दिष्ट तिथि और समय को मैप किए जा सकने वाले UTC तिथियों और समयों को प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानार्थी। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | स्थानीय सिस्टम पर उपलब्ध सभी समय क्षेत्रों का सॉर्टेड संग्रह प्राप्त करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानार्थी। |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | निर्दिष्ट तिथि और समय के लिए इस समय क्षेत्र और UTC समय क्षेत्र के बीच अंतर की गणना करता है। |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | निर्दिष्ट तिथि और समय के लिए इस समय क्षेत्र और UTC समय क्षेत्र के बीच अंतर की गणना करता है। |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | एक आंतरिक सहायक फ़ंक्शन जो निर्दिष्ट समय क्षेत्र में UTC-तारीख-समय के लिए UTC ऑफ़सेट लौटाता है। आंतरिक उपयोग के लिए। |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | एक आंतरिक सहायक फ़ंक्शन जो निर्दिष्ट समय क्षेत्र में UTC-तारीख-समय के लिए UTC ऑफ़सेट लौटाता है। आंतरिक उपयोग के लिए। |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | निर्दिष्ट तिथि और समय के लिए इस समय क्षेत्र और UTC समय क्षेत्र के बीच अंतर की गणना करता है। आंतरिक उपयोग के लिए। |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | जांचता है कि वर्तमान और अन्य समय क्षेत्रों में समान समायोजन नियम हैं या नहीं। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जांचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | जांचता है कि निर्दिष्ट तिथि और समय अस्पष्ट है और कई UTC समयों में मैप हो सकता है। |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | जांचता है कि निर्दिष्ट तिथि और समय अस्पष्ट है और कई UTC समयों में मैप हो सकता है। |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | जांचता है कि निर्दिष्ट तिथि और समय डेलाइट सेविंग टाइम की सीमा में आती है या नहीं। |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | जांचता है कि निर्दिष्ट तिथि और समय डेलाइट सेविंग टाइम की सीमा में आती है या नहीं। |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | जांचता है कि निर्दिष्ट तिथि और समय डेलाइट सेविंग टाइम की सीमा में आती है या नहीं। |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | जांचता है कि निर्दिष्ट तिथि और समय अवैध है या नहीं। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा मान प्रकार की वस्तु की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../object/tostring/) मेथड का समानार्थी। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | एक सहायक फ़ंक्शन जो वर्ष और **TransitionTime** को [DateTime](../datetime/) में परिवर्तित करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) निर्माण को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | एक shared pointer के लिए उपनाम है जो **AdjustmentRule** वर्ग के एक उदाहरण को दर्शाता है। |

## देखें

* क्लास [IEquatable](../iequatable/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)