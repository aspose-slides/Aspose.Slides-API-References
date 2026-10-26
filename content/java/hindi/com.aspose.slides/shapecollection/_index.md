---
title: ShapeCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: आकारों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/shapecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

आकारों के संग्रह का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | एक नया SmartArt डायग्राम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक नया ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | एक नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | पूर्वनिर्धारित छवि के साथ नया ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | पूर्वनिर्धारित छवि के साथ नया सेक्शन ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | पूर्वनिर्धारित छवि के साथ नया सेक्शन ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | एक नया समरी ज़ूम फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | एक नया समरी ज़ूम फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में सम्मिलित करता है। |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD ट्रैक से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD ट्रैक से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | बाहरी ऑडियो फ़ाइल से जुड़ा नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल वाले नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल वाले नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | संग्रह में निर्दिष्ट आकार की पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| [toArray()](#toArray--) | एक एरे बनाता है और लौटाता है जिसमें सभी आकार होते हैं। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा में सभी आकारों को शामिल करने वाला एरे बनाता है और लौटाता है। |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | निर्दिष्ट आकार को आकार संग्रह के भीतर नई स्थिति में ले जाता है। |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | निर्दिष्ट इंडेक्स से शुरू करके निर्दिष्ट आकारों को आकार संग्रह के भीतर पुनः क्रमित करता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | डिफ़ॉल्ट फॉर्मेटिंग के साथ नया ऑटो शैप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | नया ऑटो शैप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग से प्रारम्भ करता है। |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | गणितीय सामग्री रखने के लिए नया आयताकार ऑटो शैप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | नया ऑटो शैप बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | नया ऑटो शैप बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग से प्रारम्भ करता है। |
| [addGroupShape()](#addGroupShape--) | नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकारों में परिवर्तित करता है, और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है। |
| [insertGroupShape(int index)](#insertGroupShape-int-) | नया खाली समूह आकार बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करता है। |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि वाला नया तस्वीर फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि वाला नया तस्वीर फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | नया टेबल बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | नया टेबल बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर आकार को आकार संग्रह से हटाता है। |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | निर्दिष्ट आकार की पहली उपस्थिति को आकार संग्रह से हटाता है। |
| [clear()](#clear--) | सभी आकारों को आकार संग्रह से हटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एक इनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए एक java इटरेटर लौटाता है। |
| [getParentGroup()](#getParentGroup--) | आकार संग्रह के लिए पैरेंट समूह आकार ऑब्जेक्ट प्राप्त करता है। |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | निर्दिष्ट आकार की एक प्रतिलिपि बनाता है और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह इंगित करने वाला मान लौटाता है कि संग्रह तक पहुँच समकालिक (thread-safe) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समकालिकता रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int .

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IShape](../../com.aspose.slides/ishape).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX फ़ाइल को दर्शाने वाली Presentation क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // अपने डिफ़ॉल्ट डेटा के साथ एक चार्ट जोड़ता है
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // चार्ट शीर्षक सेट करता है
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // पहली सीरीज़ को मान दिखाने के लिए सेट करता है
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // चार्ट डेटा शीट के लिए इंडेक्स सेट करता है
>      int defaultWorksheetIndex = 0;
>      // चार्ट डेटा वर्कशीट प्राप्त करता है
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // डिफ़ॉल्ट उत्पन्न सीरीज़ और श्रेणियों को हटा देता है
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // नई सीरीज़ जोड़ता है
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // नई श्रेणियां जोड़ता है
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // पहली चार्ट सीरीज़ लेता है
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // सीरीज़ डेटा भरता है
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // सीरीज़ के लिए भराव रंग सेट करता है
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // दूसरी चार्ट सीरीज़ लेता है
>      series = chart.getChartData().getSeries().get_Item(1);
>      // सीरीज़ डेटा भरता है
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // सीरीज़ के लिए भराव रंग सेट करता है
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // पहले लेबल को श्रेणी का नाम दिखाने के लिए सेट करता है
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // तीसरे लेबल के लिए मान दिखाने हेतु सीरीज़ सेट करता है
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // PPTP फ़ाइल को डिस्क पर सहेजता है
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | float | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | float | चार्ट की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | float | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | float | चार्ट की ऊँचाई, पॉइंट्स में। |
| initWithSample | boolean | true होने पर नया चार्ट नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ होगा; false होने पर चार्ट बिना श्रृंखला और न्यूनतम सेटिंग्स के बनाया जाएगा, जिससे निर्माण तेज़ होता है। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

एक नया SmartArt डायग्राम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | डायग्राम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | डायग्राम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | डायग्राम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | डायग्राम फ्रेम की ऊँचाई, पॉइंट्स में। |
| layoutType | int | SmartArt लेआउट प्रकार। |

**रिटर्न:**  
[ISmartArt](../../com.aspose.slides/ismartart) - नया बनाया गया [ISmartArt](../../com.aspose.slides/ismartart)।

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | float | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | int | शून्य-आधारित इंडेक्स जहाँ नया चार्ट आकार संग्रह में सम्मिलित किया जाएगा। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारम्भ करता है, और इसे निर्दिष्ट इंडेक्स पर आकार संग्रह में सम्मिलित करता है।
| x | float | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | float | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | int | शेप कलेक्शन में नए चार्ट को डालने का शून्य-आधारित इंडेक्स। |
| initWithSample | boolean | नए चार्ट को सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारम्भ करने के लिए true; बिना सीरीज़ के और केवल न्यूनतम सेटिंग्स के साथ चार्ट बनाने के लिए false, जिससे निर्माण तेज़ होता है। |

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart) - नया निर्मित [IChart](../../com.aspose.slides/ichart)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

एक नया ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | ज़ूम फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह इस प्रस्तुति का हिस्सा होना चाहिए। |

**रिटर्न:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में ज़ूम ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | ज़ूम फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह इस प्रस्तुति का हिस्सा होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए छवि। |

**रिटर्न:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

एक नया ज़ूम फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | ज़ूम फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | ज़ूम फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |

**रिटर्न:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया ज़ूम फ्रेम को प्री-डिफ़ाइन्ड छवि के साथ बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में निर्दिष्ट इंडेक्स पर ज़ूम ऑब्जेक्ट बनाना और डालना दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | ज़ूम फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | ज़ूम फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए छवि। |

**रिटर्न:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

एक नया सेक्शन ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में सेक्शन ज़ूम ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए सेक्शन ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए सेक्शन ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए सेक्शन ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए सेक्शन ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | सेक्शन ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |

**रिटर्न:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

एक नया सेक्शन ज़ूम फ्रेम को प्री-डिफ़ाइन्ड छवि के साथ बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में सेक्शन ज़ूम ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए सेक्शन ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए सेक्शन ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए सेक्शन ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए सेक्शन ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | सेक्शन ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | सेक्शन ज़ूम फ्रेम के भीतर प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**रिटर्न:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

एक नया सेक्शन ज़ूम फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में निर्दिष्ट इंडेक्स पर सेक्शन ज़ूम ऑब्जेक्ट बनाना और डालना दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | सेक्शन ज़ूम फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए सेक्शन ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए सेक्शन ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए सेक्शन ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए सेक्शन ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | सेक्शन ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |

**रिटर्न:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

एक नया सेक्शन ज़ूम फ्रेम को प्री-डिफ़ाइन्ड छवि के साथ बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में निर्दिष्ट इंडेक्स पर सेक्शन ज़ूम ऑब्जेक्ट बनाने और डालने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | सेक्शन ज़ूम फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नया सेक्शन ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नया सेक्शन ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नया सेक्शन ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नया सेक्शन ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | सेक्शन ज़ूम फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | सेक्शन ज़ूम फ्रेम के भीतर प्रदर्शित करने के लिए छवि। |

**रिटर्न:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}  
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

एक नया समरी ज़ूम फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नया समरी ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नया समरी ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नया समरी ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नया समरी ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |

यह मेथड एक नया समरी ज़ूम बनाता है और इस प्रस्तुति के सभी सेक्शन के लिए ऑब्जेक्ट्स का संग्रह इसमें रखता है। |

**रिटर्न:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नया निर्मित [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}  
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

एक नया समरी ज़ूम फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह में निर्दिष्ट इंडेक्स पर एक Summary Zoom ऑब्जेक्ट बनाना और डालना दर्शाता है
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | समरी ज़ूम फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नया समरी ज़ूम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नया समरी ज़ूम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नया समरी ज़ूम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नया समरी ज़ूम फ्रेम की ऊँचाई, पॉइंट्स में। |

यह मेथड एक समरी ज़ूम फ्रेम बनाता है जो प्रस्तुति के सभी सेक्शन के लिए समरी लिंक को एकत्रित करता है। |

**रिटर्न:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नया निर्मित [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

--------------------

> ```
> निम्न उदाहरण दर्शाते हैं कि PowerPoint प्रस्तुति की स्लाइड्स में OLE ऑब्जेक्ट फ्रेम कैसे जोड़े जाएँ।
>  
>  // PPTX को दर्शाने वाली Presentation क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try
>  {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // स्ट्रीम में एक Excel फ़ाइल लोड करता है
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // एम्बेडिंग के लिए डेटा ऑब्जेक्ट बनाता है
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // एक Ole ऑब्जेक्ट फ्रेम शैल जोड़ता है
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // PPTX को डिस्क पर सहेजता है
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा की जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**रिटर्न:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पाथ।

यह पाथ प्रस्तुति में जैसा है वैसा ही संग्रहीत किया जाता है। यदि किसी रिलेटिव पाथ को निर्दिष्ट किया गया है, तो किसी अन्य डायरेक्टरी से प्रस्तुति खोलते समय फ़ाइल अप्राप्य होगी। |

**रिटर्न:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | OLE ऑब्जेक्ट फ्रेम को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एंबेडेड OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**रिटर्न:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | OLE ऑब्जेक्ट फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पथ। यह पथ प्रस्तुति में वैसा ही संग्रहित किया जाता है। यदि सापेक्ष पथ निर्दिष्ट किया जाता है, तो फ़ाइल अलग डायरेक्ट्री से प्रस्तुति खोलते समय पहुँचा नहीं जा सकेगा। |

**रिटर्न:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया बनाया गया OLE ऑब्जेक्ट फ्रेम।

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए वीडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एंबेड करने के लिए वीडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

एक नया वीडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए वीडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ्रेम की ऊँचाई, पॉइंट में। |
| video | [IVideo](../../com.aspose.slides/ivideo) | वीडियो फ्रेम में एंबेड करने के लिए [IVideo](../../com.aspose.slides/ivideo)। |

**रिटर्न:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वीडियो फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए वीडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एंबेड करने के लिए वीडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नया बनाया गया [IVideoFrame](../../com.aspose.slides/ivideoframe)।

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा होता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ऑडियो फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और इसे शेप कलेक्शन के अंत में जोड़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ऑडियो फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फाइल हो और इसे शेप कलेक्शन के अंत में जोड़ता है। एम्बेडेड ऑडियो को Presentation.Audios कलेक्शन में जोड़ा जाता है।

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली प्रस्तुति क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड प्राप्त करता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav ध्वनि फ़ाइल को स्ट्रीम में लोड करता है
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // ऑडियो फ्रेम जोड़ता है
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // ऑडियो के प्ले मोड और वॉल्यूम सेट करता है
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // PowerPoint फ़ाइल को डिस्क पर सहेजता है
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | एम्बेड करने के लिए WAV ऑडियो डेटा वाली एक इनपुट स्ट्रीम। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फाइल हो और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है। एम्बेडेड ऑडियो को Presentation.Audios कलेक्शन में जोड़ा जाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ऑडियो फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | एम्बेड करने के लिए WAV ऑडियो डेटा वाली एक इनपुट स्ट्रीम। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios कलेक्शन से एक [IAudio](../../com.aspose.slides/iaudio) उदाहरण। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप कलेक्शन में सम्मिलित करता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ऑडियो फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | नए ऑडियो फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | एम्बेड करने के लिए Presentation.Audios कलेक्शन का एक [IAudio](../../com.aspose.slides/iaudio) उदाहरण। |

**रिटर्न:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नया बनाया गया [IAudioFrame](../../com.aspose.slides/iaudioframe)।

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

निर्दिष्ट आकार की संग्रह में पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | संग्रह में खोजने के लिए आकार। |

**रिटर्न:**  
int - यदि पाया गया तो shape collection में आकार की पहली उपस्थिति का शून्य-आधारित इंडेक्स; अन्यथा, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

सभी आकारों को सम्मिलित करने वाला एक एरे बनाता और लौटाता है।

**रिटर्न:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स का एरे।

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

निर्दिष्ट रेंज में सभी आकारों को सम्मिलित करने वाला एक एरे बनाता और लौटाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | पहला आकार लौटाने का इंडेक्स। |
| count | int | वापसी में आकारों की संख्या। |

**रिटर्न:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स का एरे।

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

निर्दिष्ट आकार को शेप कलेक्शन में नई स्थिति पर ले जाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित लक्ष्य इंडेक्स जहाँ आकार रखा जाएगा। |
| shape | [IShape](../../com.aspose.slides/ishape) | कलेक्शन में ले जाने वाला [IShape](../../com.aspose.slides/ishape)। |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

निर्दिष्ट आकारों को शेप कलेक्शन में ले जाता है, उन्हें दिए गए इंडेक्स से शुरू करके रखा जाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित लक्ष्य इंडेक्स जहाँ पहला निर्दिष्ट आकार रखा जाएगा; बाद के आकार प्रदान किए क्रम में रखे जाएंगे। |
| आकार | [IShape\[\]](../../com.aspose.slides/ishape) | संग्रह के भीतर ले जाने के लिए एक या अधिक [IShape](../../com.aspose.slides/ishape) उदाहरण। |
### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

एक नया ऑटो आकार बनाता है जिसमें डिफॉल्ट फ़ॉर्मेटिंग है और इसे आकार संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए ऑटो आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | आकार के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | आकार के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | आकार के फ़्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ आरंभ करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए ऑटो आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | आकार के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | आकार के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | आकार के फ़्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर नई आकार को डिफॉल्ट टेम्प्लेट स्टाइल (सादा स्टाइल, केंद्रित टेक्स्ट, और खाली नहीं नाम) लागू करता है; false होने पर सभी गुण डिफॉल्ट मानों के साथ बनाता है। |

**वापसी:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

गणितीय सामग्री रखने के लिए एक नया आयताकार ऑटो आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

--------------------

> ```
> निम्न उदाहरण दर्शाता है कि PowerPoint प्रस्तुति में गणितीय समीकरण कैसे जोड़ें।
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | आकार के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | आकार के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | आकार के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | आकार के फ़्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

एक नया ऑटो आकार बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है, डिफॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ नया ऑटो आकार सम्मिलित किया जाएगा। |
| shapeType | int | सम्मिलित करने के लिए ऑटो आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | आकार के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | आकार के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | आकार के फ़्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया ऑटो आकार बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफॉल्ट टेम्प्लेट स्टाइल के साथ आरंभ करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ ऑटो आकार सम्मिलित किया जाएगा। |
| shapeType | int | सम्मिलित करने के लिए ऑटो आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | आकार के फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | आकार के फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | आकार के फ़्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफॉल्ट टेम्प्लेट स्टाइल (खाली नहीं नाम, सादा स्टाइल, केंद्रित टेक्स्ट) लागू करता है; false होने पर सभी गुण डिफॉल्ट मानों के साथ बनाता है। |

**वापसी:**
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape)।
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

एक नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वतः ही जोड़े गए आकारों के अनुसार समायोजित हो जाएगा।

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Presentation क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड प्राप्त करता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // स्लाइड्स के शेप कलेक्शन तक पहुँच रहा है
>      IShapeCollection slideShapes = sld.getShapes();
>      // स्लाइड में एक ग्रुप शेप जोड़ रहा है
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // जोड़े गए ग्रुप शेप के अंदर शेप्स जोड़ रहा है
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // ग्रुप शेप फ्रेम जोड़ रहा है
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX फ़ाइल को डिस्क पर लिखता है
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

एक नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकारों में परिवर्तित करता है, और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | वह [ISvgImage](../../com.aspose.slides/isvgimage) जिसमें वेक्टर सामग्री है, जिसे आकारों में बदलना है। |
| x | float | समूह के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | समूह के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | समूह के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | समूह के फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

एक नया खाली समूह आकार बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है। समूह का फ्रेम स्वतः ही जोड़े गए आकारों के अनुसार समायोजित हो जाएगा।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ समूह आकार सम्मिलित किया जाएगा। |

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape)।
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

डिफॉल्ट टेम्प्लेट स्टाइल के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण दर्शाता है कि PowerPoint प्रस्तुति में दो आकारों (एक अंडाकृति और आयत) के बीच कनेक्टर (एक मोड़ा हुआ कनेक्टर) कैसे जोड़ें।
>  
>  // PPTX फ़ाइल को दर्शाने वाली प्रस्तुति क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // किसी विशिष्ट स्लाइड के लिए शैप कलेक्शन तक पहुँचता है
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Ellipse ऑटोशेप जोड़ता है
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Rectangle ऑटोशेप जोड़ता है
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // स्लाइड शैप कलेक्शन में कनेक्टर आकार जोड़ता है
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // कनेक्टर का उपयोग करके आकारों को जोड़ता है
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // reroute को कॉल करता है जो आकारों के बीच स्वचालित सबसे छोटा मार्ग सेट करता है
>      connector.reroute();
>      // प्रस्तुति को सहेजता है
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए कनेक्टर आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफॉल्ट टेम्प्लेट स्टाइल लागू करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | बनाने के लिए कनेक्टर आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफॉल्ट टेम्प्लेट स्टाइल (खाली नहीं नाम, सादा स्टाइल) लागू करता है; false होने पर डिफॉल्ट गुण मानों के साथ कनेक्टर बनाता है। |

**वापसी:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

एक नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है, डिफॉल्ट टेम्प्लेट स्टाइल लागू करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ कनेक्टर आकार सम्मिलित किया जाएगा। |
| shapeType | int | सम्मिलित करने के लिए कनेक्टर आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट में। |

**वापसी:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया कनेक्टर आकार बनाता है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफॉल्ट टेम्प्लेट स्टाइल लागू करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ कनेक्टर आकार सम्मिलित किया जाएगा। |
| shapeType | int | सम्मिलित करने के लिए कनेक्टर आकार का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट में। |
| createFromTemplate | boolean | true होने पर डिफॉल्ट टेम्प्लेट स्टाइल (खाली नहीं नाम, सादा स्टाइल) लागू करता है; false होने पर डिफॉल्ट गुण मानों के साथ कनेक्टर बनाता है। |

**वापसी:**
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector)।
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट छवि को शामिल करने वाला एक नया चित्र फ़्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में धँसे आकार प्रकार को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | चित्र फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | चित्र फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | चित्र फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | चित्र फ़्रेम की ऊँचाई, पॉइंट में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | चित्र फ़्रेम में प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe)।
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

एक नया चित्र फ़्रेम बनाता है जिसमें निर्दिष्ट छवि होती है और इसे निर्दिष्ट अनुक्रमणिका पर आकार संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ चित्र फ़्रेम सम्मिलित किया जाएगा। |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में धँसे आकार प्रकार को निर्दिष्ट करता है, सभी प्रकार की रेखाओं को छोड़कर: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | चित्र फ़्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | चित्र फ़्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | चित्र फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | चित्र फ़्रेम की ऊँचाई, पॉइंट में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | चित्र फ़्रेम में प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe)।
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

एक नया तालिका बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

--------------------

> ```
> निम्न उदाहरण दर्शाते हैं कि PowerPoint प्रस्तुति में तालिका कैसे जोड़ें।
>  
>  // PPTX फ़ाइल को दर्शाने वाली Presentation क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try
>  {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // स्तंभों को चौड़ाई और पंक्तियों को ऊँचाई के साथ परिभाषित करता है
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // स्लाइड में तालिका आकार जोड़ता है
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // प्रत्येक सेल के लिए बॉर्डर फ़ॉर्मेट सेट करता है
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // पंक्ति 1 की सेल 1 और 2 को मिलाता है
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // मर्ज किए गए सेल में टेक्स्ट जोड़ता है
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX को डिस्क पर सहेजता है
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | टेबल का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | टेबल का y-कोऑर्डिनेट, पॉइंट्स में। |
| columnWidths | double[] | डबल्स की एक array जो टेबल के कॉलमों की चौड़ाइयों को दर्शाती है, पॉइंट्स में। |
| rowHeights | double[] | डबल्स की एक array जो टेबल की पंक्तियों की ऊँचाइयों को दर्शाती है, पॉइंट्स में। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - नया बनाया गया [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```


एक नया टेबल बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | जिस शून्य-आधारित इंडेक्स पर टेबल को सम्मिलित करना है। |
| x | float | टेबल का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | टेबल का y-कोऑर्डिनेट, पॉइंट्स में। |
| columnWidths | double[] | डबल्स की एक array जो टेबल के कॉलमों की चौड़ाइयों को दर्शाती है, पॉइंट्स में। |
| rowHeights | double[] | डबल्स की एक array जो टेबल की पंक्तियों की ऊँचाइयों को दर्शाती है, पॉइंट्स में। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - नया बनाया गया [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर shape संग्रह से shape को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए shape का शून्य-आधारित इंडेक्स। |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```


निर्दिष्ट shape की पहली आवृति को shape संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | हटाने के लिए [IShape](../../com.aspose.slides/ishape)। |

### clear() {#clear--}
```
public final void clear()
```


shape संग्रह से सभी shapes को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - एक IGenericEnumerator जो संग्रह के माध्यम से पुनरावृत्ति के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```


पूरे संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - एक java.util.Iterator for the entire collection.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


shapes संग्रह के लिए पैरेंट ग्रुप shape ऑब्जेक्ट प्राप्त करता है। केवल-पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**रिटर्न:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


निर्दिष्ट shape की एक कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए shape। |
| x | float | नई shape के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | नई shape के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | float | नई shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नई shape के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```


निर्दिष्ट shape की कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। नई shape स्रोत shape की चौड़ाई और ऊँचाई बनाए रखती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए shape। |
| x | float | नई shape के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | नई shape के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```


निर्दिष्ट shape की कॉपी बनाता है और इसे shape संग्रह के अंत में जोड़ता है। क्लोन की गई shape मूल की स्थिति और आकार को बनाए रखती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


निर्दिष्ट shape की कॉपी बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन की गई shape को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन की गई shape के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | क्लोन की गई shape के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | float | क्लोन की गई shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | क्लोन की गई shape के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```


निर्दिष्ट shape की कॉपी बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। नई shape स्रोत shape की चौड़ाई और ऊँचाई बनाए रखती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन की गई shape को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन की गई shape के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | float | क्लोन की गई shape के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```


निर्दिष्ट shape की कॉपी बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। क्लोन की गई shape मूल की स्थिति और आकार को बनाए रखती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | क्लोन की गई shape को सम्मिलित करने के लिए शून्य-आधारित इंडेक्स। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नया बनाया गया [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह से सभी तत्वों को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ़) है या नहीं इसे दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य  boolean .

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक synchronization root लौटाता है। केवल-पढ़ने योग्य  Object .

**रिटर्न:**
java.lang.Object