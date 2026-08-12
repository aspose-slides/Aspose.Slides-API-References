---
title: StringBuilder
second_title: Aspose.Slides for C++ API संदर्भ
description: "बफ़र जो स्ट्रिंग को भाग-बाग करके इकट्ठा करता है। इस प्रकार को या तो स्टैक में वैल्यू टाइप के रूप में या हीप में System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जा सकता है। एक बार ऑब्जेक्ट आवंटित हो जाने पर, इन दो उपयोग मामलों को कभी मिश्रित न करें: स्टैक-आवंटित ऑब्जेक्ट्स पर SmartPtr पॉइंटर्स रखना कड़ाई से प्रतिबंधित है।"
type: docs
weight: 326
url: /hi/system.text/stringbuilder/
---
## StringBuilder क्लास

[Buffer](../../system/buffer/) का उपयोग स्ट्रिंग को भाग-भाग में जुटाने के लिए किया जाता है। इस प्रकार को या तो स्टैक में वैल्यू टाइप के रूप में या हिप में [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जा सकता है। एक बार ऑब्जेक्ट आवंटित हो जाने पर, इन दो उपयोग मामलों को कभी मिश्रित न करें: स्टैक-आवंटित ऑब्जेक्ट्स पर [SmartPtr](../../system/smartptr/) पॉइंटर्स रखना कड़ाई से प्रतिबंधित है।

```cpp
class StringBuilder : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | बिल्डर में एक कैरेक्टर जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | बिल्डर में कई कैरेक्टर जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | बिल्डर में कैरेक्टर एरे जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | बिल्डर में कैरेक्टर एरे का स्लाइस जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | बिल्डर में स्ट्रिंग जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | बिल्डर में स्ट्रिंग स्लाइस जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को बिल्डर में जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | बिल्डर की सामग्री को बिल्डर में जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(**float**) | बिल्डर में फ्लोटिंग पॉइंट वैल्यू जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(**double**) | बिल्डर में फ्लोटिंग पॉइंट वैल्यू जोड़ता है। |
| [StringBuilder](./) * [Append](./append/)(int) | बिल्डर में इंटेजर वैल्यू जोड़ता है। |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | बिल्डर में अंकगणितीय वैल्यू जोड़ता है। |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | बिल्डर में एनीम वैल्यू की स्ट्रिंग प्रतिनिधित्व जोड़ता है। |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | बिल्डर में स्वरूपित स्ट्रिंग जोड़ता है। |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | बिल्डर में स्वरूपित स्ट्रिंग जोड़ता है। |
| [StringBuilder](./) * [AppendLine](./appendline/)() | बिल्डर में नया लाइन कैरेक्टर जोड़ता है। |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | बिल्डर में स्ट्रिंग के बाद नया लाइन कैरेक्टर जोड़ता है। |
| [StringBuilder](./) * [Clear](./clear/)() | बिल्डर से सभी कैरेक्टर हटाता है। |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | बिल्डर का डेटा मौजूदा एरे स्थितियों में कॉपी करता है। |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | सुनिश्चित करता है कि इस [System.Text.StringBuilder](./) के इंस्टेंस की क्षमता कम से कम निर्दिष्ट मान हो। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| int [get_Capacity](./get_capacity/)() const | स्ट्रिंग बिल्डर की वर्तमान क्षमता प्राप्त करता है। |
| int [get_Length](./get_length/)() const | बिल्डर में वर्तमान में मौजूद स्ट्रिंग की लंबाई प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| char_t [idx_get](./idx_get/)(int) const | निर्दिष्ट स्थिति पर कैरेक्टर प्राप्त करता है। |
| void [idx_set](./idx_set/)(int, char_t) | निर्दिष्ट स्थिति पर कैरेक्टर सेट करता है। |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | बिल्डर के निश्चित स्थान में स्ट्रिंग डालता है। |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | बिल्डर के निश्चित स्थान में दोहराई गई स्ट्रिंग डालता है। |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | बिल्डर के निश्चित स्थान में कैरेक्टर डालता है। |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | बिल्डर के निश्चित स्थान में कैरेक्टर डालता है। |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | बिल्डर के निश्चित स्थान में वैल्यू डालता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब क्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब क्लासेज़ के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| char_t [operator[]](./operator[]/)(int) const | निर्दिष्ट स्थिति पर कैरेक्टर प्राप्त करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | बिल्डर से फ्रैगमेंट हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयरड रेफ़रेंस काउंट घटाता है। |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | बिल्डर में सबस्ट्रिंग को प्रतिस्थापित करता है। |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | बिल्डर की रेंज में सबस्ट्रिंग को प्रतिस्थापित करता है। |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | बिल्डर में कैरेक्टर को प्रतिस्थापित करता है। |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | बिल्डर की रेंज में कैरेक्टर को प्रतिस्थापित करता है। |
| void [set_Capacity](./set_capacity/)(int) | स्ट्रिंग बिल्डर की वर्तमान क्षमता सेट करता है। |
| void [set_Length](./set_length/)(int) | बिल्डर को निर्दिष्ट लंबाई तक ट्रंकेट या बढ़ाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को एक वीक्स पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक्स मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को डिक्रीमेंट करता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [StringBuilder](./stringbuilder/)() | कन्स्ट्रक्टर। |
|  [StringBuilder](./stringbuilder/)(int) | कन्स्ट्रक्टर। |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | कन्स्ट्रक्टर। |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | कन्स्ट्रक्टर। |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | कन्स्ट्रक्टर। |
| [String](../../system/string/) [ToString](./tostring/)() const override | बिल्डर में वर्तमान में उपलब्ध स्ट्रिंग प्राप्त करता है। |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | बिल्डर में वर्तमान में उपलब्ध सबस्ट्रिंग प्राप्त करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक्स रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक्स रेफ़रेंस काउंट को डिक्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
|  [~StringBuilder](./~stringbuilder/)() | डिस्ट्रक्टर। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Text](../)
* लाइब्रेरी [Aspose.Slides](../../)