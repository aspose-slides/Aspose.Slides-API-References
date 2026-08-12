---
title: IRotation3D
second_title: Aspose.Slides for C++ API संदर्भ
description: एक चार्ट का 3D घूर्णन दर्शाता है।
type: docs
weight: 1171
url: /hi/aspose.slides.charts/irotation3d/
---
## IRotation3D क्लास

एक चार्ट के 3D घूर्णन का प्रतिनिधित्व करता है।

```cpp
class IRotation3D : public virtual System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है (20 से 2000 प्रतिशत के बीच)। पढ़ें **uint16_t**। |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें **uint16_t**। |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | 3D चार्ट्स के लिए पर्सपेक्टिव मान (फ़ील्ड ऑफ़ व्यू कोण) लौटाता है (0 से 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नजरअंदाज़ किया जाता है। पढ़ें **uint8_t**। |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | निर्धारित करता है कि क्या चार्ट एक्सिस सीधे कोण पर हैं, बजाय पर्सपेक्टिव में खींचे जाने के। दूसरे शब्दों में यह तय करता है कि एक्सिस के कोण चार्ट के घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। पढ़ें **bool**। |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | 3D चार्ट्स के लिए X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है, अर्थात् Y दिशा में ( -90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के अनुरूप है। पढ़ें **int8_t**। |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | 3D चार्ट्स के लिए Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है, अर्थात् X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के अनुरूप है। पढ़ें **uint16_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट के साथ जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टैंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंन्ट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत (20 से 2000 प्रतिशत) के रूप में सेट करता है। लिखें **uint16_t**। |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई सेट करता है (5 से 500 प्रतिशत के बीच)। लिखें **uint16_t**। |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | 3D चार्ट्स के लिए पर्सपेक्टिव मान (फ़ील्ड ऑफ़ व्यू कोण) सेट करता है (0 से 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नजरअंदाज़ किया जाता है। लिखें **uint8_t**। |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | निर्धारित करता है कि क्या चार्ट एक्सिस सीधे कोण पर हैं, बजाय पर्सपेक्टिव में खींचे जाने के। दूसरे शब्दों में यह तय करता है कि एक्सिस के कोण चार्ट के घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। लिखें **bool**। |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | X-अक्ष के चारों ओर घूर्णन डिग्री सेट करता है, अर्थात् Y दिशा में ( -90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के अनुरूप है। लिखें **int8_t**। |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Y-अक्ष के चारों ओर घूर्णन डिग्री सेट करता है, अर्थात् X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के अनुरूप है। लिखें **uint16_t**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (न कि शेयर) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंन्ट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* क्लास [Object](../../system/object/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)