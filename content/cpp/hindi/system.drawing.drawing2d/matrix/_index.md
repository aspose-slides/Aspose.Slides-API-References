---
title: Matrix
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक 3x3 मैट्रिक्स का प्रतिनिधित्व करता है जो परिवर्तन ऑपरेशनों को परिभाषित करता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग कर ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस क्लास को System::SmartPtr प्वाइंटर में लपेटें और इसे फ़ंक्शन को तर्क के रूप में पास करने के लिए उपयोग करें।"
type: docs
weight: 118
url: /hi/system.drawing.drawing2d/matrix/
---
## मैट्रिक्स क्लास


Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | वर्तमान ऑब्जेक्ट की एक कॉपी बनाता है। |
| void [Dispose](./dispose/)() | वर्तमान ऑब्जेक्ट द्वारा अधिग्रहीत सभी ऑपरेटिंग सिस्टम संसाधनों को मुक्त करता है। |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | जाँचता है कि निर्दिष्ट ऑब्जेक्ट [Matrix](./) है और यह ऑब्जेक्ट के समान है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | मैट्रिक्स के तत्वों को निम्न क्रम में रखते हुए एक एरे लौटाता है: m11, m12, m21, m22, dx, dy। |
| **bool** [get_IsIdentity](./get_isidentity/)() const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मैट्रिक्स पहचान मैट्रिक्स है या नहीं। |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मैट्रिक्स उल्टा किया जा सकता है या नहीं। |
| **float** [get_OffsetX](./get_offsetx/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स का X अनुवाद मान लौटाता है। |
| **float** [get_OffsetY](./get_offsety/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स का Y अनुवाद मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| void [Invert](./invert/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को उल्टा करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [Matrix](./matrix/)() | [Matrix](./) क्लास का नया उदाहरण बनाता है जो पहचान मैट्रिक्स का प्रतिनिधित्व करता है। |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | [Matrix](./) क्लास का नया उदाहरण बनाता है और इसे निर्दिष्ट मानों से प्रारंभ करता है। |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | [Matrix](./) क्लास का नया उदाहरण बनाता है जो निर्दिष्ट आयत और बिंदुओं की एरे द्वारा परिभाषित ज्यामितीय रूपांतरण को दर्शाता है। |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | [Matrix](./) क्लास का नया उदाहरण बनाता है जो निर्दिष्ट आयत और बिंदुओं की एरे द्वारा परिभाषित ज्यामितीय रूपांतरण को दर्शाता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को निर्दिष्ट मैट्रिक्स से गुणा करता है। |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को निर्दिष्ट मैट्रिक्स से गुणा करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइन्मेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Reset](./reset/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को रीसेट करता है ताकि वह पहचान मैट्रिक्स बन जाए। |
| void [Rotate](./rotate/)(**float**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को निर्दिष्ट कोण द्वारा घड़ी की दिशा में घुमाता है। |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को मूल बिंदु के चारों ओर निर्दिष्ट कोण द्वारा घड़ी की दिशा में घुमाता है। |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण द्वारा घड़ी की दिशा में घुमाता है। |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स को निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण द्वारा घड़ी की दिशा में घुमाता है। |
| void [Scale](./scale/)(**float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट स्केल वेक्टर लागू करता है। |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट स्केल वेक्टर लागू करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Shear](./shear/)(**float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट शियर वेक्टर लागू करता है। |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट शियर वेक्टर लागू करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्मेशन को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्मेशन को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्मेशन को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्मेशन को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स के केवल स्केल और रोटेट घटकों को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स के केवल स्केल और रोटेट घटकों को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स के केवल स्केल और रोटेट घटकों को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स के केवल स्केल और रोटेट घटकों को निर्दिष्ट बिंदुओं पर लागू करता है। |
| void [Translate](./translate/)(**float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट ट्रांसलेट वेक्टर लागू करता है। |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स पर निर्दिष्ट ट्रांसलेट वेक्टर लागू करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स से एरे में प्रत्येक वेक्टर को गुणा करता है। |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मैट्रिक्स से एरे में प्रत्येक वेक्टर को गुणा करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Matrix](./~matrix/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Drawing::Drawing2D](../)
* लाइब्रेरी [Aspose.Slides](../../)