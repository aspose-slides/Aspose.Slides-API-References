---
title: PathGradientBrush
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक ब्रश का प्रतिनिधित्व करता है जो ग्रेडिएंट के साथ GraphicsPath ऑब्जेक्ट के अंदर को भरता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिये करें।"
type: docs
weight: 144
url: /hi/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush क्लास

एक ब्रश का प्रतिनिधित्व करता है जो एक [GraphicsPath](../graphicspath/) ऑब्जेक्ट के आंतरिक भाग को ग्रेडिएंट से भरता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की एक कॉपी बनाता है। |
| virtual void [Dispose](../../system/idisposable/dispose/)() | कुछ नहीं करता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अवधारणाओं का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना नक़ल करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना नक़ल करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | लागू नहीं किया गया है। |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | वर्तमान ऑब्जेक्ट द्वारा भरे गए पाथ के केंद्र में स्थित एक रंग लौटाता है। |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | ग्रेडिएंट का मध्य बिंदु प्राप्त करता है। |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | ग्रेडिएंट फ़ॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | एक मान लौटाता है जो बहु-रंग रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | लागू नहीं किया गया है। |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | इस [PathGradientBrush](./) द्वारा भरें गये पाथ के बिंदुओं के अनुरूप रंग लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए ब्रश के लिए ज्यामितीय परिवर्तन निर्दिष्ट करने वाले [Matrix](../matrix/) ऑब्जेक्ट की एक कॉपी लौटाता है। |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | रैप मोड लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को निर्दिष्ट मैट्रिक्स द्वारा गुणा करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | [PathGradientBrush](./) क्लास का नया इंस्टेंस बनाता है। |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | [PathGradientBrush](./) क्लास का नया इंस्टेंस बनाता है। |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | [PathGradientBrush](./) क्लास का नया इंस्टेंस बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नलपॉइंटर के केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [ResetTransform](./resettransform/)() | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को रीसेट करता है जिससे वह पहचान (आइडेंटिटी) मैट्रिक्स बन जाए। |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को घुमाता है। |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट कारकों द्वारा स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को स्केल करता है। |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | इस ब्रश के लिए बेस रंगों के कारकों और स्थितियों को निर्दिष्ट करने वाला ब्लेंड सेट करता है। |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | वर्तमान ऑब्जेक्ट द्वारा भरे गए पाथ के केंद्र में स्थित एक रंग सेट करता है। |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | ग्रेडिएंट का मध्य बिंदु सेट करता है। |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | ग्रेडिएंट फ़ॉलऑफ़ के लिए फोकस बिंदु सेट करता है। |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | बहु-रंग रैखिक ग्रेडिएंट को परिभाषित करने वाला मान सेट करता है। |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | [PathGradientBrush](./) द्वारा भरें गये पाथ के बिंदुओं के अनुरूप रंग सेट करता है। |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए ब्रश के लिए ज्यामितीय परिवर्तन निर्दिष्ट करने वाला [Matrix](../matrix/) ऑब्जेक्ट सेट करता है। |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | रैप मोड सेट करता है। |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | लागू नहीं किया गया है। |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | लागू नहीं किया गया है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को एक कमजोर पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | निर्दिष्ट क्रम में निर्दिष्ट परिमाणों द्वारा स्थानीय ज्यामितीय ट्रांसफ़ॉर्मेशन को ट्रांसलेट करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंत्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Brush](../../system.drawing/brush/)
* नेमस्पेस [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)