---
title: IShapeCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: shapes के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ishapecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

shapes के संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [getParentGroup()](#getParentGroup--) | shapes संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape संग्रह के अंत में जोड़ता है। |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape संग्रह के अंत में जोड़ता है। |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | एक नया SmartArt डायग्राम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक नया Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | एक नया video फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | एक नया video फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | एक नया video फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD ट्रैक से जुड़ा नया audio फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD ट्रैक से जुड़ा नया audio फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | बाहरी audio फ़ाइल से जुड़ा नया audio फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | बाहरी audio फ़ाइल से जुड़ा नया audio फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल के साथ नया audio फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूदा audio ऑब्जेक्ट का उपयोग करके नया audio फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल के साथ नया audio फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूदा audio ऑब्जेक्ट का उपयोग करके नया audio फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | संग्रह में निर्दिष्ट shape की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है। |
| [toArray()](#toArray--) | सभी shapes को शामिल करने वाला array बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा में सभी shapes को शामिल करने वाला array बनाता और लौटाता है। |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | निर्दिष्ट shape को shape संग्रह में नई स्थिति पर ले जाता है। |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | निर्दिष्ट shape को shape संग्रह में स्थानांतरित करता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ नया auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | नया auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है। |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | गणितीय सामग्री रखने के लिए नया rectangle auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ प्रारंभ करता है। |
| [addGroupShape()](#addGroupShape--) | नया खाली group shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | नया group shape बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत shapes में बदलता है, और परिणत समूह को shape संग्रह के अंत में जोड़ता है। |
| [insertGroupShape(int index)](#insertGroupShape-int-) | नया खाली group shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया connector shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | नया connector shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | नया connector shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | नया connector shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि को शामिल करने वाला नया picture फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि को शामिल करने वाला नया picture फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | नया table बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | नया table बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर shape को shape संग्रह से हटा देता है। |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | निर्दिष्ट shape की पहली उपस्थिति को shape संग्रह से हटा देता है। |
| [clear()](#clear--) | shape संग्रह से सभी shapes को हटा देता है। |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने-योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

shapes संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। केवल-पढ़ने-योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**वापसी मान:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट में। |
| width | float | chart की चौड़ाई, पॉइंट में। |
| height | float | chart की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट में। |
| width | float | chart की चौड़ाई, पॉइंट में। |
| height | float | chart की ऊँचाई, पॉइंट में। |
| initWithSample | boolean | true होने पर chart को नमूना series डेटा और सेटिंग्स के साथ प्रारंभ किया जाता है; false होने पर chart बिना किसी series और न्यूनतम सेटिंग्स के बनाया जाता है, जिससे निर्माण तेज़ होता है। |

**वापसी मान:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

एक SmartArt डायग्राम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | डायग्राम फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | डायग्राम फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | डायग्राम फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | डायग्राम फ्रेम की ऊँचाई, पॉइंट में। |
| layoutType | int | SmartArt लेआउट प्रकार। |

**वापसी मान:**
[ISmartArt](../../com.aspose.slides/ismartart) - नया बनाया गया [ISmartArt](../../com.aspose.slides/ismartart)।

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिए chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट में। |
| width | float | नए chart की चौड़ाई, पॉइंट में। |
| height | float | नए chart की ऊँचाई, पॉइंट में। |
| index | int | शून्य-आधारित सूचकांक जहाँ नया chart shape संग्रह में सम्मिलित किया जाएगा। |

**वापसी मान:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

एक नया chart बनाता है, इसे नमूना series डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिए chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट में। |
| width | float | नए chart की चौड़ाई, पॉइंट में। |
| height | float | नए chart की ऊँचाई, पॉइंट में। |
| index | int | शून्य-आधारित सूचकांक जहाँ नया chart shape संग्रह में सम्मिलित किया जाएगा। |
| initWithSample | boolean | true होने पर chart को नमूना series डेटा और सेटिंग्स के साथ प्रारंभ किया जाता है; false होने पर chart बिना series के और न्यूनतम सेटिंग्स के बनाया जाता है, जिससे निर्माण तेज़ होता है। |

**वापसी मान:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**वापसी मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक की गई फ़ाइल का पथ।

यह पथ प्रस्तुति में जैसा है वैसा संग्रहीत किया जाता है। यदि सापेक्ष पथ निर्दिष्ट किया जाता है, तो अलग निर्देशिका से प्रस्तुति खोलते समय फ़ाइल असुलभ होगी। |

**वापसी मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**वापसी मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक की गई फ़ाइल का पथ।

यह पथ प्रस्तुति में जैसा है वैसा संग्रहीत किया जाता है। यदि सापेक्ष पथ निर्दिष्ट किया जाता है, तो अलग निर्देशिका से प्रस्तुति खोलते समय फ़ाइल असुलभ होगी। |

**वापसी मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में एक Zoom ऑब्जेक्ट जोड़ने का प्रदर्शन करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह प्रस्तुति से संबंधित होना चाहिए। |

**वापसी मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया बनाया गया [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में एक Zoom ऑब्जेक्ट जोड़ने का प्रदर्शन करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह प्रस्तुति से संबंधित होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) के लिए संदर्भित स्लाइड की छवि। |

**वापसी मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया बनाया गया [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में एक Zoom ऑब्जेक्ट को निर्दिष्ट सूचकांक पर बनाना और सम्मिलित करना प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Zoom फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |

**वापसी मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया बनाया गया [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में एक Zoom ऑब्जेक्ट को निर्दिष्ट सूचकांक पर बनाना और सम्मिलित करना प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Zoom फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) की छवि। |

**वापसी मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया बनाया गया [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में एक Section Zoom ऑब्जेक्ट जोड़ने का प्रदर्शन करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |

**वापसी मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया बनाया गया [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में एक Section Zoom ऑब्जेक्ट जोड़ने का प्रदर्शन करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया बनाया गया [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में एक Section Zoom ऑब्जेक्ट को निर्दिष्ट सूचकांक पर बनाना और सम्मिलित करना प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Section Zoom फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |

**वापसी मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया बनाया गया [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में निर्दिष्ट सूचकांक पर एक Section Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Section Zoom फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड रखनी चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने की छवि। |

**वापसी मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया बनाया गया [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

एक नया Summary Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में एक Summary Zoom ऑब्जेक्ट जोड़ने को प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट में।

--------------------

यह विधि प्रेजेंटेशन में सभी सेक्शन के लिए सारांश लिंक को एकत्रित करके Summary Zoom फ्रेम बनाता है। |

**वापसी मान:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नया बनाया गया [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

एक नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में एक Summary Zoom ऑब्जेक्ट को बनाना और निर्दिष्ट सूचकांक पर सम्मिलित करना प्रदर्शित करता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Summary Zoom फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट में।

--------------------

यह विधि प्रेजेंटेशन में सभी सेक्शन के लिए सारांश लिंक को एकत्रित करके Summary Zoom फ्रेम बनाता है। |

**वापसी मान:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नया बनाया गया [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

एक नया video फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए video फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए video फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए video फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए video फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एम्बेड करने के लिए video फ़ाइल का पथ या नाम। |

**वापसी मान:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

एक नया video फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए video फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए video फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए video फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए video फ्रेम की ऊँचाई, पॉइंट में। |
| video | [IVideo](../../com.aspose.slides/ivideo) | video फ्रेम में एम्बेड करने के लिए [IVideo](../../com.aspose.slides/ivideo)। |

**वापसी मान:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

एक नया video फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | video फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए video फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए video फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए video फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए video फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एम्बेड करने के लिए video फ़ाइल का पथ या नाम। |

**वापसी मान:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

एक नया audio फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

एक नया audio फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | audio फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

एक नया audio फ्रेम बनाता है जो बाहरी audio फ़ाइल से जुड़ा होता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी audio फ़ाइल का पथ या नाम। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

एक नया audio फ्रेम बनाता है जो बाहरी audio फ़ाइल से जुड़ा होता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | audio फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी audio फ़ाइल का पथ या नाम। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

एक नया audio फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल शामिल है और इसे shape संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | एम्बेड करने के लिए WAV ऑडियो डेटा वाला इनपुट स्ट्रीम। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

एक नया audio फ्रेम बनाता है और Presentation.Audios सूची से मौजूदा audio ऑब्जेक्ट का उपयोग करके इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) इंस्टेंस। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

एक नया audio फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल शामिल है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | audio फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | एम्बेड करने के लिए WAV ऑडियो डेटा वाला इनपुट स्ट्रीम। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

एक नया audio फ्रेम बनाता है और Presentation.Audios सूची से मौजूदा audio ऑब्जेक्ट का उपयोग करके इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | audio फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | नए audio फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए audio फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए audio फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए audio फ्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) इंस्टेंस जिसे एम्बेड किया जाना है। |

**वापसी मान:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

संग्रह में निर्दिष्ट shape की पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | संग्रह में खोजने के लिए shape। |

**वापसी मान:**
int - यदि shape संग्रह में पाई जाती है तो उसकी पहली उपस्थिति का शून्य-आधारित सूचकांक; अन्यथा \\u20131।

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

सभी shapes को शामिल करने वाला array बनाता और लौटाता है।

**वापसी मान:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स का array।

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा में सभी shapes को शामिल करने वाला array बनाता और लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | वापस करने वाले पहले shape का सूचकांक। |
| count | int | लौटाने वाले shapes की संख्या। |

**वापसी मान:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स का array।

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

निर्दिष्ट shape को shape संग्रह में नई स्थिति पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य शून्य-आधारित सूचकांक जहाँ shape रखा जाएगा। |
| shape | [IShape](../../com.aspose.slides/ishape) | संग्रह में ले जाने के लिए [IShape](../../com.aspose.slides/ishape)। |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

निर्दिष्ट shapes को shape संग्रह में ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | प्रथम निर्दिष्ट shape को रखने का शून्य-आधारित लक्ष्य सूचकांक; बाद के shapes क्रम में लगाए जाएंगे। |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | एक या अधिक [IShape](../../com.aspose.slides/ishape) इंस्टेंस जिन्हें संग्रह में ले जाना है। |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ नया auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ नया auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर नए shape पर डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग (सरल स्टाइल, केंद्रित पाठ, गैर-रिक्त नाम) लागू किया जाता है; false होने पर सभी प्रॉपर्टीज़ को डिफ़ॉल्ट मानों पर सेट करके shape बनाया जाता है। |

**वापसी मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

गणितीय सामग्री रखने के लिए नया rectangle auto shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नया auto shape सम्मिलित करने का शून्य-आधारित सूचकांक। |
| shapeType | int | सम्मिलित करने वाले auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया auto shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नया auto shape सम्मिलित करने का शून्य-आधारित सूचकांक। |
| shapeType | int | सम्मिलित करने वाले auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग (गैर-रिक्त नाम, सरल स्टाइल, केंद्रित पाठ) लागू किया जाता है; false होने पर सभी प्रॉपर्टीज़ को डिफ़ॉल्ट मानों पर सेट करके shape बनाया जाता है। |

**वापसी मान:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

एक नया खाली group shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से जोड़ने वाले किसी भी shape को फिट करने के लिए समायोजित हो जाएगा।

**वापसी मान:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

एक नया group shape बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत shapes में बदलता है, और परिणत समूह को shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | उन वेक्टर सामग्री वाली [ISvgImage](../../com.aspose.slides/isvgimage) जिसे shapes में बदलना है। |
| x | float | समूह फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | समूह फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | समूह फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | समूह फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

एक नया खाली group shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। समूह का फ्रेम स्वचालित रूप से जोड़ने वाले किसी भी shape को फिट करने के लिए समायोजित हो जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | समूह shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |

**वापसी मान:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया connector shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

नया connector shape बनाता है और इसे shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | बनाने वाले connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग (गैर-रिक्त नाम, सरल स्टाइल) लागू किया जाता है; false होने पर डिफ़ॉल्ट प्रॉपर्टी मानों के साथ connector बनाया जाता है। |

**वापसी मान:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया connector shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | connector shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| shapeType | int | सम्मिलित करने वाले connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया connector shape बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | connector shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| shapeType | int | सम्मिलित करने वाले connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग (गैर-रिक्त नाम, सरल स्टाइल) लागू किया जाता है; false होने पर डिफ़ॉल्ट प्रॉपर्टी मानों के साथ connector बनाया जाता है। |

**वापसी मान:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट छवि को शामिल करने वाला नया picture फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में समाहित shape प्रकार को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5। |
| x | float | picture फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | picture फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | picture फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | picture फ्रेम की ऊँचाई, पॉइंट में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture फ्रेम में प्रदर्शित करने वाला [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी मान:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe)।

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट छवि को शामिल करने वाला नया picture फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | picture फ्रेम को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में समाहित shape प्रकार को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5। |
| x | float | picture फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | picture फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | picture फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | picture फ्रेम की ऊँचाई, पॉइंट में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture फ्रेम में प्रदर्शित करने वाला [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी मान:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe)।

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

नया table बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | table का x-निर्देशांक, पॉइंट में। |
| y | float | table का y-निर्देशांक, पॉइंट में। |
| columnWidths | double[] | table के कॉलम की चौड़ाइयों को दर्शाने वाला double एरे, पॉइंट में। |
| rowHeights | double[] | table की पंक्तियों की ऊँचाइयों को दर्शाने वाला double एरे, पॉइंट में। |

**वापसी मान:**
[ITable](../../com.aspose.slides/itable) - नया बनाया गया [ITable](../../com.aspose.slides/itable)।

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

नया table बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | table को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| x | float | table का x-निर्देशांक, पॉइंट में। |
| y | float | table का y-निर्देशांक, पॉइंट में। |
| columnWidths | double[] | table के कॉलम की चौड़ाइयों को दर्शाने वाला double एरे, पॉइंट में। |
| rowHeights | double[] | table की पंक्तियों की ऊँचाइयों को दर्शाने वाला double एरे, पॉइंट में। |

**वापसी मान:**
[ITable](../../com.aspose.slides/itable) - नया बनाया गया [ITable](../../com.aspose.slides/itable)।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट सूचकांक पर shape को shape संग्रह से हटा देता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले shape का शून्य-आधारित सूचकांक। |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

shape संग्रह से निर्दिष्ट shape की पहली उपस्थिति को हटा देता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | हटाने वाले [IShape](../../com.aspose.slides/ishape)। |

### clear() {#clear--}
```
public abstract void clear()
```

shape संग्रह से सभी shapes को हटा देता है।

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला shape। |
| x | float | क्लोन किए गए shape के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए shape के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | क्लोन किए गए shape के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | क्लोन किए गए shape के फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। नया shape sourceShape की चौड़ाई और ऊँचाई को बनाए रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए shape के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए shape के फ्रेम का y-निर्देशांक, पॉइंट में। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। क्लोन किया गया shape मूल की स्थिति और आकार को बनाए रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन किए गए shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए shape के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए shape के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | क्लोन किए गए shape के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | क्लोन किए गए shape के फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। नया shape sourceShape की चौड़ाई और ऊँचाई को बनाए रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन किए गए shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए shape के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए shape के फ्रेम का y-निर्देशांक, पॉइंट में। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

निर्दिष्ट shape की एक कॉपी बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है। क्लोन किया गया shape मूल की स्थिति और आकार को बनाए रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन किए गए shape को सम्मिलित करने का शून्य-आधारित सूचकांक। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |

**वापसी मान:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape)।