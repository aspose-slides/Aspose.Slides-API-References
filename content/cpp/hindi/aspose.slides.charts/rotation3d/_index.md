---
title: Rotation3D
second_title: Aspose.Slides for C++ API संदर्भ
description: एक चार्ट के 3D घूर्णन का प्रतिनिधित्व करता है।
type: docs
weight: 1327
url: /hi/aspose.slides.charts/rotation3d/
---
## Rotation3D क्लास

3D चार्ट के घूर्णन का प्रतिनिधित्व करता है।

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है (20 से 2000 प्रतिशत के बीच)। पढ़ें **uint16_t**। |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें **uint16_t**। |
| **uint8_t** [get_Perspective](./get_perspective/)() override | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) लौटाता है (0 से 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नज़रअंदाज़ किया जाता है। पढ़ें **uint8_t**। |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | निर्धारित करता है कि चार्ट अक्षों को दाईं कोण पर रखा गया है या परिप्रेक्ष्य में खींचा गया है। अर्थात यह तय करता है कि अक्षों के कोण चार्ट के घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। पढ़ें **bool**। |
| **int8_t** [get_RotationX](./get_rotationx/)() override | 3D चार्ट्स के लिए X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है, यानी Y दिशा में ( -90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ के "Y Rotation" विकल्प के साथ मेल खाती है। पढ़ें **int8_t**। |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | 3D चार्ट्स के लिए Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है, यानी X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ के "X Rotation" विकल्प के साथ मेल खाती है। पढ़ें **uint16_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउन्ड को घटाता है। |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में सेट करता है (20 से 2000 प्रतिशत के बीच)। लिखें **uint16_t**। |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। लिखें **uint16_t**। |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू एंगल) सेट करता है (0 से 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नज़रअंदाज़ किया जाता है। लिखें **uint8_t**। |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | निर्धारित करता है कि चार्ट अक्ष दाएं कोण पर हैं या नहीं... लिखें **bool**। |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | X-अक्ष के चारों ओर घूर्णन डिग्री सेट करता है... लिखें **int8_t**। |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Y-अक्ष के चारों ओर घूर्णन डिग्री सेट करता है... लिखें **uint16_t**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'वें टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता और परत देता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में रूपांतरित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IRotation3D](../irotation3d/)
* क्लास [IDOMObject](../../aspose.slides/idomobject/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)