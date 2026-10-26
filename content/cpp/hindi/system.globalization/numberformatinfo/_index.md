---
title: NumberFormatInfo
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "संख्याओं को स्वरूपित करने के तरीके की जानकारी रखता है। सेट्टर ऑपरेशन्स केवल गैर-रीड-ऑनली वस्तुओं पर सक्षम होते हैं। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new के द्वारा कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां उत्पन्न होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में भेजने के लिए करें।"
type: docs
weight: 248
url: /hi/system.globalization/numberformatinfo/
---
## NumberFormatInfo क्लास

संख्याओं को फॉर्मेट करने के तरीके के बारे में जानकारी रखता है। सेट्टर ऑपरेशन्स केवल गैर-केवल-पढ़ने योग्य ऑब्जेक्ट्स पर सक्षम होते हैं। इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फ़ॉल्ट्स का कारण बन सकता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें।

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | फ़ॉर्मेट जानकारी की क्लोन बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना को एमीलेट करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना को एमीलेट करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | मुद्रा दशमलव अंकों की संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | मुद्रा दशमलव विभाजक प्राप्त करता है। |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | मुद्रा समूह विभाजक प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | प्रति समूह मुद्रा दशमलव अंकों की संख्या प्राप्त करता है। |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | मुद्रा नकारात्मक पैटर्न प्राप्त करता है। |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | मुद्रा सकारात्मक पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | मुद्रा प्रतीक प्राप्त करता है। |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | वर्तमान थ्रेड संस्कृति द्वारा निर्धारित नंबर फ़ॉर्मेट जानकारी प्राप्त करता है। |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | एक मान प्राप्त करता है जो दर्शाता है कि अंक का आकार कैसे प्रदर्शित किया जाए। |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | अपरिवर्तनीय संस्कृति द्वारा निर्धारित नंबर फ़ॉर्मेट जानकारी प्राप्त करता है। |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | जाँचता है कि फ़ॉर्मेट केवल-पढ़ने योग्य है या नहीं। |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Not-a-Number प्रतीक प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | अंकों के प्रतीक (0 से 9) प्राप्त करता है। |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | नकारात्मक अनंत प्रतीक प्राप्त करता है। |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | नकारात्मक चिह्न प्राप्त करता है। |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | दशमलव अंकों की संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | दशमलव विभाजक प्राप्त करता है। |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | संख्या समूह विभाजक प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | प्रति समूह अंकों की संख्या प्राप्त करता है। |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | संख्या नकारात्मक पैटर्न प्राप्त करता है। |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | प्रतिशत मानों में दशमलव स्थानों की संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | प्रतिशत मानों में दशमलव विभाजक प्राप्त करता है। |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | प्रतिशत मानों में समूह विभाजक प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | प्रति प्रतिशत मान समूह में अंकों की संख्या प्राप्त करता है। |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | प्रतिशत नकारात्मक पैटर्न प्राप्त करता है। |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | प्रतिशत सकारात्मक पैटर्न प्राप्त करता है। |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | प्रतिशत प्रतीक प्राप्त करता है। |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | परमीले प्रतीक प्राप्त करता है। |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | सकारात्मक अनंत प्रतीक प्राप्त करता है। |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | सकारात्मक चिह्न प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | विशिष्ट प्रकार का फ़ॉर्मेटर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | फ़ॉर्मेट प्रोवाइडर से जुड़ा फ़ॉर्मेटर प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का उदाहरण है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [NumberFormatInfo](./numberformatinfo/)() | डिफ़ॉल्ट कंस्ट्रक्टर (अपरिवर्तनीय [NumberFormatInfo](./))। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | फ़ॉर्मेटर का केवल-पढ़ने योग्य संस्करण प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषता। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स केस के लिए विशेषता। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | मुद्रा दशमलव अंकों की संख्या सेट करता है। |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | मुद्रा दशमलव विभाजक सेट करता है। |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | मुद्रा समूह विभाजक सेट करता है। |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | प्रति समूह मुद्रा दशमलव अंकों की संख्या सेट करता है। |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | मुद्रा नकारात्मक पैटर्न सेट करता है। |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | मुद्रा सकारात्मक पैटर्न सेट करता है। |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | मुद्रा प्रतीक सेट करता है। |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | एक मान सेट करता है जो निर्दिष्ट करता है कि अंक का आकार कैसे प्रदर्शित किया जाए। |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Not-a-Number प्रतीक सेट करता है। |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | अंकों के प्रतीक (0 से 9) सेट करता है। |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | नकारात्मक अनंत प्रतीक सेट करता है। |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | नकारात्मक चिह्न सेट करता है। |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | दशमलव अंकों की संख्या सेट करता है। |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | दशमलव विभाजक सेट करता है। |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | संख्या समूह विभाजक सेट करता है। |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | प्रति समूह अंकों की संख्या सेट करता है। |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | संख्या नकारात्मक पैटर्न सेट करता है। |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | प्रतिशत मानों में दशमलव स्थानों की संख्या सेट करता है। |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | प्रतिशत मानों में दशमलव विभाजक सेट करता है। |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | प्रतिशत मानों में समूह विभाजक सेट करता है। |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | प्रति प्रतिशत मान समूह में अंकों की संख्या सेट करता है। |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | प्रतिशत नकारात्मक पैटर्न सेट करता है। |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | प्रतिशत सकारात्मक पैटर्न सेट करता है। |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | प्रतिशत प्रतीक सेट करता है। |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | परमीले प्रतीक सेट करता है। |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | सकारात्मक अनंत प्रतीक सेट करता है। |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | सकारात्मक चिह्न सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को साझा के बजाय कमजोर पॉइंटर सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* क्लास [IFormatProvider](../../system/iformatprovider/)
* क्लास [ICloneable](../../system/icloneable/)
* नेमस्पेस [System::Globalization](../)
* लाइब्रेरी [Aspose.Slides](../../)