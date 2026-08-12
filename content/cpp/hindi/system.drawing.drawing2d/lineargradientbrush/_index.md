---
title: LinearGradientBrush
second_title: Aspose.Slides for C++ API संदर्भ
description: "रैखिक ग्रेडिएंट ब्रश का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन को तर्क के रूप में पास करें।"
type: docs
weight: 105
url: /hi/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush वर्ग


एक रैखिक ग्रेडिएंट ब्रश का प्रतिनिधित्व करता है। इस वर्ग के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। स्टैक पर या operator new का उपयोग करके इस प्रकार का इंस्टेंस कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन को तर्क के रूप में पास करें।

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## मेथड्स

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | वर्तमान ऑब्जेक्ट की एक कॉपी बनाता है। |
| virtual void [Dispose](../../system/idisposable/dispose/)() | कुछ नहीं करता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | इस ब्रश के लिए बेस रंगों के कारकों और स्थितियों को निर्दिष्ट करने वाला ब्लेंड लौटाता है। |
| **bool** [get_GammaCorrection](./get_gammacorrection/)() const | एक मान लौटाता है जो दर्शाता है कि इस ब्रश के लिए गामा सुधार सक्षम है। |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | [ColorBlend](../colorblend/) ऑब्जेक्ट लौटाता है जो मल्टीकलर रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_LinearColors](./get_linearcolors/)() const | इस ग्रेडिएंट के प्रारंभिक और अंतिम रंग लौटाता है। |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | एक बाउंडिंग आयत लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | [Matrix](../matrix/) ऑब्जेक्ट की एक कॉपी लौटाता है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए ब्रश के ज्यामितीय रूपांतरणों को निर्दिष्ट करता है। |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | रैप मोड लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | [LinearGradientBrush](./) का नया इंस्टेंस बनाता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को निर्दिष्ट मैट्रिक्स द्वारा गुणा करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ के लिए कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ के लिए कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [ResetTransform](./resettransform/)() | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स रीसेट करता है। |
| void [RotateTransform](./rotatetransform/)(**float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स घुमाता है। |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को स्केल करता है। |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | इस ब्रश के लिए बेस रंगों के कारकों और स्थितियों को निर्दिष्ट करने वाला ब्लेंड सेट करता है। |
| void [set_GammaCorrection](./set_gammacorrection/)(**bool**) | इस ब्रश के लिए गामा सुधार स्थिति सेट करता है। |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | [ColorBlend](../colorblend/) ऑब्जेक्ट सेट करता है जो मल्टीकलर रैखिक ग्रेडिएंट को परिभाषित करता है। |
| void [set_LinearColors](./set_linearcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | इस ग्रेडिएंट के प्रारंभिक और अंतिम रंग सेट करता है। |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | [Matrix](../matrix/) ऑब्जेक्ट सेट करता है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए ब्रश के ज्यामितीय रूपांतरणों को निर्दिष्ट करता है। |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | रैप मोड सेट करता है। |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | लागू नहीं किया गया। |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | लागू नहीं किया गया। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसलेट करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## संबंधित देखें

* क्लास [Brush](../../system.drawing/brush/)
* नामस्थान [System::Drawing::Drawing2D](../)
* लाइब्रेरी [Aspose.Slides](../../)