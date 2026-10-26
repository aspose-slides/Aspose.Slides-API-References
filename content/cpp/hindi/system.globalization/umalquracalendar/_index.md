---
title: UmAlQuraCalendar
second_title: Aspose.Slides for C++ API संदर्भ
description: "Um Al Qura कैलेंडर। लागू नहीं किया गया है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित करना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी बनाएं नहीं, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फॉल्ट्स का कारण बन सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन्स में आर्गुमेंट के रूप में पास करें।"
type: docs
weight: 391
url: /hi/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar क्लास

Um Al Qura calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
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
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | समय बिंदु में सप्ताह जोड़ता है। |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | समय बिंदु में वर्ष जोड़ता है। |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI जानकारी। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की एक प्रति बनाता है और उसे साझा पॉइंटर के रूप में लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | एल्गोरिद्म प्रकार प्राप्त करता है। |
| int [get_CurrentEra](../calendar/get_currentera/)() const | वर्तमान युग का सूचकांक प्राप्त करता है। |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | वर्तमान युग का मान प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | कैलेंडर में मौजूद युगों की सूची प्राप्त करता है। |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | जाँचता है कि कैलेंडर केवल-पढ़ने योग्य है या नहीं। |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित अधिकतम समय बिंदु। |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित न्यूनतम समय बिंदु। |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2-अंकों से प्रस्तुत किए जा सकने वाले अंतिम वर्ष को प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए महीने का दिन प्राप्त करता है। |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए सप्ताह का दिन प्राप्त करता है। |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का दिन प्राप्त करता है। |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए युग प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए घंटे प्राप्त करता है। |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | निर्दिष्ट वर्ष के लिए लीप माह प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI जानकारी। |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI जानकारी। |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिलीसेकंड प्राप्त करता है। |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिनट प्राप्त करता है। |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए माह प्राप्त करता है। |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए सेकंड प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का सप्ताह प्राप्त करता है। |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | जाँचता है कि माह लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | जाँचता है कि माह लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | जाँचता है कि माह लीप है या नहीं। |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | वर्ष, माह, दिन और युग मानों की जाँच करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटर ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनि‍ंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | कैलेंडर का केवल-पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | 2-अंकों से प्रस्तुत किए जा सकने वाले अंतिम वर्ष को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर नहीं) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | TwoDigitYearMax प्रॉपर्टी का उपयोग करके वर्ष को 4-अंकीय वर्ष में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
|  [UmAlQuraCalendar](./umalquracalendar/)() | कंस्ट्रक्टर। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटर ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | वर्तमान UmAlQura युग। |

## देखें

* क्लास [Calendar](../calendar/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)