---
title: KoreanCalendar
second_title: "Aspose.Slides के लिए C++ API संदर्भ"
description: "कोरियन कैलेंडर। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन दोषों का कारण बन सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 222
url: /hi/system.globalization/koreancalendar/
---
## KoreanCalendar क्लास

कोरियन कैलेंडर। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन त्रुटियों का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों को तर्क के रूप में पास करें।

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## Methods

| विधि | विवरण |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | समय बिंदु में दिन जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | समय बिंदु में घंटे जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | समय बिंदु में मिलीसेकंड जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | समय बिंदु में मिनट जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | समय बिंदु में महीने जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | समय बिंदु में सेकंड जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | समय बिंदु में हफ्ते जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | समय बिंदु में वर्ष जोड़ता है। |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI जानकारी। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की प्रति बनाता है और उसका साझा पॉइंटर लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिंटैक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की C# शैली में तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | एल्गोरिदम प्रकार प्राप्त करता है। |
| int [get_CurrentEra](../calendar/get_currentera/)() const | वर्तमान युग का सूचकांक प्राप्त करता है। |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | वर्तमान युग का मान प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | कैलेंडर में मौजूद युगों की सूचि प्राप्त करता है। |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | जाँचता है कि कैलेंडर केवल-पढ़ने योग्य है या नहीं। |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित अधिकतम समय बिंदु। |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित न्यूनतम समय बिंदु। |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2-अंकीय द्वारा प्रतिनिधित्व किया जा सकने वाला अंतिम वर्ष प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट के साथ जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए महीने का दिन प्राप्त करता है। |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए सप्ताह का दिन प्राप्त करता है। |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए वर्ष का दिन प्राप्त करता है। |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए युग प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए घंटे प्राप्त करता है। |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | निर्दिष्ट वर्ष के लिए लीप महीने को प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | निर्दिष्ट वर्ष के लिए लीप महीने को प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | निर्दिष्ट वर्ष के लिए लीप महीने को प्राप्त करता है। |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिलीसेकंड प्राप्त करता है। |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिनट प्राप्त करता है। |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए महीना प्राप्त करता है। |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI जानकारी। |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI जानकारी। |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए सेकंड प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का सप्ताह प्राप्त करता है। |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए वर्ष प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | जाँचता है कि महीना लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | जाँचता है कि महीना लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | जाँचता है कि महीना लीप है या नहीं। |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | वर्ष, माह, दिन और युग मानों की जाँच करता है। |
|  [KoreanCalendar](./koreancalendar/)() | निर्माता। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | कैलेंडर का केवल पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2-अंकीय द्वारा प्रतिनिधित्व किया जा सकने वाला अंतिम वर्ष सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट तर्क को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | वर्ष को TwoDigitYearMax प्रॉपर्टी का उपयोग करके 4-अंकीय वर्ष में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## Fields

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | वर्तमान कोरियन युग। |

## See Also

* Class [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)