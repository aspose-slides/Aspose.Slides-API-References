---
title: GraphicsPath
second_title: Aspose.Slides for C++ API संदर्भ
description: "जुड़ी हुई लाइनों और वक्रों का एक सेट दर्शाता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion faults उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 66
url: /hi/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath क्लास


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में जुड़े हुए लाइनों और वक्रों का एक सेट दर्शाता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन faults उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class GraphicsPath : public System::Object
```

## Methods

| मेथड | विवरण |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट अण्डाकार चाप जोड़ता है। |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट अण्डाकार चाप जोड़ता है। |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट अण्डाकार चाप जोड़ता है। |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट अण्डाकार चाप जोड़ता है। |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट क्यूबिक बीज़ियर वक्र जोड़ता है। |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट क्यूबिक बीज़ियर वक्र जोड़ता है। |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट क्यूबिक बीज़ियर वक्र जोड़ता है। |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट क्यूबिक बीज़ियर वक्र जोड़ता है। |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान चित्र में जुड़े हुए क्यूबिक बीज़ियर वक्रों का क्रम जोड़ता है। |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान चित्र में जुड़े हुए क्यूबिक बीज़ियर वक्रों का क्रम जोड़ता है। |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट बन्द वक्र जोड़ता है। |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट बन्द वक्र जोड़ता है। |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट वक्र जोड़ता है। |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट वक्र जोड़ता है। |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट वक्र जोड़ता है। |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट वक्र जोड़ता है। |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट दीर्घवृत्त जोड़ता है। |
| void [AddEllipse](./addellipse/)(int, int, int, int) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट दीर्घवृत्त जोड़ता है। |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट दीर्घवृत्त जोड़ता है। |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट दीर्घवृत्त जोड़ता है। |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट रेखा जोड़ता है। |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट रेखा जोड़ता है। |
| void [AddLine](./addline/)(int, int, int, int) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट रेखा जोड़ता है। |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट रेखा जोड़ता है। |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में जुड़े हुए रेखा खंडों की निर्दिष्ट श्रृंखला जोड़ता है। |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में जुड़े हुए रेखा खंडों की निर्दिष्ट श्रृंखला जोड़ता है। |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट पथ जोड़ता है। |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में पाई आकार की निर्दिष्ट रूपरेखा जोड़ता है। |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में पाई आकार की निर्दिष्ट रूपरेखा जोड़ता है। |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में पाई आकार की निर्दिष्ट रूपरेखा जोड़ता है। |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट बहुभुज जोड़ता है। |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट बहुभुज जोड़ता है। |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट आयत जोड़ता है। |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में निर्दिष्ट आयत जोड़ता है। |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में आयतों की निर्दिष्ट श्रृंखला जोड़ता है। |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में आयतों की निर्दिष्ट श्रृंखला जोड़ता है। |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में एक टेक्स्ट स्ट्रिंग जोड़ता है। |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में एक टेक्स्ट स्ट्रिंग जोड़ता है। |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में एक टेक्स्ट स्ट्रिंग जोड़ता है। |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में एक टेक्स्ट स्ट्रिंग जोड़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | वर्तमान ऑब्जेक्ट की एक प्रति बनाता है। |
| void [CloseAllFigures](./closeallfigures/)() | सभी खुले आकृतियों को बंद करता है और एक नई शुरू करता है। |
| void [CloseFigure](./closefigure/)() | वर्तमान आकृति को बंद करता है और नई शुरू करता है। |
| void [Dispose](./dispose/)() | वर्तमान ऑब्जेक्ट द्वारा प्राप्त सभी ऑपरेटिंग सिस्टम संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [Flatten](./flatten/)() | पथ में प्रत्येक वक्र को जुड़े हुए रेखाओं की श्रृंखला में बदलकर सपाट करता है। 0.25 का फ्लैटनेस मान उपयोग किया जाता है। |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | पथ में प्रत्येक वक्र को जुड़े हुए रेखाओं की श्रृंखला में बदलकर सपाट करता है। 0.25 का फ्लैटनेस मान उपयोग किया जाता है। |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | पथ में प्रत्येक वक्र को जुड़े हुए रेखाओं की श्रृंखला में बदलकर सपाट करता है। |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | वर्तमान ऑब्जेक्ट का भराव मोड लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ को बनाने वाले बिंदुओं और उनके प्रकारों को शामिल करने वाला [PathData](../pathdata/) ऑब्जेक्ट लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ को बनाने वाले बिंदुओं को शामिल करने वाला एरे लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ को बनाने वाले बिंदुओं के प्रकार दर्शाने वाले मानों को शामिल करने वाला एरे लौटाता है। |
| int [get_PointCount](./get_pointcount/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में बिंदुओं की संख्या लौटाता है। |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | निर्दिष्ट मैट्रिक्स से रूपांतरित होने पर वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ को सीमित करने वाले आयत का प्रतिनिधित्व करने वाला [RectangleF](../../system.drawing/rectanglef/) ऑब्जेक्ट लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | एक मान लौटाता है जो बिटवाइज़ संयोजन है ... जो दर्शाता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ में कौन से प्रकार के आकृतियां शामिल हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | पथ में अंतिम बिंदु का प्रतिनिधित्व करने वाला [PointF](../../system.drawing/pointf/) ऑब्जेक्ट लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | निर्दिष्ट भराव मोड के साथ [GraphicsPath](./) क्लास का नया उदाहरण बनाता है। |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | निर्दिष्ट पथ का प्रतिनिधित्व करने वाला [GraphicsPath](./) ऑब्जेक्ट का नया उदाहरण बनाता है। |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | निर्दिष्ट पथ का प्रतिनिधित्व करने वाला [GraphicsPath](./) ऑब्जेक्ट का नया उदाहरण बनाता है। |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | निर्दिष्ट [GraphicsPath](./) की रूपरेखा के भीतर (या नीचे) निर्दिष्ट बिंदु स्थित है या नहीं दर्शाता है, जब इसे निर्दिष्ट [Pen](../../system.drawing/pen/) से बनाया गया हो। लागू नहीं किया गया। |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | निर्धारित करता है कि निर्दिष्ट बिंदु वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ के भीतर स्थित है या नहीं। |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | निर्धारित करता है कि निर्दिष्ट बिंदु वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ के भीतर स्थित है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाएँ प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर के साथ वैल्यू प्रकार के ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और नलपॉइंटर के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Reset](./reset/)() | सभी बिंदुओं को हटाकर पथ को खाली करता है। |
| void [Reverse](./reverse/)() | [GraphicsPath](./) की PathPoints एरे में बिंदुओं का क्रम उलटता है। |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | वर्तमान ऑब्जेक्ट का भराव मोड सेट करता है। |
| void [SetMarkers](./setmarkers/)() | लागू नहीं किया गया। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को एक वैक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वैक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [StartFigure](./startfigure/)() | एक नई आकृति शुरू करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | निर्दिष्ट ट्रांसफॉर्म मैट्रिक्स को लागू करके वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए पथ को रूपांतरित करता है। |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | इस पथ को मूल पथ के चारों ओर की रूपरेखा से बदलता है। |
|  [~GraphicsPath](./~graphicspath/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## See Also

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Drawing::Drawing2D](../)
* लाइब्रेरी [Aspose.Slides](../../)