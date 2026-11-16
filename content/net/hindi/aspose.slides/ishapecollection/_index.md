---
title: IShapeCollection
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: शेप्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
weight: 7000
url: /hi/aspose.slides/ishapecollection/
---
## IShapeCollection इंटरफ़ेस

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पढ़ने-योग्य [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | शेप्स कलेक्शन के लिए पैरेंट ग्रुप शेप ऑब्जेक्ट प्राप्त करता है। केवल-पढ़ने-योग्य [`IGroupShape`](../igroupshape). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | एक नया ऑडियो फ़्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | एक नया ऑडियो फ़्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ़्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios कलेक्शन में जोड़ा जाता है। |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | एक नया ऑडियो फ़्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा होता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ नया ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | एक नया ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग से आरंभ करता है। |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से आरंभ करता है, और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से आरंभ करता है, और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। क्लोन किया गया शेप मूल की स्थिति और आकार को बरकरार रखता है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। नया शेप *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | एक नया खाली ग्रुप शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। ग्रुप का फ्रेम स्वचालित रूप से उसके भीतर जोड़े गए किसी भी शेप को फिट करने के लिए समायोजित होगा। |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | एक नया ग्रुप शेप बनाता है, निर्दिष्ट SVG इमेज को व्यक्तिगत शेप्स में बदलता है, और परिणामी ग्रुप को शेप कलेक्शन के अंत में जोड़ता है। |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | गणितीय सामग्री रखने के लिए नया आयताकार ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट इमेज सहित नया पिक्चर फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | एक नया सेक्शन जूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | एक पूर्वनिर्धारित इमेज के साथ नया सेक्शन जूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | एक SmartArt डायग्राम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | एक नया समरी जूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | एक नया टेबल बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | एक नया वीडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | एक नया ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | एक नया ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। |
| [Clear](../../aspose.slides/ishapecollection/clear)() | शेप कलेक्शन से सभी शेप्स हटाता है। |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | कलेक्शन में निर्दिष्ट शेप की पहली घटना का शून्य-आधारित अनुक्रमणिका लौटाता है। |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | एक नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके। |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | एक एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। एम्बेडेड ऑडियो Presentation.Audios कलेक्शन में जोड़ा जाता है। |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा होता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है। |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग से आरंभ करता है। |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से आरंभ करता है, और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से आरंभ करता है, और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। क्लोन किया गया शेप मूल की स्थिति और आकार को बरकरार रखता है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। नया शेप *sourceShape* की चौड़ाई और ऊँचाई को बरकरार रखता है। |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | निर्दिष्ट शेप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है, डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | एक नया कनेक्टर शेप बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | एक नया खाली ग्रुप शेप बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। ग्रुप का फ्रेम स्वचालित रूप से उसके भीतर जोड़े गए किसी भी शेप को फिट करने के लिए समायोजित होगा। |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | निर्दिष्ट इमेज सहित नया पिक्चर फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | एक नया सेक्शन जूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | एक पूर्वनिर्धारित इमेज के साथ नया सेक्शन जूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | एक नया समरी जूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | एक नया टेबल बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | एक नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | एक नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | एक पूर्वनिर्धारित इमेज के साथ नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर शेप कलेक्शन में डालता है। |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | निर्दिष्ट शेप की पहली घटना को शेप कलेक्शन से हटाता है। |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | निर्दिष्ट अनुक्रमणिका पर शेप को शेप कलेक्शन से हटाता है। |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | निर्दिष्ट शेप को शेप कलेक्शन के भीतर नई स्थिति में ले जाता है। |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | निर्दिष्ट शेप्स को शेप कलेक्शन के भीतर ले जाता है, उन्हें दिए गए अनुक्रमणिका से शुरू करके रखता है। |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | सभी शेप्स को शामिल करने वाला एक एरे बनाता और लौटाता है। |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | निर्दिष्ट सीमा में सभी शेप्स को शामिल करने वाला एक एरे बनाता और लौटाता है। |

### संबंधित देखें

* इंटरफ़ेस [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* इंटरफ़ेस [IShape](../ishape)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->