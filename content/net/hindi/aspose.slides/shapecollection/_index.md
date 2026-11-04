---
title: ShapeCollection
second_title: Aspose.Sildes .NET के लिये API संदर्भ
description: शेप्स का एक संग्रह दर्शाता है।
type: docs
weight: 9880
url: /hi/aspose.slides/shapecollection/
---
## ShapeCollection क्लास

शेप्स का एक संग्रह दर्शाता है।

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य Int32। |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | कोई मान लौटाता है जो संकेत करता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ) है या नहीं। केवल पढ़ने योग्य Boolean। |
| [Item](../../aspose.slides/shapecollection/item) { get; } | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [`IShape`](../ishape)। |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | शेप्स संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | समकालिक मूल लौटाता है। केवल पढ़ने योग्य Object। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | एक नई ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ी होती है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | एक नई ऑडियो फ्रेम बनाता है और Presentation.Audios सूची के मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | एक नई ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे शेप्स संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है। |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | एक नई ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ी होती है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नई ऑटो शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | एक नई ऑटो शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग से प्रारंभ करता है। |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। क्लोन किया गया शेप मूल की स्थिति और आकार बनाए रखता है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। नई शेप *sourceShape* की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ एक नया कनेक्टर शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | एक नया कनेक्टर शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | एक नया खाली समूह शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से समायोजित होगा ताकि जोड़े गए किसी भी शेप को फिट कर सके। |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | एक नया समूह शेप बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत शेप्स में परिवर्तित करता है, और परिणामस्वरूप समूह को शेप्स संग्रह के अंत में जोड़ता है। |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | गणितीय सामग्री रखने के लिए एक नया आयताकार ऑटो शेप बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि सहित एक नया पिक्चर फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | एक नया Section Zoom फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | एक SmartArt आरेख बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | एक नया Summary Zoom फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | एक नई टेबल बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | एक नया वीडियो फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | एक नया Zoom फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | एक नया Zoom फ्रेम बनाता है और इसे शेप्स संग्रह के अंत में जोड़ता है। |
| [Clear](../../aspose.slides/shapecollection/clear)() | शेप्स संग्रह से सभी शेप्स को हटाता है। |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | संग्रह में निर्दिष्ट शेप की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | एक नई ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ी होती है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | एक नई ऑडियो फ्रेम बनाता है और Presentation.Audios सूची के मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | एक नई ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios संग्रह में जोड़ा जाता है। |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | एक नई ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ी होती है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | एक नई ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है। |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | एक नई ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग से प्रारंभ करता है। |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। क्लोन किया गया शेप मूल की स्थिति और आकार को बनाए रखता है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। नई शेप *sourceShape* की चौड़ाई और ऊँचाई को बनाए रखती है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | एक नया खाली समूह शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। समूह का फ्रेम स्वचालित रूप से समायोजित होगा ताकि जोड़े गए किसी भी शेप को फिट कर सके। |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि सहित एक नया पिक्चर फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | एक नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | एक नई टेबल बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शेप्स संग्रह में सम्मिलित करता है। |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | शेप्स संग्रह से निर्दिष्ट शेप की पहली उपस्थिति को हटाता है। |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | निर्दिष्ट अनुक्रमांक पर शेप को शेप्स संग्रह से हटाता है। |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | निर्दिष्ट शेप को शेप्स संग्रह के भीतर नई स्थिति में ले जाता है। |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | निर्दिष्ट शेप्स को शेप्स संग्रह के भीतर ले जाता है, उन्हें दिए गए अनुक्रमांक से शुरू होकर रखते हुए। |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | एक एरे बनाता है जिसमें सभी शेप्स होते हैं और उसे लौटाता है। |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | एक एरे बनाता है जिसमें निर्दिष्ट रेंज में सभी शेप्स होते हैं और उसे लौटाता है। |

### देखें

* क्लास [DomObject&lt;TParent&gt;](../domobject-1)
* क्लास [GroupShape](../groupshape)
* इंटरफ़ेस [IShapeCollection](../ishapecollection)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->