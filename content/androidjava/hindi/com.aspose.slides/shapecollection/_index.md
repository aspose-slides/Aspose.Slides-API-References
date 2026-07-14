---
title: ShapeCollection
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: आकारों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/shapecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

एक shape का संग्रह दर्शाता है।  
## Methods  

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और shape संग्रह के अंत में जोड़ता है। |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और shape संग्रह के अंत में जोड़ता है। |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | एक SmartArt डायग्राम बनाता है और उसे shape संग्रह के अंत में जोड़ता है। |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक नया Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि वाला नया Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि वाला नया Section Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि वाला नया Section Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | एक नया वीडियो फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल है और shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूद ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios सूची से मौजूद ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | संग्रह में निर्दिष्ट shape की पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है। |
| [toArray()](#toArray--) | सभी shapes को सम्मिलित करने वाला array बनाता है और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा में सभी shapes को सम्मिलित करने वाला array बनाता है और लौटाता है। |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | निर्दिष्ट shape को shape संग्रह के भीतर नई स्थिति में ले जाता है। |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | निर्दिष्ट shape को shape संग्रह के भीतर ले जाता है, उन्हें दिए गए इंडेक्स से शुरू होते हुए रखता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | डिफ़ॉल्ट फॉर्मेटिंग के साथ एक नया auto shape बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | एक नया auto shape बनाता है और shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट फॉर्मेटिंग से प्रारम्भ करता है। |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | गणितीय सामग्री होस्ट करने के लिए एक नया rectangle auto shape बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | एक नया auto shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट फॉर्मेटिंग लागू करता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | एक नया auto shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग से प्रारम्भ करता है। |
| [addGroupShape()](#addGroupShape--) | एक नया खाली group shape बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | एक नया group shape बनाता है, निर्दिष्ट SVG इमेज को व्यक्तिगत shapes में बदलता है, और परिणामस्वरूप समूह को shape संग्रह के अंत में जोड़ता है। |
| [insertGroupShape(int index)](#insertGroupShape-int-) | एक नया खाली group shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ एक नया connector shape बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | एक नया connector shape बनाता है और shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | एक नया connector shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | एक नया connector shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट इमेज को सम्मिलित करने वाला नया picture frame बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट इमेज को सम्मिलित करने वाला नया picture frame बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | एक नया टेबल बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | एक नया टेबल बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर shape को shape संग्रह से हटाता है। |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | निर्दिष्ट shape की पहली उपस्थिति को shape संग्रह से हटाता है। |
| [clear()](#clear--) | shape संग्रह से सभी shapes को हटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए java iterator लौटाता है। |
| [getParentGroup()](#getParentGroup--) | shapes संग्रह के लिए पैरेंट group shape ऑब्जेक्ट प्राप्त करता है। |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि संग्रह तक पहुँच synchronized (थ्रेड-सेफ़) है या नहीं, इसका मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |

### size() {#size--}  
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने-योग्य `int` ।

**वापसी:**  
int  

### get_Item(int index) {#get-Item-int-}  
```
public final IShape get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने-योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}  
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // उसके डिफ़ॉल्ट डेटा के साथ एक chart जोड़ता है
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // chart शीर्षक सेट करता है
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // पहले series को मान दिखाने के लिये सेट करता है
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // chart डेटा शीट के लिये इंडेक्स सेट करता है
>      int defaultWorksheetIndex = 0;
>      // chart डेटा वर्कशीट प्राप्त करता है
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // डिफ़ॉल्ट जेनरेटेड series और categories को हटाता है
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // नई series जोड़ता है
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // नई categories जोड़ता है
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // पहला chart series लेता है
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // series डेटा भरता है
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // series के लिये fill रंग सेट करता है
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // दूसरा chart series लेता है
>      series = chart.getChartData().getSeries().get_Item(1);
>      // series डेटा भरता है
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // series के लिये fill रंग सेट करता है
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // पहला लेबल Category नाम दिखाने के लिये सेट करता है
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // series को तीसरे लेबल के लिये मान दिखाने के लिये सेट करता है
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिये chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट्स में। |
| width | float | chart की चौड़ाई, पॉइंट्स में। |
| height | float | chart की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IChart](../../com.aspose.slides/ichart) - नव निर्मित [IChart](../../com.aspose.slides/ichart)।  

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}  
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिये chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट्स में। |
| width | float | chart की चौड़ाई, पॉइंट्स में। |
| height | float | chart की ऊँचाई, पॉइंट्स में। |
| initWithSample | boolean | `true` → नमूना series डेटा और सेटिंग्स के साथ प्रारम्भ करे; `false` → कोई series नहीं और न्यूनतम सेटिंग्स के साथ बनायें, जिससे निर्माण तेज़ हो। |

**वापसी:**  
[IChart](../../com.aspose.slides/ichart) - नव निर्मित [IChart](../../com.aspose.slides/ichart)।  

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}  
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

एक SmartArt डायग्राम बनाता है और shape संग्रह के अंत में जोड़ता है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | डायग्राम फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | डायग्राम फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | डायग्राम फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | डायग्राम फ्रेम की ऊँचाई, पॉइंट्स में। |
| layoutType | int | SmartArt लेआउट प्रकार। |

**वापसी:**  
[ISmartArt](../../com.aspose.slides/ismartart) - नव निर्मित [ISmartArt](../../com.aspose.slides/ismartart)।  

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}  
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिये chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट्स में। |
| width | float | chart की चौड़ाई, पॉइंट्स में। |
| height | float | chart की ऊँचाई, पॉइंट्स में। |
| index | int | शून्य-आधारित इंडेक्स जहाँ नया chart सम्मिलित किया जाएगा। |

**वापसी:**  
[IChart](../../com.aspose.slides/ichart) - नव निर्मित [IChart](../../com.aspose.slides/ichart)।  

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}  
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

एक नया chart बनाता है, उसे नमूना series डेटा और सेटिंग्स से प्रारम्भ करता है, और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिये chart का प्रकार। |
| x | float | नए chart का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए chart का y-निर्देशांक, पॉइंट्स में। |
| width | float | chart की चौड़ाई, पॉइंट्स में। |
| height | float | chart की ऊँचाई, पॉइंट्स में। |
| index | int | शून्य-आधारित इंडेक्स जहाँ नया chart सम्मिलित किया जाएगा। |
| initWithSample | boolean | `true` → नमूना series डेटा और सेटिंग्स के साथ प्रारम्भ करे; `false` → कोई series नहीं और न्यूनतम सेटिंग्स के साथ बनायें, जिससे निर्माण तेज़ हो। |

**वापसी:**  
[IChart](../../com.aspose.slides/ichart) - नव निर्मित [IChart](../../com.aspose.slides/ichart)।  

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
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
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह इस प्रस्तुति का हिस्सा होना चाहिए। |

**वापसी:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नव निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।  

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लें कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
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
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह इस प्रस्तुति का हिस्सा होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए इमेज। |

**वापसी:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नव निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।  

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह के निर्दिष्ट इंडेक्स पर Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो स्लाइड हैं):
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
| index | int | शून्य-आधारित इंडेक्स जहाँ Zoom फ्रेम सम्मिलित होगा। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |

**वापसी:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नव निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।  

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}  
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक पूर्वनिर्धारित इमेज वाला नया Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह के निर्दिष्ट इंडेक्स पर Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है
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
| index | int | शून्य-आधारित इंडेक्स जहाँ Zoom फ्रेम सम्मिलित होगा। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए इमेज। |

**वापसी:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - नव निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।  

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में Section Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
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
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होना चाहिए। |

**वापसी:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नव निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।  

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

एक पूर्वनिर्धारित इमेज वाला नया Section Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में Section Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए Section Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ़्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होनी चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने हेतु [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नव निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।  

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह के निर्दिष्ट इंडेक्स पर Section Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है
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
| index | int | शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम सम्मिलित होगा। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होनी चाहिए। |

**वापसी:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नव निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।  

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}  
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

एक पूर्वनिर्धारित इमेज वाला नया Section Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह के निर्दिष्ट इंडेक्स पर Section Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
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
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम सम्मिलित होगा। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होनी चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने हेतु इमेज। |

**वापसी:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नव निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।  

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}  
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

एक नया Summary Zoom फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण संग्रह के अंत में Summary Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
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
| x | float | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |

---  

यह मेथड एक नया Summary Zoom बनाता है और इस प्रस्तुति के सभी सेक्शनों के लिए ऑब्जेक्ट्स का संग्रह इसमें रखता है।  

**वापसी:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नव निर्मित [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।  

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}  
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

एक नया Summary Zoom फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण संग्रह के निर्दिष्ट इंडेक्स पर Summary Zoom ऑब्जेक्ट बनाने और सम्मिलित करने को दर्शाता है
>  (मान लीजिए कि "Presentation.pptx" प्रस्तुति में कम से कम दो सेक्शन हैं):
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
| index | int | शून्य-आधारित इंडेक्स जहाँ Summary Zoom फ्रेम सम्मिलित होगा। |
| x | float | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |

---  

यह मेथड सभी सेक्शनों के लिए सारांश लिंक को सम्मिलित करते हुए एक Summary Zoom फ्रेम बनाता है।  

**वापसी:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नव निर्मित [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)।  

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // PPTX का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टेंटिएट करता है
>  Presentation pres = new Presentation();
>  try
>  {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // एक Excel फ़ाइल को स्ट्रीम में लोड करता है
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
>      // एम्बेड करने हेतु डेटा ऑब्जेक्ट बनाता है
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // एक Ole ऑब्जेक्ट फ्रेम shape जोड़ता है
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
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)) की जानकारी। |

**वापसी:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नव निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।  

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}  
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पथ।  

यह पथ प्रस्तुति में जैसा है वैसा संग्रहीत किया जाता है। यदि सापेक्ष पथ दिया गया है, तो प्रस्तुति को किसी अलग डायरेक्टरी से खोलने पर फ़ाइल पहुँच योग्य नहीं होगी। |

**वापसी:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नव निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।  

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}  
```
public final IOoleObjectFrame 
... (Oops! The response is incorrect; it includes code modifications and an error.)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

--------------------

> ```
> यह उदाहरण दूसरे इंडेक्स पर OLE ऑब्जेक्ट सम्मिलित करने को दर्शाता है:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित होगा। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा की जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**वापसी:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नव निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।  

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}  
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित होगा। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पथ।  

यह पथ प्रस्तुति में जैसा है वैसा संग्रहीत किया जाता है। यदि सापेक्ष पथ दिया गया है, तो प्रस्तुति को किसी अलग डायरेक्टरी से खोलने पर फ़ाइल पहुँच योग्य नहीं होगी। |

**वापसी:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नव निर्मित OLE ऑब्जेक्ट फ्रेम।  

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}  
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | java.lang.String | एम्बेड करने के लिये वीडियो फ़ाइल का पथ या नाम। |

**वापसी:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नव निर्मित [IVideoFrame](../../com.aspose.slides/ivideoframe)।  

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}  
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

एक नया वीडियो फ्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| video | [IVideo](../../com.aspose.slides/ivideo) | फ्रेम में एम्बेड करने के लिये [IVideo](../../com.aspose.slides/ivideo)। |

**वापसी:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नव निर्मित [IVideoFrame](../../com.aspose.slides/ivideoframe)।  

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}  
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ वीडियो फ्रेम सम्मिलित होगा। |
| x | float | नए वीडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए वीडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | वीडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | वीडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | java.lang.String | एम्बेड करने के लिये वीडियो फ़ाइल का पथ या नाम। |

**वापसी:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नव निर्मित [IVideoFrame](../../com.aspose.slides/ivideoframe)।  

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}  
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}  
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम सम्मिलित होगा। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}  
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | java.lang.String | लिंक करने के लिये बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}  
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम सम्मिलित होगा। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| fname | java.lang.String | लिंक करने के लिये बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}  
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल है और shape संग्रह के अंत में जोड़ता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है।

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाली प्रस्तुति क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड प्राप्त करता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav साउंड फ़ाइल को स्ट्रीम में लोड करता है
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
>      // PowerPoint फ़ाइल को डिस्क पर लिखता है
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | java.io.InputStream | एम्बेड करने हेतु WAV ऑडियो डेटा वाला इनपुट स्ट्रीम। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}  
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ्रेम बनाता है जिसमें एम्बेडेड WAV फ़ाइल है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। एम्बेडेड ऑडियो Presentation.Audios संग्रह में जोड़ा जाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम सम्मिलित होगा। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio_stream | java.io.InputStream | एम्बेड करने हेतु WAV ऑडियो डेटा वाला इनपुट स्ट्रीम। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}  
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ्रेम बनाता है और Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) इंस्टेंस। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}  
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है, Presentation.Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ ऑडियो फ्रेम सम्मिलित होगा। |
| x | float | नए ऑडियो फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए ऑडियो फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ऑडियो फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ऑडियो फ्रेम की ऊँचाई, पॉइंट्स में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) इंस्टेंस जिसे एम्बेड करना है। |

**वापसी:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नव निर्मित [IAudioFrame](../../com.aspose.slides/iaudioframe)।  

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}  
```
public final int indexOf(IShape shape)
```

shape संग्रह में निर्दिष्ट shape की पहली उपस्थिति का शून्य-आधारित इंडेक्स लौटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | खोजे जाने वाला shape। |

**वापसी:**  
int - यदि shape मिल जाता है तो शून्य-आधारित इंडेक्स; अन्यथा \\u20131।  

### toArray() {#toArray--}  
```
public final IShape[] toArray()
```

सभी shapes को सम्मिलित करने वाला array बनाता है और लौटाता है।

**वापसी:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स की एक array।  

### toArray(int startIndex, int count) {#toArray-int-int-}  
```
public final IShape[] toArray(int startIndex, int count)
```

निर्दिष्ट सीमा में सभी shapes को सम्मिलित करने वाला array बनाता है और लौटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| startIndex | int | पहला shape का इंडेक्स जिसे लौटाना है। |
| count | int | लौटाने हेतु shapes की संख्या। |

**वापसी:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स की एक array।  

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}  
```
public final void reorder(int index, IShape shape)
```

निर्दिष्ट shape को shape संग्रह के भीतर नई स्थिति में ले जाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | लक्ष्य शून्य-आधारित इंडेक्स जहाँ shape रखा जाएगा। |
| shape | [IShape](../../com.aspose.slides/ishape) | संग्रह के भीतर ले जाने वाला [IShape](../../com.aspose.slides/ishape)। |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}  
```
public final void reorder(int index, IShape[] shapes)
```

निर्दिष्ट shapes को shape संग्रह के भीतर ले जाता है, उन्हें दिए गए इंडेक्स से शुरू होते हुए रखता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | पहला निर्दिष्ट shape का लक्ष्य शून्य-आधारित इंडेक्स; बाद के shapes क्रम में रखे जाएँगे। |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | एक या अधिक [IShape](../../com.aspose.slides/ishape) इंस्टेंस जिन्हें संग्रह में ले जाना है। |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}  
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट फॉर्मेटिंग के साथ एक नया auto shape बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिये auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नव निर्मित [IAutoShape](../../com.aspose.slides/iautoshape)।  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}  
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया auto shape बनाता है और shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट फॉर्मेटिंग से प्रारम्भ करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिये auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | `true` → डिफ़ॉल्ट टेम्पलेट स्टाइलिंग (सरल स्टाइल, केंद्रित टेक्स्ट, गैर-खाली नाम) लागू करता है; `false` → सभी गुण डिफ़ॉल्ट मानों के साथ बनाता है। |

**वापसी:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नव निर्मित [IAutoShape](../../com.aspose.slides/iautoshape)।  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}  
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

गणितीय सामग्री होस्ट करने के लिये एक नया rectangle auto shape बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण PowerPoint प्रस्तुति में गणितीय समीकरण जोड़ने को दर्शाता है।
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नव निर्मित [IAutoShape](../../com.aspose.slides/iautoshape)।  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}  
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

एक नया auto shape बनाता है और डिफ़ॉल्ट टेम्पलेट फॉर्मेटिंग के साथ निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ नया auto shape सम्मिलित होगा। |
| shapeType | int | सम्मिलित करने के लिये auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नव निर्मित [IAutoShape](../../com.aspose.slides/iautoshape)।  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}  
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया auto shape बनाता है और वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ auto shape सम्मिलित होगा। |
| shapeType | int | सम्मिलित करने के लिये auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | shape फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | shape फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | shape फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | shape फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | `true` → डिफ़ॉल्ट टेम्पलेट स्टाइलिंग (गैर-खाली नाम, सरल स्टाइल, केंद्रित टेक्स्ट) लागू करता है; `false` → सभी गुण डिफ़ॉल्ट मानों के साथ बनाता है। |

**वापसी:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नव निर्मित [IAutoShape](../../com.aspose.slides/iautoshape)।  

### addGroupShape() {#addGroupShape--}  
```
public final IGroupShape addGroupShape()
```

एक नया खाली group shape बनाता है और shape संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गये shape को फिट करने के लिये समायोजित होगा।

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Presentation क्लास को इंस्टेंटिएट करता है
>  Presentation pres = new Presentation();
>  try {
>      // पहली स्लाइड तक पहुँचता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // स्लाइड्स के shape संग्रह तक पहुँच रहा है
>      IShapeCollection slideShapes = sld.getShapes();
>      // स्लाइड में एक group shape जोड़ रहा है
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // जोड़िए गए group shape के अंदर shapes जोड़ता है
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // group shape फ्रेम जोड़ता है
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX फ़ाइल को डिस्क पर सहेजता है
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नव निर्मित [IGroupShape](../../com.aspose.slides/igroupshape)।  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}  
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

एक नया group shape बनाता है, निर्दिष्ट SVG इमेज को व्यक्तिगत shapes में बदलता है, और परिणामस्वरूप समूह को shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | वेक्टर सामग्री वाली [ISvgImage](../../com.aspose.slides/isvgimage) जिसे shapes में बदलना है। |
| x | float | समूह फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | समूह फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | समूह फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | समूह फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नव निर्मित [IGroupShape](../../com.aspose.slides/igroupshape)।  

### insertGroupShape(int index) {#insertGroupShape-int-}  
```
public final IGroupShape insertGroupShape(int index)
```

एक नया खाली group shape बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गये shape को फिट करने के लिये समायोजित होगा।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ group shape सम्मिलित होगा। |

**वापसी:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नव निर्मित [IGroupShape](../../com.aspose.slides/igroupshape)।  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}  
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ एक नया connector shape बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि PowerPoint प्रस्तुति में दो shapes (एक ellipse और rectangle) के बीच connector (एक bent connector) कैसे जोड़ें।
>  
>  // PPTX फ़ाइल का प्रतिनिधित्व करने वाली प्रस्तुति क्लास का इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try {
>      // एक विशिष्ट स्लाइड के लिए shape संग्रह तक पहुँचता है
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Ellipse ऑटोशेप जोड़ता है
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Rectangle ऑटोशेप जोड़ता है
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // स्लाइड shape संग्रह में एक connector shape जोड़ता है
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // connector का उपयोग करके shapes को जोड़ता है
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // reroute को कॉल करता है जो shapes के बीच स्वचालित सबसे छोटा रास्ता सेट करता है
>      connector.reroute();
>      // प्रस्तुति को सहेजता है
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिये connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IConnector](../../com.aspose.slides/iconnector) - नव निर्मित [IConnector](../../com.aspose.slides/iconnector)।  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}  
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया connector shape बनाता है और shape संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeType | int | बनाने के लिये connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | `true` → डिफ़ॉल्ट टेम्पलेट स्टाइलिंग (गैर-खाली नाम, सरल स्टाइल) लागू करता है; `false` → डिफ़ॉल्ट गुणों के साथ connector बनाता है। |

**वापसी:**  
[IConnector](../../com.aspose.slides/iconnector) - नव निर्मित [IConnector](../../com.aspose.slides/iconnector)।  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}  
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

एक नया connector shape बनाता है और डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ connector shape सम्मिलित होगा। |
| shapeType | int | सम्मिलित करने के लिये connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IConnector](../../com.aspose.slides/iconnector) - नव निर्मित [IConnector](../../com.aspose.slides/iconnector)।  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}  
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया connector shape बनाता है और वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ connector shape सम्मिलित होगा। |
| shapeType | int | सम्मिलित करने के लिये connector shape का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | connector फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | connector फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | connector फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | connector फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | `true` → डिफ़ॉल्ट टेम्पलेट स्टाइलिंग (गैर-खाली नाम, सरल स्टाइल) लागू करता है; `false` → डिफ़ॉल्ट गुणों के साथ connector बनाता है। |

**वापसी:**  
[IConnector](../../com.aspose.slides/iconnector) - नव निर्मित [IConnector](../../com.aspose.slides/iconnector)।  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट इमेज को सम्मिलित करने वाला नया picture frame बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में समाहित shape प्रकार को निर्दिष्ट करता है, सभी प्रकार की लाइनों को छोड़कर। |
| x | float | picture frame का x-निर्देशांक, पॉइंट्स में। |
| y | float | picture frame का y-निर्देशांक, पॉइंट्स में। |
| width | float | picture frame की चौड़ाई, पॉइंट्स में। |
| height | float | picture frame की ऊँचाई, पॉइंट्स में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame में प्रदर्शित करने हेतु [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नव निर्मित [IPictureFrame](../../com.aspose.slides/ipictureframe)।  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट इमेज को सम्मिलित करने वाला नया picture frame बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ picture frame सम्मिलित होगा। |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में समाहित shape प्रकार को निर्दिष्ट करता है, सभी प्रकार की लाइनों को छोड़कर। |
| x | float | picture frame का x-निर्देशांक, पॉइंट्स में। |
| y | float | picture frame का y-निर्देशांक, पॉइंट्स में। |
| width | float | picture frame की चौड़ाई, पॉइंट्स में। |
| height | float | picture frame की ऊँचाई, पॉइंट्स में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | picture frame में प्रदर्शित करने हेतु [IPPImage](../../com.aspose.slides/ippimage)। |

**वापसी:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नव निर्मित [IPictureFrame](../../com.aspose.slides/ipictureframe)।  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}  
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

एक नया टेबल बनाता है और shape संग्रह के अंत में जोड़ता है।

--------------------

> ```
> निम्न उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति में तालिका कैसे जोड़ें।
>  
>  // PPTX फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टेंस बनाता है
>  Presentation pres = new Presentation();
>  try
>  {
>      // पहली स्लाइड तक पहुँचें
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // कॉलम की चौड़ाइयों और पंक्तियों की ऊँचाइयों को परिभाषित करें
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // स्लाइड में तालिका shape जोड़ें
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // हर सेल के लिए बॉर्डर फॉर्मेट सेट करें
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
>      // पंक्ति 1 के सेल 1 और 2 को मिलाएँ
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // मर्ज किए गए सेल में टेक्स्ट जोड़ें
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX को डिस्क पर सहेजें
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | float | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | float | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | double[] | टेबल के कॉलम की चौड़ाइयों का प्रतिनिधित्व करने वाला double एरे, पॉइंट्स में। |
| rowHeights | double[] | टेबल की रो की ऊँचाइयों का प्रतिनिधित्व करने वाला double एरे, पॉइंट्स में। |

**वापसी:**  
[ITable](../../com.aspose.slides/itable) - नव निर्मित [ITable](../../com.aspose.slides/itable)।  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}  
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

एक नया टेबल बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ टेबल सम्मिलित होगा। |
| x | float | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | float | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | double[] | कॉलम की चौड़ाइयों का प्रतिनिधित्व करने वाला double एरे, पॉइंट्स में। |
| rowHeights | double[] | रो की ऊँचाइयों का प्रतिनिधित्व करने वाला double एरे, पॉइंट्स में। |

**वापसी:**  
[ITable](../../com.aspose.slides/itable) - नव निर्मित [ITable](../../com.aspose.slides/itable)।  

### removeAt(int index) {#removeAt-int-}  
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर shape को shape संग्रह से हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाने हेतु shape का शून्य-आधारित इंडेक्स। |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}  
```
public final void remove(IShape shape)
```

निर्दिष्ट shape की पहली उपस्थिति को shape संग्रह से हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | हटाने हेतु [IShape](../../com.aspose.slides/ishape)। |

### clear() {#clear--}  
```
public final void clear()
```

सभी shapes को shape संग्रह से हटाता है।

### iterator() {#iterator--}  
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला enumerator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - संग्रह के माध्यम से इटररेट करने हेतु उपयोगी IGenericEnumerator।  

### iteratorJava() {#iteratorJava--}  
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

पूरे संग्रह के लिये java iterator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - पूरे संग्रह के लिये java.util.Iterator।  

### getParentGroup() {#getParentGroup--}  
```
public final IGroupShape getParentGroup()
```

shapes संग्रह के लिये पैरेंट group shape ऑब्जेक्ट प्राप्त करता है। केवल-पढ़ने-योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**वापसी:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}  
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला shape। |
| x | float | नई shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नई shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नई shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नई shape के फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}  
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है। नई shape का चौड़ाई एवं ऊँचाई sourceShape से समान रहती है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला shape। |
| x | float | नई shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नई shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}  
```
public final IShape addClone(IShape sourceShape)
```

निर्दिष्ट shape की एक कॉपी बनाता है और shape संग्रह के अंत में जोड़ता है। क्लोन की पोज़िशन और आकार मूल shape के समान रहता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}  
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ क्लोन्ड shape सम्मिलित होगा। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन्ड shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | क्लोन्ड shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | क्लोन्ड shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | क्लोन्ड shape के फ्रेम की ऊँचाई, पॉइंट्स में। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}  
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। नई shape की चौड़ाई एवं ऊँचाई sourceShape के समान रहती है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ क्लोन्ड shape सम्मिलित होगा। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन्ड shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | क्लोन्ड shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}  
```
public final IShape insertClone(int index, IShape sourceShape)
```

निर्दिष्ट shape की एक कॉपी बनाता है और निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है। क्लोन की पोज़िशन और आकार मूल shape के समान रहता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ क्लोन्ड shape सम्मिलित होगा। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने वाला [IShape](../../com.aspose.slides/ishape)। |

**वापसी:**  
[IShape](../../com.aspose.slides/ishape) - नव निर्मित [IShape](../../com.aspose.slides/ishape)।  

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}  
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारम्भिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}  
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच synchronized (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने-योग्य `boolean`।

**वापसी:**  
boolean  

### getSyncRoot() {#getSyncRoot--}  
```
public final Object getSyncRoot()
```

एक synchronization root लौटाता है। केवल-पढ़ने-योग्य `Object`।

**वापसी:**  
java.lang.Object