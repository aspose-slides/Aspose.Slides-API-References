---
title: CultureInfo
second_title: "Aspose.Slides for C++ API रेफ़रेंस"
description: "संस्कृति-विशिष्ट मानों और एल्गोरिदमों का संग्रह। सेट्टर ऑपरेशन्स केवल गैर-केवल-पढ़ने-योग्य ऑब्जेक्ट्स पर सक्रिय होते हैं। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियों और/या असर्शन दोष उत्पन्न होंगे। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्युमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 53
url: /hi/system.globalization/cultureinfo/
---
## CultureInfo क्लास

Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## मेथड्स

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | कैश किए गए संस्कृति सूचना को रीफ़्रेश करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | संस्कृति सूचना की प्रतिलिपि बनाता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | नाम द्वारा संस्कृति बनाता है। |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI सूचना। |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | कंस्ट्रक्टर। |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | कंस्ट्रक्टर। |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | हमेशा ArgumentNullException फेंकता है। |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | ऑब्जेक्ट्स की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | संस्कृति द्वारा उपयोग किए जाने वाले कैलेंडर को प्राप्त करता है। |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | स्ट्रिंग कंपैरेटर प्राप्त करता है जो संस्कृति नियमों का पालन करता है। |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | वर्तमान संस्कृति का वर्णन करने वाले संस्कृति प्रकारों का बिटवाइज़ संयुक्त प्राप्त करता है। |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | वर्तमान थ्रेड के लिए सेट की गई संस्कृति प्राप्त करता है। |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | वर्तमान थ्रेड की UI संस्कृति प्राप्त करता है। |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | तारीख फ़ॉर्मेट जानकारी प्राप्त करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | वर्तमान एप्लिकेशन डोमेन में डिफ़ॉल्ट संस्कृति प्राप्त करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | वर्तमान एप्लिकेशन डोमेन में डिफ़ॉल्ट UI संस्कृति प्राप्त करता है। |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | संस्कृति का डिस्प्ले नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | संस्कृति का अंग्रेज़ी नाम प्राप्त करता है। |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | भाषा के लिए RFC 4646 नाम प्राप्त करता है। |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | ऑपरेटिंग सिस्टम के साथ स्थापित संस्कृति प्राप्त करता है। |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | इनवेरिएंट संस्कृति प्राप्त करता है। |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | जाँचता है कि संस्कृति तटस्थ है या नहीं। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | जाँचता है कि संस्कृति ऑब्जेक्ट केवल-पढ़ने योग्य है या नहीं। |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | सक्रिय इनपुट लोकेल पहचानकर्ता प्राप्त करता है। |
| virtual int [get_LCID](./get_lcid/)() const | संस्कृति पहचानकर्ता प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | संस्कृति का नाम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | संस्कृति का मूल नाम प्राप्त करता है। |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | संख्या फ़ॉर्मेट जानकारी प्राप्त करता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | संस्कृति के साथ उपयोग की जा सकने वाली कैलेंडरों की सूची। |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | पैरेंट संस्कृति प्राप्त करता है। |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | संस्कृति द्वारा उपयोग किए जाने वाले टेक्स्ट पैरामीटर प्राप्त करता है। |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | तीन-अक्षर ISO 639-2 भाषा कोड प्राप्त करता है। |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | भाषा के लिए तीन-अक्षर कोड प्राप्त करता है जैसा कि [Windows](../../system.windows/) API में परिभाषित है। |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | संस्कृति से जुड़ा दो-अक्षर ISO भाषा नाम प्राप्त करता है। |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | एक फ्लैग प्राप्त करता है जो दर्शाता है कि [CultureInfo](./) उपयोगकर्ता-चयनित संस्कृति सेटिंग्स का उपयोग करता है या नहीं। |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | कंसोल अनुप्रयोगों के लिए उपयुक्त वैकल्पिक संस्कृति प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | नाम द्वारा संस्कृति प्राप्त करता है। CreateSpecificCulture के समान। |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | नाम द्वारा संस्कृति प्राप्त करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | आईडी द्वारा संस्कृति प्राप्त करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | डिप्रिकेटेड। निर्दिष्ट RFC 4646 भाषा टैग द्वारा केवल-पढ़ने योग्य [CultureInfo](./) ऑब्जेक्ट प्राप्त करता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | निर्दिष्ट प्रकारों में आने वाली संस्कृतियाँ प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | विशिष्ट प्रकार के लिए फ़ॉर्मेट ऑब्जेक्ट प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | ऑब्जेक्ट हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **bool** [IsInherited](./isinherited/)() const | इनहेरिटेड फ़्लैग प्राप्त करता है। केवल आंतरिक उपयोग के लिए। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्ट को सक्षम करता है। |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्ट को सक्षम करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | संस्कृति पैरामीटरों की तुलना करता है। |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | संस्कृति का केवल-पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | वर्तमान थ्रेड के लिए संस्कृति सेट करता है। |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | वर्तमान थ्रेड की UI संस्कृति सेट करता है। |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | तारीख फ़ॉर्मेट जानकारी सेट करता है। |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | वर्तमान एप्लिकेशन डोमेन में डिफ़ॉल्ट संस्कृति सेट करता है। |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | वर्तमान एप्लिकेशन डोमेन में डिफ़ॉल्ट UI संस्कृति सेट करता है। |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | संख्या फ़ॉर्मेट जानकारी प्राप्त करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (सह-शेयर नहीं) सेट करता है। कंटेनरों में पॉइंटरों को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और मान लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | संस्कृति को स्ट्रिंग में बदलता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* क्लास [IFormatProvider](../../system/iformatprovider/)
* क्लास [ICloneable](../../system/icloneable/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)