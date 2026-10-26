---
title: MathPortion
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: गणितीय संदर्भ के साथ एक भाग का प्रतिनिधित्व करता है।
type: docs
weight: 1041
url: /hi/aspose.slides.mathtext/mathportion/
---
## MathPortion वर्ग


Represents a portion with mathematical context inside.

```cpp
class MathPortion : public Aspose::Slides::Portion,
                    public Aspose::Slides::MathText::IMathPortion
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AddField](../../aspose.slides/portion/addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../../aspose.slides/ifieldtype/)\>) override | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है। |
| void [AddField](../../aspose.slides/portion/addfield/)([System::String](../../system/string/)) override | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करती है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली की फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली की फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिये। |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../../aspose.slides/ifield/)\> [get_Field](../../aspose.slides/portion/get_field/)() override | इस भाग का फ़ील्ड लौटाता है। केवल-पढ़ने योग्य [IField](../../aspose.slides/ifield/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathParagraph](../imathparagraph/)\> [get_MathParagraph](./get_mathparagraph/)() override | गणित पैराग्राफ |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../../aspose.slides/iportionformat/)\> [get_PortionFormat](../../aspose.slides/portion/get_portionformat/)() override | फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं और कोई इनहेरिटेंस लागू नहीं होती। केवल-पढ़ने योग्य [IPortionFormat](../../aspose.slides/iportionformat/)। |
| [System::String](../../system/string/) [get_Text](../../aspose.slides/portion/get_text/)() override | एक भाग का साधारण टेक्स्ट प्राप्त करता है। पढ़ें [System::String](../../system/string/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](../../aspose.slides/portion/getcoordinates/)() override | भाग की शुरुआत के निर्देशांक प्राप्त करता है। X निर्देशांक बिंदु भाग की शुरुआत को दर्शाता है, जिसमें पहला अक्षर और बाएँ साइड बियरिंग शामिल है। Y निर्देशांक टॉप साइड बियरिंग को शामिल करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](../../aspose.slides/portion/getrect/)() override | भाग को सीमित करने वाले आयत के निर्देशांक प्राप्त करता है। आयत में भाग के सभी टेक्स्ट लाइनों को शामिल किया जाता है, यहाँ तक कि खाली लाइनों को भी। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर के समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
|  [MathPortion](./mathportion/)() | [MathPortion](./) वर्ग का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
|  [Portion](../../aspose.slides/portion/portion/)() | [Portion](../../aspose.slides/portion/) वर्ग का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [Portion](../../aspose.slides/portion/portion/)([System::String](../../system/string/)) | [Portion](../../aspose.slides/portion/) वर्ग का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [Portion](../../aspose.slides/portion/portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](../../aspose.slides/portion/)\>) | [Portion](../../aspose.slides/portion/) वर्ग का नया इंस्टेंस इनिशियलाइज़ करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस के द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस के द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemoveField](../../aspose.slides/portion/removefield/)() override | इस फ़ील्ड भाग को सरल भाग में परिवर्तित करता है। |
| void [set_Text](../../aspose.slides/portion/set_text/)([System::String](../../system/string/)) override | एक भाग का साधारण टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणियाँ

उदाहरण:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## संबंधित देखें

* वर्ग [Portion](../../aspose.slides/portion/)
* वर्ग [IMathPortion](../imathportion/)
* नामस्थान [Aspose::Slides::MathText](../)
* लाइब्रेरी [Aspose.Slides](../../)