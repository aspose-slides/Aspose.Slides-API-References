---
title: DateTimeFormatInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: "तारीख और समय फ़ॉर्मेटिंग पैरामीटरों का सेट। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शंस को आर्ग्यूमेंट के रूप में पास करने के लिये करें।"
type: docs
weight: 66
url: /hi/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo क्लास

तारीख और समय फ़ॉर्मेटिंग पैरामीटर्स का सेट। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन्स में आर्ग्यूमेंट के रूप में पास करें।

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | फ़ॉर्मेट जानकारी की प्रतिलिपि बनाता है। |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | डिफ़ॉल्ट कंस्ट्रक्टर, अपरिवर्तनीय फ़ॉर्मेट जानकारी बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | संक्षिप्त दिन नाम प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | जेनिटिव रूप में संक्षिप्त महीने के नाम प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | संक्षिप्त महीने के नाम प्राप्त करता है। |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | AM डिज़ाइनएटर प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | फ़ॉर्मेटर से जुड़ी कैलेंडर प्राप्त करता है। |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | फ़ॉर्मेटर से जुड़ा कैलेंडर सप्ताह नियम प्राप्त करता है। |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | वर्तमान थ्रेड का डेट और टाइम फ़ॉर्मेटर प्राप्त करता है। |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | डेट सेपरेटर प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | दिन नाम प्राप्त करता है। |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | सप्ताह का पहला दिन प्राप्त करता है। |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | पूर्ण डेट और टाइम पैटर्न प्राप्त करता है। |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | अपरिवर्तनीय डेट और टाइम फ़ॉर्मेटर प्राप्त करता है। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | जाँचता है कि फ़ॉर्मेटर केवल-पढ़ने योग्य है या नहीं। |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | लॉन्ग डेट पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | लॉन्ग टाइम पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | महीने के दिन का पैटर्न प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | जेनिटिव रूप में महीने के नाम प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | महीने के नाम प्राप्त करता है। |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | यदि उपलब्ध हो तो नेटिव कैलेंडर नाम प्राप्त करता है। |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | PM डिज़ाइनएटर प्राप्त करता है। |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | RFC1123 पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | शॉर्ट डेट पैटर्न प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | संभव सबसे छोटे दिन नाम प्राप्त करता है। |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | शॉर्ट टाइम पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | सॉर्टेबल डेट और टाइम पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | टाइम सेपरेटर प्राप्त करता है। |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | यूनिवर्सल सॉर्टेबल डेट और टाइम पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | वर्ष और महीने का पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | संक्षिप्त सप्ताह दिवस का नाम प्राप्त करता है। |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | संक्षिप्त युग नाम प्राप्त करता है। |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | संक्षिप्त महीने का नाम प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | वह सभी पैटर्न प्राप्त करता है जिनमें डेट और टाइम वैल्यू को फ़ॉर्मेट किया जा सकता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | निर्दिष्ट फ़ॉर्मेट स्ट्रिंग का उपयोग करके डेट और टाइम वैल्यू को फ़ॉर्मेट करने के सभी पैटर्न प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | हफ़्ते के दिन का नाम प्राप्त करता है। |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | नाम द्वारा युग प्राप्त करता है। |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | युग का नाम प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | विशिष्ट प्रकार के फ़ॉर्मेटर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | फ़ॉर्मेट प्रोवाइडर से जुड़े फ़ॉर्मेटर को प्राप्त करता है। |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | लीप-इयर महीने का नाम प्राप्त करता है। |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | जेनिटिव महीने का नाम प्राप्त करता है। |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | महीने का नाम प्राप्त करता है। |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | निर्दिष्ट हफ़्ते के दिन के सबसे छोटे नाम को प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | फ़ॉर्मेटर का रीड-ऑनली संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | नल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नल पॉइंटर के केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | संक्षिप्त दिन नाम सेट करता है। |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | जेनिटिव रूप में संक्षिप्त महीने के नाम सेट करता है। |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | संक्षिप्त महीने के नाम सेट करता है। |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | AM डिज़ाइनएटर सेट करता है। |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | फ़ॉर्मेटर से जुड़ी कैलेंडर सेट करता है। |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | फ़ॉर्मेटर से जुड़ा कैलेंडर सप्ताह नियम सेट करता है। |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | डेट सेपरेटर सेट करता है। |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | दिन नाम सेट करता है। |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | सप्ताह का पहला दिन सेट करता है। |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | पूर्ण डेट और टाइम पैटर्न सेट करता है। |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | लॉन्ग डेट पैटर्न सेट करता है। |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | लॉन्ग टाइम पैटर्न सेट करता है। |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | महीने के दिन का पैटर्न सेट करता है। |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | जेनिटिव रूप में महीने के नाम सेट करता है। |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | महीनें के नाम सेट करता है। |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | PM डिज़ाइनएटर सेट करता है। |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | शॉर्ट डेट पैटर्न सेट करता है। |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | संभव सबसे छोटे दिन नाम सेट करता है। |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | शॉर्ट टाइम पैटर्न सेट करता है। |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | टाइम सेपरेटर सेट करता है। |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | वर्ष और महीने का पैटर्न सेट करता है। |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | निर्दिष्ट फ़ॉर्मेट के लिए पैटर्न सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | एनवें टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (स्लैक्ड शेयर नहीं) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाकर लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* क्लास [IFormatProvider](../../system/iformatprovider/)
* क्लास [ICloneable](../../system/icloneable/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)