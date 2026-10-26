---
title: TaiwanLunisolarCalendar
second_title: Aspose.Slides for C++ API संदर्भ
description: "Taiwan lunisolar calendar. लागू नहीं किया गया है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टांस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असेर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 339
url: /hi/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar क्लास

Taiwan lunisolar calendar. Not implemented. Objects of this क्लास should only be allocated using [System::MakeObject()](../../system/makeobject/) फ़ंक्शन. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this क्लास into [System::SmartPtr](../../system/smartptr/) पॉइंटर and use this pointer to pass it to फ़ंक्शन्स as argument.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## मेथड्स

| मेथड | विवरण |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की एक कॉपी बनाता है और उसे एक साझा पॉइंटर के रूप में लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI जानकारी। |
| int [get_CurrentEra](../calendar/get_currentera/)() const | वर्तमान युग का इंडेक्स प्राप्त करता है। |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | वर्तमान युग का मान प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | कैलेंडर में मौजूद युगों की सूची प्राप्त करता है। |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | जांचता है कि कैलेंडर केवल-पढ़ने योग्य है या नहीं। |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित अधिकतम समय बिंदु। |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | कैलेंडर द्वारा समर्थित न्यूनतम समय बिंदु। |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 2-अंकीय से प्रतिनिधित्व योग्य अंतिम वर्ष प्राप्त करता है। |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | आकाशीय तना प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए माह का दिन प्राप्त करता है। |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए सप्ताह का दिन प्राप्त करता है। |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का दिन प्राप्त करता है। |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | विशिष्ट महीने में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | विशिष्ट वर्ष में दिनों की संख्या प्राप्त करता है। |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | निर्दिष्ट समय बिंदु के लिए युग प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए घंटे प्राप्त करता है। |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | निर्दिष्ट वर्ष के लिए अनुषंगिक (लीप) माह प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | निर्दिष्ट वर्ष के लिए अनुषंगिक (लीप) माह प्राप्त करता है। |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | निर्दिष्ट वर्ष के लिए अनुषंगिक (लीप) माह प्राप्त करता है। |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिलीसेकंड प्राप्त करता है। |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए मिनट प्राप्त करता है। |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए माह प्राप्त करता है। |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | निर्दिष्ट वर्ष में महीनों की संख्या प्राप्त करता है। |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI जानकारी। |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI जानकारी। |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए सेकंड प्राप्त करता है। |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | षड्युग चक्र में वर्ष प्राप्त करता है। |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | भौगोलिक शाखा प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष का सप्ताह प्राप्त करता है। |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | निर्दिष्ट समय बिंदु के लिए वर्ष प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | जाँचता है कि दिन लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | जाँचता है कि माह लीप है या नहीं। |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | जाँचता है कि माह लीप है या नहीं। |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | जाँचता है कि वर्ष लीप है या नहीं। |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | वर्ष, माह, दिन और युग के मानों की जाँच करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | कैलेंडर का केवल-पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू प्रकार के ऑब्जेक्ट को nullptr के साथ करती है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 2-अंकीय से प्रतिनिधित्व योग्य अंतिम वर्ष को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'th' टेम्प्लेट आर्गुमेंट को एक वैक पॉइंटर (शेयर्ड की बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वैक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | कन्स्ट्रक्टर। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) ऑब्जेक्ट को घटकों से बनाता है। |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | वर्ष को TwoDigitYearMax प्रॉपर्टी का उपयोग करके 4-अंकीय वर्ष में परिवर्तित करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* नामस्थान [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)