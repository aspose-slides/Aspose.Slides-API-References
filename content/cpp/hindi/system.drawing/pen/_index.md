---
title: Pen
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "रेखाओं और वक्रों के रंग, चौड़ाई आदि जैसी गुणों का प्रतिनिधित्व करता है जिन्हें खींचा जा रहा है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new द्वारा कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करें।"
type: docs
weight: 183
url: /hi/system.drawing/pen/
---
## Pen क्लास

Represents properties such as color, width etc. of the lines and curves being drawn. Objects of this क्लास should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this क्लास into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Pen : public System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | वर्तमान ऑब्जेक्ट की एक प्रति लौटाता है। |
| void [Dispose](./dispose/)() | वर्तमान ऑब्जेक्ट द्वारा प्राप्त सभी संचालन संसाधनों को रिलीज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | वर्तमान [Pen](./) ऑब्जेक्ट की अलाइनमेंट दर्शाने वाला मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | इस पेन के [Brush](../brush/) ऑब्जेक्ट को लौटाता है। |
| [Color](../color/) [get_Color](./get_color/)() const | इस पेन का रंग लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | कम्पाउंड पेन को निर्दिष्ट करने वाले मानों की एक एरे लौटाता है। |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | डैश्ड लाइन के दोनों सिरों पर प्रयुक्त कैप को दर्शाने वाला मान लौटाता है। |
| **float** [get_DashOffset](./get_dashoffset/)() const | लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | डैश्ड लाइन में कस्टम डैश पैटर्न दर्शाने वाली एरे लौटाता है। |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | वर्तमान [Pen](./) ऑब्जेक्ट की डैश शैली दर्शाने वाला मान लौटाता है। |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | वर्तमान [Pen](./) ऑब्जेक्ट के एंडिंग लाइन कैप को दर्शाने वाला मान लौटाता है। |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | इस [Pen](./) ऑब्जेक्ट द्वारा खींची गई लाइनों के जुड़ने के तरीके को दर्शाने वाला मान लौटाता है। |
| **float** [get_MiterLimit](./get_miterlimit/)() const | माइटर्ड कोने पर जॉइन की मोटाई की सीमा लौटाता है। |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | लागू नहीं किया गया। |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | वर्तमान [Pen](./) ऑब्जेक्ट के शुरुआती लाइन कैप को दर्शाने वाला मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पेन के लिए ज्यामितीय ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाले मैट्रिक्स ऑब्जेक्ट की एक प्रति लौटाता है। |
| **float** [get_Width](./get_width/)() const | वर्तमान [Pen](./) ऑब्जेक्ट की चौड़ाई लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | वर्तमान ऑब्जेक्ट के ट्रांसफ़ॉर्म मैट्रिक्स को निर्दिष्ट मैट्रिक्स से गुणा करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
|  [Pen](./pen/)(const [Color](../color/)\&) | निर्दिष्ट रंग को दर्शाने वाला नया [Pen](./) ऑब्जेक्ट बनाता है। |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | निर्दिष्ट रंग और चौड़ाई को दर्शाने वाला नया [Pen](./) ऑब्जेक्ट बनाता है। |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | निर्दिष्ट [Brush](../brush/) ऑब्जेक्ट से प्रारंभ किया गया नया [Pen](./) ऑब्जेक्ट बनाता है। |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | निर्दिष्ट [Brush](../brush/) ऑब्जेक्ट से प्रारंभ किया गया नया [Pen](./) ऑब्जेक्ट बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तौर पर वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [ResetTransform](./resettransform/)() | वर्तमान ऑब्जेक्ट के ट्रांसफ़ॉर्म मैट्रिक्स को रीसेट करता है ताकि वह पहचान मैट्रिक्स बन जाए। |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट कोण से स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को घुमाता है। |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट कारकों से स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को स्केल करता है। |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | वर्तमान [Pen](./) ऑब्जेक्ट की अलाइनमेंट सेट करता है। |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | इस पेन के [Brush](../brush/) ऑब्जेक्ट को सेट करता है। |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | इस पेन का रंग सेट करता है। |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | कम्पाउंड पेन को निर्दिष्ट करने वाले मानों की एरे सेट करता है। |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | कस्टम एंड लाइन कैप सेट करता है। |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | कस्टम स्टार्ट लाइन कैप सेट करता है। |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | डैश्ड लाइन के दोनों सिरों पर उपयोग किए जाने वाले कैप को निर्दिष्ट करने वाला मान सेट करता है। |
| void [set_DashOffset](./set_dashoffset/)(**float**) | लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी सेट करता है। |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | डैश्ड लाइन में कस्टम डैश पैटर्न निर्दिष्ट करने वाली एरे सेट करता है। एरे में वैकल्पिक डैश और स्पेस की लंबाई दर्शाने वाले संख्या होते हैं। |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | वर्तमान [Pen](./) ऑब्जेक्ट की डैश शैली को निर्दिष्ट करने वाला मान सेट करता है। |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | वर्तमान [Pen](./) ऑब्जेक्ट के एंडिंग लाइन कैप को सेट करता है। |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | इस [Pen](./) ऑब्जेक्ट द्वारा खींची गई लाइनों के जुड़ने के तरीके को निर्दिष्ट करने वाला मान सेट करता है। |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | माइटर्ड कोने पर जॉइन की मोटाई की सीमा सेट करता है। |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | वर्तमान [Pen](./) ऑब्जेक्ट के शुरुआती लाइन कैप को सेट करता है। |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए पेन के लिए ज्यामितीय ट्रांसफ़ॉर्मेशन निर्दिष्ट करने वाला मैट्रिक्स ऑब्जेक्ट सेट करता है। |
| void [set_Width](./set_width/)(**float**) | वर्तमान [Pen](./) ऑब्जेक्ट की चौड़ाई सेट करता है। |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | लागू नहीं किया गया। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को ट्रांसलेट करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)