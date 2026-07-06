---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API संदर्भ
description: आकारों का संग्रह दर्शाता है।
type: docs
weight: 6980
url: /hi/aspose.slides/ishapecollection/
---
## IShapeCollection interface

आकारों का संग्रह दर्शाता है।

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [`IShape`](../ishape)। |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | आकार संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | एक नया ऑडियो फ्रेम बनाता है और Presentation.Audios सूची से मौजूदा ऑडियो वस्तु का उपयोग करके इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | एम्बेडेड WAV फ़ाइल के साथ एक नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है। |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | डिफॉल्ट फॉर्मेटिंग के साथ एक नया ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | नया ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफॉल्ट टेम्पलेट फॉर्मेटिंग के साथ आरंभ करता है। |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ आरंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ आरंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। क्लोन किया गया आकार मूल की स्थिति और आकार को बनाए रखता है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। नई आकार *sourceShape* की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | डिफॉल्ट टेम्पलेट स्टाइलिंग के साथ नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से जोड़ी गई किसी भी आकार के अनुसार समायोजित हो जाएगा। |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकारों में बदलता है, और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है। |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | गणितीय सामग्री रखने के लिए नया आयताकार ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि के साथ नया चित्र फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | नया Section Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | नया SmartArt आरेख बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | नया Summary Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | नया तालिका बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [Clear](../../aspose.slides/ishapecollection/clear)() | सभी आकारों को आकार संग्रह से हटाता है। |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | संग्रह में निर्दिष्ट आकार की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | नया ऑडियो फ्रेम बनाता है और Presentation.Audios सूची से मौजूदा ऑडियो वस्तु का उपयोग करके इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है। |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | नया ऑटो आकार बनाता है और डिफॉल्ट टेम्पलेट फॉर्मेटिंग लागू करके इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | नया ऑटो आकार बनाता है और वैकल्पिक रूप से डिफॉल्ट टेम्पलेट स्टाइलिंग के साथ इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ आरंभ करता है, और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ आरंभ करता है, और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | निर्दिष्ट आकार की कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। क्लोन किया गया आकार मूल की स्थिति और आकार को बनाए रखता है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | निर्दिष्ट आकार की कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। नई आकार *sourceShape* की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | निर्दिष्ट आकार की कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | नया कनेक्टर आकार बनाता है और डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करके इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | नया कनेक्टर आकार बनाता है और वैकल्पिक रूप से डिफॉल्ट टेम्पलेट स्टाइलिंग लागू करके इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | नया खाली समूह आकार बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। समूह का फ्रेम स्वचालित रूप से जोड़े गए किसी भी आकार के अनुसार समायोजित हो जाएगा। |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि के साथ नया चित्र फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | नया तालिका बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | आकार संग्रह से निर्दिष्ट आकार की पहली उपस्थिति को हटाता है। |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | आकार संग्रह से निर्दिष्ट सूचकांक पर आकार को हटाता है। |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | निर्दिष्ट आकार को आकार संग्रह के भीतर नई स्थिति में ले जाता है। |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | निर्दिष्ट आकारों को आकार संग्रह में ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है। |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | सभी आकारों को सम्मिलित करने वाला एक array बनाता है और लौटाता है। |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | निर्दिष्ट सीमा में सभी आकारों को सम्मिलित करने वाला एक array बनाता है और लौटाता है। |

### संबंधित देखें

* इंटरफ़ेस [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* इंटरफ़ेस [IShape](../ishape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->