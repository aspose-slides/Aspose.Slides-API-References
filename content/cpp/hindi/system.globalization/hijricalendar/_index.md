---
title: HijriCalendar
second_title: Aspose.Slides for C++ API संदर्भ
description: "हिज़्री कैलेंडर। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियों और/या असर्शन त्रुटियों का सामना करना पड़ सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 157
url: /hi/system.globalization/hijricalendar/
---
## HijriCalendar क्लास

हिज़्री कैलेंडर। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या Assertion त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शनों को तर्क के रूप में पास करने के लिए उपयोग करें।

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## विधियाँ

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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान वस्तु की एक कॉपी बनाता है और उसके लिए एक shared pointer लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | एल्गोरिद्म प्रकार प्राप्त करता है। |
| int [get_CurrentEra](../calendar/get_currentera/)() const | वर्तमान युग का सूचकांक प्राप्त करता है। |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | वर्तमान युग का मान प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | कैलेंडर में मौजूद युगों की सूची प्राप्त करता है। |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | हिज़्री समायोजन प्राप्त करता है। |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | जाँचता है कि कैलेंडर केवल-पढ़ने योग्य है या नहीं। |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित अधिकतम समय बिंदु। |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित न्यूनतम समय बिंदु। |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2-अंकीय द्वारा प्रतिनिधित्व किया जा सकने वाला अंतिम वर्ष प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ा रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए महीने का दिन प्राप्त करता है। |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए सप्ताह का दिन प्राप्त करता है। |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का दिन प्राप्त करता है। |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए युग प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए घंटे प्राप्त करता है। |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | निर्दिष्ट वर्ष के लिए लीप महीने को प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI जानकारी। |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI जानकारी। |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिलीसेकंड प्राप्त करता है। |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिनट प्राप्त करता है। |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए महीना प्राप्त करता है। |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए सेकंड प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का सप्ताह प्राप्त करता है। |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष प्राप्त करता है। |
|  [HijriCalendar](./hijricalendar/)() | निर्माता। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | जाँचता है कि महीना लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | जाँचता है कि महीना लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | जाँचता है कि महीना लीप है या नहीं। |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | वर्ष, महीने, दिन और युग मानों की जाँच करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी अंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | कैलेंडर का केवल-पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से shared रेफ़रेंस काउंटर घटाता है। |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | हिज़्री समायोजन सेट करता है। |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2-अंकीय द्वारा प्रतिनिधित्व किया जा सकने वाला अंतिम वर्ष सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | shared रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | shared रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | shared रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax प्रॉपर्टी का उपयोग करके वर्ष को 4-अंकीय वर्ष में बदलता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी अंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | वर्तमान हिज़्री युग। |

## संबंधित देखें

* क्लास [Calendar](../calendar/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)