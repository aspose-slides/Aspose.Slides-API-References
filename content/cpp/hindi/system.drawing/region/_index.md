---
title: Region
second_title: Aspose.Slides for C++ API संदर्भ
description: "ग्राफ़िक आकार के अंदरूनी हिस्से का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या operator new का उपयोग करके नहीं बनाना चाहिए, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों में पास करें।"
type: docs
weight: 261
url: /hi/system.drawing/region/
---
## Region वर्ग

ग्राफिक आकार के अंदरूनी हिस्से का प्रतिनिधित्व करता है। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या operator new का उपयोग करके नहीं बनाना चाहिए, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों में पास करें।

```cpp
class Region : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | वर्तमान वस्तु की एक प्रति लौटाता है। |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस भाग के साथ प्रतिस्थापित करता है जो निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र का वह हिस्सा है जो इस क्षेत्र के साथ प्रतिच्छेद नहीं करता। |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस भाग के साथ प्रतिस्थापित करता है जो निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र का वह हिस्सा है जो इस क्षेत्र के साथ प्रतिच्छेद नहीं करता। |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस भाग के साथ प्रतिस्थापित करता है जो निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र का वह हिस्सा है जो इस क्षेत्र के साथ प्रतिच्छेद नहीं करता। |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस भाग के साथ प्रतिस्थापित करता है जो निर्दिष्ट क्षेत्र का वह हिस्सा है जो इस क्षेत्र के साथ प्रतिच्छेद नहीं करता। |
| void [Dispose](./dispose/)() | वर्तमान वस्तु द्वारा प्राप्त सभी ऑपरेटिंग सिस्टम संसाधनों को मुक्त करता है। |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | निर्धारित करता है कि क्या निर्दिष्ट क्षेत्र, निर्दिष्ट ड्रॉइंग सतह पर वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के समान है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, फिर भी दो NaN को समान माना जाता है, इस प्रकार C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, फिर भी दो NaN को समान माना जाता है, इस प्रकार C#-शैली के डबल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस परिणाम के साथ प्रतिस्थापित करता है जिसमें निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र को इससे निष्कासन किया गया है। |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस परिणाम के साथ प्रतिस्थापित करता है जिसमें निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र को इससे निष्कासन किया गया है। |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस परिणाम के साथ प्रतिस्थापित करता है जिसमें निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र को इससे निष्कासन किया गया है। |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को उस परिणाम के साथ प्रतिस्थापित करता है जिसमें निर्दिष्ट क्षेत्र को इससे निष्कासन किया गया है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | एक [RectangleF](../rectanglef/) संरचना प्राप्त करता है जो एक आयत को दर्शाती है जो इस [Region](./) को [Graphics](../graphics/) वस्तु की ड्रॉइंग सतह पर सीमित करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफरेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं का हैशिंग सक्षम करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को परिभाषित करने वाले डेटा युक्त RegionData वस्तु लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | निर्दिष्ट मैट्रिक्स परिवर्तन लागू करने के बाद इस [Region](./) का अनुमान लगाने वाले [RectangleF](../rectanglef/) संरचनाओं का एक एरे लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के प्रतिच्छेदन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के प्रतिच्छेदन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र के प्रतिच्छेदन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट क्षेत्र के प्रतिच्छेदन के परिणाम के साथ प्रतिस्थापित करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या वस्तु लक्ष्य प्रकार द्वारा वर्णित प्रकार की एक उदाहरण है। C# 'is' ऑपरेटर का समकक्ष। |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र का निर्दिष्ट ड्रॉइंग सतह पर आंतरिक हिस्सा खाली है। |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र का निर्दिष्ट ड्रॉइंग सतह पर अनंत आंतरिक हिस्सा है। |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | निर्धारित करता है कि क्या निर्दिष्ट बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | निर्धारित करता है कि क्या निर्दिष्ट बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | निर्धारित करता है कि क्या निर्दिष्ट आयत का कोई भाग वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | निर्धारित करता है कि क्या निर्दिष्ट आयत का कोई भाग वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | निर्दिष्ट ग्राफ़िक्स का उपयोग करके निर्धारित करता है कि क्या指定 बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | निर्दिष्ट ग्राफ़िक्स का उपयोग करके निर्धारित करता है कि क्या निर्दिष्ट बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | निर्दिष्ट ग्राफ़िक्स का उपयोग करके निर्धारित करता है कि क्या निर्दिष्ट आयत का कोई भाग वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | निर्दिष्ट ग्राफ़िक्स का उपयोग करके निर्धारित करता है कि क्या निर्दिष्ट आयत का कोई भाग वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | निर्धारित करता है कि क्या निर्दिष्ट बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | निर्दिष्ट ग्राफ़िक्स का उपयोग करके निर्धारित करता है कि क्या निर्दिष्ट बिंदु वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र के भीतर स्थित है। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [MakeEmpty](./makeempty/)() | वर्तमान वस्तु को खाली आंतरिक भाग से आरंभ करता है। |
| void [MakeInfinite](./makeinfinite/)() | इस क्षेत्र वस्तु को अनंत आंतरिक भाग से आरंभ करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया वस्तु आरंभ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया वस्तु आरंभ करता है और सबक्लासों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार की वस्तु की nullptr के साथ संदर्भ-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
|  [Region](./region/)() | [Region](./) वर्ग का एक नया उदाहरण बनाता है। |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र को दर्शाने वाला [Region](./) वर्ग का एक नया उदाहरण बनाता है। |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र को दर्शाने वाला [Region](./) वर्ग का एक नया उदाहरण बनाता है। |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र को दर्शाने वाला [Region](./) वर्ग का एक नया उदाहरण बनाता है। |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | निर्दिष्ट RegionData वस्तु द्वारा परिभाषित क्षेत्र को दर्शाने वाला [Region](./) वर्ग का एक नया उदाहरण बनाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफरेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफरेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | निर्दिष्ट मैट्रिक्स द्वारा इस क्षेत्र को परिवर्तित करता है। |
| void [Transform](./transform/)(const SkMatrix\&) | निर्दिष्ट मैट्रिक्स द्वारा इस क्षेत्र को परिवर्तित करता है। |
| void [Translate](./translate/)(int, int) | निर्दिष्ट मात्रा से क्षेत्र के निर्देशांक को स्थानांतरित करता है। |
| void [Translate](./translate/)(**float**, **float**) | निर्दिष्ट मात्रा से क्षेत्र के निर्देशांक को स्थानांतरित करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के संघ ऑपरेशन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के संघ ऑपरेशन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र के संघ ऑपरेशन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट क्षेत्र के संघ ऑपरेशन के परिणाम के साथ प्रतिस्थापित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफरेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफरेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के उन भागों के साथ प्रतिस्थापित करता है जो प्रतिच्छेद नहीं करते। |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट आयत द्वारा परिभाषित क्षेत्र के उन भागों के साथ प्रतिस्थापित करता है जो प्रतिच्छेद नहीं करते। |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट पथ द्वारा परिभाषित क्षेत्र के उन भागों के साथ प्रतिस्थापित करता है जो प्रतिच्छेद नहीं करते। |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए क्षेत्र को इस क्षेत्र और निर्दिष्ट क्षेत्र के उन भागों के साथ प्रतिस्थापित करता है जो प्रतिच्छेद नहीं करते। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
| virtual  [~Region](./~region/)() | डिस्ट्रक्टर। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)