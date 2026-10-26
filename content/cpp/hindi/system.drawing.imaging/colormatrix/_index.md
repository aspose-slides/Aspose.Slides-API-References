---
title: ColorMatrix
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "RGBAW रंग स्थान के निर्देशांक वाले 5x5 मैट्रिक्स का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में संलग्न करें और इस पॉइंटर का उपयोग तर्क के रूप में फ़ंक्शन में पास करने के लिए करें।"
type: docs
weight: 27
url: /hi/system.drawing.imaging/colormatrix/
---
## ColorMatrix क्लास

RGBAW रंग स्थान के लिए निर्देशांक युक्त 5x5 मैट्रिक्स का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। स्टैक पर या operator new का उपयोग करके इस प्रकार का इंस्टेंस कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में संलग्न करें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।

```cpp
class ColorMatrix : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | [ColorMatrix](./) क्लास की नई इंस्टेंस बनाता है और इसे आइडेंटिटी मैट्रिक्स के मानों से प्रारंभ करता है। |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | [ColorMatrix](./) क्लास की नई इंस्टेंस बनाता है और इसे निर्दिष्ट मानों से प्रारंभ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaNs को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaNs को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_Matrix00](./get_matrix00/)() const | 0-थ पंक्ति और 0-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix01](./get_matrix01/)() const | 0-थ पंक्ति और 1-st स्तंभ में मान लौटाता है। |
| **float** [get_Matrix02](./get_matrix02/)() const | 0-थ पंक्ति और 2-nd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix03](./get_matrix03/)() const | 0-थ पंक्ति और 3-rd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix04](./get_matrix04/)() const | 0-थ पंक्ति और 4-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix10](./get_matrix10/)() const | 1-st पंक्ति और 0-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix11](./get_matrix11/)() const | 1-st पंक्ति और 1-st स्तंभ में मान लौटाता है। |
| **float** [get_Matrix12](./get_matrix12/)() const | 1-st पंक्ति और 2-nd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix13](./get_matrix13/)() const | 1-st पंक्ति और 3-rd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix14](./get_matrix14/)() const | 1-st पंक्ति और 4-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix20](./get_matrix20/)() const | 2-nd पंक्ति और 0-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix21](./get_matrix21/)() const | 2-nd पंक्ति और 1-st स्तंभ में मान लौटाता है। |
| **float** [get_Matrix22](./get_matrix22/)() const | 2-nd पंक्ति और 2-nd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix23](./get_matrix23/)() const | 2-nd पंक्ति और 3-rd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix24](./get_matrix24/)() const | 2-nd पंक्ति और 4-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix30](./get_matrix30/)() const | 3-rd पंक्ति और 0-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix31](./get_matrix31/)() const | 3-rd पंक्ति और 1-st स्तंभ में मान लौटाता है। |
| **float** [get_Matrix32](./get_matrix32/)() const | 3-rd पंक्ति और 2-nd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix33](./get_matrix33/)() const | 3-rd पंक्ति और 3-rd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix34](./get_matrix34/)() const | 3-rd पंक्ति और 4-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix40](./get_matrix40/)() const | 4-थ पंक्ति और 0-थ स्तंभ में मान लौटाता है। |
| **float** [get_Matrix41](./get_matrix41/)() const | 4-थ पंक्ति और 1-st स्तंभ में मान लौटाता है। |
| **float** [get_Matrix42](./get_matrix42/)() const | 4-थ पंक्ति और 2-nd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix43](./get_matrix43/)() const | 4-थ पंक्ति और 3-rd स्तंभ में मान लौटाता है। |
| **float** [get_Matrix44](./get_matrix44/)() const | 4-थ पंक्ति और 4-थ स्तंभ में मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| **float** [idx_get](./idx_get/)(int, int) | निर्दिष्ट पंक्ति और स्तंभ पर मान लौटाता है। |
| **float** [idx_set](./idx_set/)(int, int, **float**) | मैट्रिक्स में निर्दिष्ट स्थान पर निर्दिष्ट मान सेट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकाक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिये। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिये। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Matrix00](./set_matrix00/)(**float**) | 0-थ पंक्ति और 0-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix01](./set_matrix01/)(**float**) | 0-थ पंक्ति और 1-st स्तंभ में मान सेट करता है। |
| void [set_Matrix02](./set_matrix02/)(**float**) | 0-थ पंक्ति और 2-nd स्तंभ में मान सेट करता है। |
| void [set_Matrix03](./set_matrix03/)(**float**) | 0-थ पंक्ति और 3-rd स्तंभ में मान सेट करता है। |
| void [set_Matrix04](./set_matrix04/)(**float**) | 0-थ पंक्ति और 4-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix10](./set_matrix10/)(**float**) | 1-st पंक्ति और 0-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix11](./set_matrix11/)(**float**) | 1-st पंक्ति और 1-st स्तंभ में मान सेट करता है। |
| void [set_Matrix12](./set_matrix12/)(**float**) | 1-st पंक्ति और 2-nd स्तंभ में मान सेट करता है। |
| void [set_Matrix13](./set_matrix13/)(**float**) | 1-st पंक्ति और 3-rd स्तंभ में मान सेट करता है। |
| void [set_Matrix14](./set_matrix14/)(**float**) | 1-st पंक्ति और 4-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix20](./set_matrix20/)(**float**) | 2-nd पंक्ति और 0-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix21](./set_matrix21/)(**float**) | 2-nd पंक्ति और 1-st स्तंभ में मान सेट करता है। |
| void [set_Matrix22](./set_matrix22/)(**float**) | 2-nd पंक्ति और 2-nd स्तंभ में मान सेट करता है। |
| void [set_Matrix23](./set_matrix23/)(**float**) | 2-nd पंक्ति और 3-rd स्तंभ में मान सेट करता है। |
| void [set_Matrix24](./set_matrix24/)(**float**) | 2-nd पंक्ति और 4-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix30](./set_matrix30/)(**float**) | 3-rd पंक्ति और 0-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix31](./set_matrix31/)(**float**) | 3-rd पंक्ति और 1-st स्तंभ में मान सेट करता है। |
| void [set_Matrix32](./set_matrix32/)(**float**) | 3-rd पंक्ति और 2-nd स्तंभ में मान सेट करता है। |
| void [set_Matrix33](./set_matrix33/)(**float**) | 3-rd पंक्ति और 3-rd स्तंभ में मान सेट करता है। |
| void [set_Matrix34](./set_matrix34/)(**float**) | 3-rd पंक्ति और 4-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix40](./set_matrix40/)(**float**) | 4-थ पंक्ति और 0-थ स्तंभ में मान सेट करता है। |
| void [set_Matrix41](./set_matrix41/)(**float**) | 4-थ पंक्ति और 1-st स्तंभ में मान सेट करता है। |
| void [set_Matrix42](./set_matrix42/)(**float**) | 4-थ पंक्ति और 2-nd स्तंभ में मान सेट करता है। |
| void [set_Matrix43](./set_matrix43/)(**float**) | 4-थ पंक्ति और 3-rd स्तंभ में मान सेट करता है। |
| void [set_Matrix44](./set_matrix44/)(**float**) | 4-थ पंक्ति और 4-थ स्तंभ में मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को शैर्ड के बजाय वीक़ पॉइंटर सेट करता है। कंटेनरों में पॉइंटर्स को वीक़ मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक़ रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक़ रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Drawing::Imaging](../)
* लाइब्रेरी [Aspose.Slides](../../)