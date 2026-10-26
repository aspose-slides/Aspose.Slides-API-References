---
title: ConsoleOutput
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "मानक आउटपुट स्ट्रीम का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों को तर्क के रूप में पास करें।"
type: docs
weight: 209
url: /hi/system/consoleoutput/
---
## ConsoleOutput क्लास

मानक आउटपुट स्ट्रीम का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन faults हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों को तर्क के रूप में पास करें।

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | स्ट्रीम को बंद करता है और प्राप्त संसाधनों को रिलीज़ करता है। |
| void [Dispose](../../system.io/textwriter/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../object/equals/) सिमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual void [Flush](../../system.io/textwriter/flush/)() | बफ़र की सामग्री को अंतर्निहित स्ट्रीम में फ़्लश करता है। |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | हमेशा ASCII एन्कोडिंग लौटाता है। |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | वर्तमान में उपयोग किए जा रहे [IFormatProvider](../iformatprovider/) ऑब्जेक्ट को लौटाता है। |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | वर्तमान में उपयोग किए जा रहे [IFormatProvider](../iformatprovider/) ऑब्जेक्ट को लौटाता है। |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट में लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) की वह विशेषता जो स्ट्रिंग और nullptr के मामले के लिए है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) की वह विशेषता जो स्ट्रिंग्स के मामले के लिए है। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयरड रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | एक लाइन टर्मिनेटर स्ट्रिंग सेट करता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट में अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(**bool**) override | निर्दिष्ट bool मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | निर्दिष्ट ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(char_t) override | निर्दिष्ट कैरेक्टर मान को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)([Decimal](../decimal/)) override | [Decimal](../decimal/) मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**double**) override | डबल-प्रेसिशन फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**int32_t**) override | 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**int64_t**) override | 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**float**) override | सिंगल-प्रेसिशन फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const [String](../string/)\&) override | निर्दिष्ट स्ट्रिंग ऑब्जेक्ट को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**uint32_t**) override | अनसाइंड 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(**uint64_t**) override | अनसाइंड 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | निर्दिष्ट कैरेक्टर एरे की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट कैरेक्टर एरे की मान रेंज की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const char_t *) override | निर्दिष्ट c-string को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | निर्दिष्ट [TypeInfo](../typeinfo/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | निर्दिष्ट 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम पर लिखता है। |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फॉर्मेट के अनुसार फॉर्मेट करके स्ट्रीम पर लिखता है। |
| void [WriteLine](./writeline/)() override | वर्तमान लाइन टर्मिनेटर को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | निर्दिष्ट ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**bool**) override | निर्दिष्ट bool मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(char_t) override | निर्दिष्ट कैरेक्टर मान को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | [Decimal](../decimal/) मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**double**) override | डबल-प्रेसिशन फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(int) override | 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**int64_t**) override | 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**float**) override | सिंगल-प्रेसिशन फ्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | निर्दिष्ट स्ट्रिंग ऑब्जेक्ट को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**uint32_t**) override | अनसाइंड 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(**uint64_t**) override | अनसाइंड 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | निर्दिष्ट कैरेक्टर एरे की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट कैरेक्टर एरे की मान रेंज की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const char_t *) override | निर्दिष्ट c-string को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | निर्दिष्ट [TypeInfo](../typeinfo/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को वर्तमान लाइन टर्मिनेटर के साथ जोड़कर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए आउटपुट स्ट्रीम पर आउटपुट करता है। |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फॉर्मेट के अनुसार फॉर्मेट करके, लाइन-टर्मिनेटिंग कैरेक्टर्स के साथ स्ट्रीम पर लिखता है। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | डिस्ट्रक्टर। |
## देखें भी

* क्लास [TextWriter](../../system.io/textwriter/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)