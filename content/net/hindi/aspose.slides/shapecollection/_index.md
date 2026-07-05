---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API संदर्भ
description: आकारों का एक संग्रह दर्शाता है।
type: docs
weight: 9860
url: /hi/aspose.slides/shapecollection/
---
## ShapeCollection क्लास

आकारों के संग्रह का प्रतिनिधित्व करता है।

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | कॉल्शन में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | कॉल्शन तक पहुंच समक्रमित (थ्रेड-सेफ़) है या नहीं, यह दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | आकार संग्रह के लिए पैरेंट ग्रुप शीप ऑब्जेक्ट प्राप्त करता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य Object. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से लिंक्ड होता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | एक नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे आकार संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है। |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से लिंक्ड होता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो शेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | एक नया ऑटो शेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग से इनिशियलाइज़ करता है। |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज डेटा और सेटिंग्स के साथ इनिशियलाइज़ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज डेटा और सेटिंग्स के साथ इनिशियलाइज़ करता है, और वैकल्पिक रूप से इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। क्लोन किया गया आकार मूल की स्थिति और आकार को बरकरार रखता है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। नया आकार *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | एक नया खाली ग्रुप आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। ग्रुप का फ्रेम किसी भी जोड़े गए आकार को फिट करने के लिए स्वचालित रूप से समायोजित होगा। |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | एक नया ग्रुप आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकारों में परिवर्तित करता है, और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है। |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | गणितीय सामग्री को रखने के लिए एक नया आयताकार ऑटो शेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि को शामिल करने वाला एक नया पिक्चर फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | पूर्वनिर्धारित छवि के साथ एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | एक SmartArt डायग्राम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | एक नया सारांश ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | एक नई टेबल बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [Clear](../../aspose.slides/shapecollection/clear)() | आकार संग्रह से सभी आकार हटाता है। |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | एक एनोमेरेटर लौटाता है जो संग्रह को पारित करता है। |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | संग्रह में निर्दिष्ट आकार की पहली उपस्थिति का शून्य-आधारित अनुक्रमांक लौटाता है। |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से लिंक्ड होता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | एक नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल होती है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है। |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से लिंक्ड होता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है। |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग से इनिशियलाइज़ करता है। |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज डेटा और सेटिंग्स से इनिशियलाइज़ करता है, और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | एक नया चार्ट बनाता है, इसे सैंपल सीरीज डेटा और सेटिंग्स से इनिशियलाइज़ करता है, और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। क्लोन किया गया आकार मूल की स्थिति और आकार को बरकरार रखता है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। नया आकार *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | निर्दिष्ट आकार की एक कॉपी बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | एक नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | एक नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | एक नया खाली ग्रुप आकार बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। ग्रुप का फ्रेम किसी भी जोड़े गए आकार को फिट करने के लिए स्वचालित रूप से समायोजित होगा। |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट छवि को शामिल करने वाला एक नया पिक्चर फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | पूर्वनिर्धारित छवि के साथ एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | एक नया सारांश ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | एक नई टेबल बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | एक नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | पूर्वनिर्धारित छवि के साथ एक नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमांक पर आकार संग्रह में सम्मिलित करता है। |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | निर्दिष्ट आकार की पहली उपस्थिति को आकार संग्रह से हटाता है। |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | निर्दिष्ट अनुक्रमांक पर आकार को आकार संग्रह से हटाता है। |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | निर्दिष्ट आकार को आकार संग्रह में नई स्थिति पर ले जाता है। |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | निर्दिष्ट आकारों को आकार संग्रह में ले जाता है, उन्हें दिए गए अनुक्रमांक से शुरू करके रखता है। |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | एक एरे बनाता और लौटाता है जिसमें सभी आकार सम्मिलित होते हैं। |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | एक एरे बनाता और लौटाता है जिसमें निर्दिष्ट रेंज के सभी आकार सम्मिलित होते हैं। |

### संबंधित देखें

* क्लास [DomObject&lt;TParent&gt;](../domobject-1)
* क्लास [GroupShape](../groupshape)
* इंटरफ़ेस [IShapeCollection](../ishapecollection)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->