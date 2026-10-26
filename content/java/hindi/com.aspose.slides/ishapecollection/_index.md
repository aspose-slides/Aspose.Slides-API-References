---
title: IShapeCollection
second_title: Aspose.Slides जावा API संदर्भ
description: आकारों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ishapecollection/
---
**सभी लागू किए गए इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

आकारों के संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [getParentGroup()](#getParentGroup--) | आकार संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | एक SmartArt आरेख बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | एक नया Zoom फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | एक नया Section Zoom फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | एक पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | एक नया Summary Zoom फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | एक नया वीडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | एक नया वीडियो फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | एक नया ऑडियो फ्रेम बनाता है जो CD ट्रैक से जुड़ा है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | एक नया ऑडियो फ्रेम बनाता है जो बाहरी ऑडियो फ़ाइल से जुड़ा है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | प्रस्तुति की Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | एम्बेडेड WAV फ़ाइल के साथ नया ऑडियो फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | प्रस्तुति की Audios सूची से मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके नया ऑडियो फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | संग्रह में निर्दिष्ट आकार की पहली घटना का शून्य-आधारित सूचकांक लौटाता है। |
| [toArray()](#toArray--) | सभी आकारों को समाहित करने वाला एरे बनाता है और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | निर्दिष्ट सीमा में सभी आकारों को समाहित करने वाला एरे बनाता है और लौटाता है। |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | निर्दिष्ट आकार को आकार संग्रह के भीतर नई स्थिति में ले जाता है। |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | निर्दिष्ट आकारों को आकार संग्रह के भीतर ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ नया ऑटोशेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | नया ऑटोशेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है। |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | गणितीय सामग्री को होस्ट करने के लिए नया आयताकार ऑटोशेप बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | नया ऑटोशेप बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है। |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | नया ऑटोशेप बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ प्रारंभ करता है। |
| [addGroupShape()](#addGroupShape--) | नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकारों में बदलता है, और परिणामस्वरूप समूह को आकार संग्रह के अंत में जोड़ता है। |
| [insertGroupShape(int index)](#insertGroupShape-int-) | नया खाली समूह आकार बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | नया कनेक्टर आकार बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है, डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | नया कनेक्टर आकार बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है। |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि को सम्मिलित करने वाला नया चित्र फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | निर्दिष्ट छवि को सम्मिलित करने वाला नया चित्र फ्रेम बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | नया तालिका बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | नया तालिका बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर आकार को आकार संग्रह से हटाता है। |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | निर्दिष्ट आकार की पहली घटना को आकार संग्रह से हटाता है। |
| [clear()](#clear--) | सभी आकारों को आकार संग्रह से हटाता है। |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | निर्दिष्ट आकार की कॉपी बनाता है और इसे आकार संग्रह के अंत में जोड़ता है। |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | निर्दिष्ट आकार की कॉपी बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | निर्दिष्ट आकार की कॉपी बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | निर्दिष्ट आकार की कॉपी बनाता है और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IShape](../../com.aspose.slides/ishape)।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मूल्य:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

आकार संग्रह के लिए पैरेंट समूह आकार वस्तु प्राप्त करता है। केवल पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

**वापसी मूल्य:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, बिंदुओं में। |
| y | float | नए चार्ट का y-निर्देशांक, बिंदुओं में। |
| width | float | चार्ट की चौड़ाई, बिंदुओं में। |
| height | float | चार्ट की ऊँचाई, बिंदुओं में। |

**वापसी मूल्य:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | जोड़ने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, बिंदुओं में। |
| y | float | नए चार्ट का y-निर्देशांक, बिंदुओं में। |
| width | float | चार्ट की चौड़ाई, बिंदुओं में। |
| height | float | चार्ट की ऊँचाई, बिंदुओं में। |
| initWithSample | boolean | true होने पर नया चार्ट नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ होता है; false होने पर चार्ट बिना श्रृंखला और केवल न्यूनतम सेटिंग्स के बनाया जाता है, जिससे निर्माण तेज़ होता है। |

**वापसी मूल्य:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

एक SmartArt आरेख बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

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


**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | आरेख के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | float | आरेख के फ्रेम का y-निर्देशांक, बिंदुओं में। |
| width | float | आरेख के फ्रेम की चौड़ाई, बिंदुओं में। |
| height | float | आरेख के फ्रेम की ऊँचाई, बिंदुओं में। |
| layoutType | int | SmartArt लेआउट प्रकार। |

**वापसी मूल्य:**
[ISmartArt](../../com.aspose.slides/ismartart) - नया बनाया गया [ISmartArt](../../com.aspose.slides/ismartart)।

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, बिंदुओं में। |
| y | float | नए चार्ट का y-निर्देशांक, बिंदुओं में। |
| width | float | नए चार्ट की चौड़ाई, बिंदुओं में। |
| height | float | नए चार्ट की ऊँचाई, बिंदुओं में। |
| index | int | शून्य-आधारित सूचकांक जहाँ नया चार्ट आकार संग्रह में डाला जाएगा। |

**वापसी मूल्य:**
[IChart](../../com.aspose.slides/ichart) - नया बनाया गया [IChart](../../com.aspose.slides/ichart)।

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट सूचकांक पर आकार संग्रह में डालता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | बनाने के लिए चार्ट का प्रकार। |
| x | float | नए चार्ट का x-निर्देशांक, बिंदुओं में। |
| y | float | नए चार्ट का y-निर्देशांक, बिंदुओं में। |
| width | float | नए चार्ट की चौड़ाई, बिंदुओं में। |
| height | float | नए चार्ट की ऊँचाई, बिंदुओं में। |
| index | int | शून्य-आधारित सूचकांक जहाँ नया चार्ट आकार संग्रह में डाला जाएगा। |
| initWithSample | boolean | true होने पर नया चार्ट नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ होता है; false होने पर चार्ट बिना श्रृंखला और केवल न्यूनतम सेटिंग्स के बनाया जाता है, जिससे निर्माण तेज़ होता है। |
| initWithSample | boolean | True को यह दर्शाने के लिए कि नया chart नमूना series डेटा और settings के साथ प्रारंभ किया जाए; false को यह दर्शाने के लिए कि chart को बिना series के और केवल न्यूनतम settings के साथ बनाया जाए, जिससे निर्माण तेज़ हो जाता है। |

**रिटर्न मान:**
[IChart](../../com.aspose.slides/ichart) - नया निर्मित [IChart](../../com.aspose.slides/ichart)।

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | संलग्न OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**रिटर्न मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पथ। इस पथ को प्रस्तुति में जैसा है वैसा ही संग्रहीत किया जाता है। यदि कोई सापेक्ष पथ निर्दिष्ट किया गया है, तो प्रस्तुति को किसी अलग निर्देशिका से खोलने पर फ़ाइल अनुपलब्ध होगी। |

**रिटर्न मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित सूचकांक जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | संलग्न OLE डेटा जानकारी ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo))। |

**रिटर्न मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित सूचकांक जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| className | java.lang.String | OLE ऑब्जेक्ट का क्लास नाम। |
| path | java.lang.String | लिंक्ड फ़ाइल का पथ। इस पथ को प्रस्तुति में जैसा है वैसा ही संग्रहीत किया जाता है। यदि कोई सापेक्ष पथ निर्दिष्ट किया गया है, तो प्रस्तुति को किसी अलग निर्देशिका से खोलने पर फ़ाइल अनुपलब्ध होगी। |

**रिटर्न मान:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - नया निर्मित [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह प्रस्तुति का हिस्सा होना चाहिए। |

**रिटर्न मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide); यह प्रस्तुति का हिस्सा होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए छवि। |

**रिटर्न मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

एक नया Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित सूचकांक जहाँ Zoom फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |

**रिटर्न मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

एक नया Zoom फ्रेम पूर्वनिर्धारित छवि के साथ बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| index | int | वह शून्य-आधारित सूचकांक जहाँ Zoom फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [ISlide](../../com.aspose.slides/islide)। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | संदर्भित स्लाइड [IPPImage](../../com.aspose.slides/ippimage) के लिए छवि। |

**रिटर्न मान:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - नया निर्मित [IZoomFrame](../../com.aspose.slides/izoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होना चाहिए। |

**रिटर्न मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

पूर्वनिर्धारित छवि के साथ एक नया Section Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**रिटर्न मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | वह शून्य-आधारित सूचकांक जहाँ Section Zoom फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होना चाहिए। |

**रिटर्न मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

पूर्वनिर्धारित छवि के साथ एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape collection में सम्मिलित करता है।

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित सूचकांक जहाँ Section Zoom फ्रेम सम्मिलित किया जाएगा। |
| x | float | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [ISection](../../com.aspose.slides/isection); यह प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल होना चाहिए। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए छवि। |

**रिटर्न मान:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - नया निर्मित [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)।

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

एक नया Summary Zoom फ्रेम बनाता है और इसे shape collection के अंत में जोड़ता है।

--------------------

> ```
> यह उदाहरण एक संग्रह के अंत में Summary Zoom ऑब्जेक्ट जोड़ने को दर्शाता है
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
| x | float | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**रिटर्न:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नई बनाई गई [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

एक नया Summary Zoom फ़्रेम बनाता है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है।

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | शून्य-आधारित सूचकांक जहाँ Summary Zoom फ़्रेम डालना है। |
| x | float | नए Summary Zoom फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए Summary Zoom फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए Summary Zoom फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए Summary Zoom फ़्रेम की ऊँचाई, पॉइंट में। |

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**रिटर्न:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - नई बनाई गई [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ़्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए वीडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए वीडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए वीडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एंबेड करने के लिए वीडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नई बनाई गई [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ़्रेम बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए वीडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए वीडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए वीडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| video | [IVideo](../../com.aspose.slides/ivideo) | वीडियो फ़्रेम में एंबेड करने के लिए [IVideo](../../com.aspose.slides/ivideo)। |

**रिटर्न:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नई बनाई गई [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

एक नया वीडियो फ़्रेम बनाता है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ वीडियो फ़्रेम डालना है। |
| x | float | नए वीडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए वीडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए वीडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए वीडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | एंबेड करने के लिए वीडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - नई बनाई गई [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

एक नया ऑडियो फ़्रेम जो CD ट्रैक से जुड़ा है बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

एक नया ऑडियो फ़्रेम जो CD ट्रैक से जुड़ा है बनाता है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ ऑडियो फ़्रेम डालना है। |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ़्रेम जो बाहरी ऑडियो फ़ाइल से जुड़ा है बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

एक नया ऑडियो फ़्रेम जो बाहरी ऑडियो फ़ाइल से जुड़ा है बनाता है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ ऑडियो फ़्रेम डालना है। |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| fname | java.lang.String | लिंक करने के लिए बाहरी ऑडियो फ़ाइल का पथ या नाम। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ़्रेम बनाता है जिसमें एंबेडेड WAV फ़ाइल होती है और shape संग्रह के अंत में जोड़ता है। एंबेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | WAV ऑडियो डेटा वाला इनपुट स्ट्रीम जिसे एंबेड करना है। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ़्रेम बनाता है और Presentation.Audios सूची में मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) उदाहरण। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

एक नया ऑडियो फ़्रेम बनाता है जिसमें एंबेडेड WAV फ़ाइल होती है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है। एंबेडेड ऑडियो Presentation.Audios संग्रह में जोड़ी जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ ऑडियो फ़्रेम डालना है। |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| audio_stream | java.io.InputStream | WAV ऑडियो डेटा वाला इनपुट स्ट्रीम जिसे एंबेड करना है। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

एक नया ऑडियो फ़्रेम बनाता है और निर्दिष्ट सूचकांक पर shape संग्रह में डालता है, Presentation.Audios सूची में मौजूदा ऑडियो ऑब्जेक्ट का उपयोग करके।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ ऑडियो फ़्रेम डालना है। |
| x | float | नए ऑडियो फ़्रेम का x-समन्वय, पॉइंट में। |
| y | float | नए ऑडियो फ़्रेम का y-समन्वय, पॉइंट में। |
| width | float | नए ऑडियो फ़्रेम की चौड़ाई, पॉइंट में। |
| height | float | नए ऑडियो फ़्रेम की ऊँचाई, पॉइंट में। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios संग्रह से एक [IAudio](../../com.aspose.slides/iaudio) उदाहरण जिसे एंबेड किया जाएगा। |

**रिटर्न:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - नई बनाई गई [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

निर्दिष्ट shape की संग्रह में पहली उपस्थिति का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | संग्रह में खोजने के लिए shape। |

**रिटर्न:**
int - शून्य-आधारित सूचकांक यदि मिला; अन्यथा, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

एक एरे बनाता और लौटाता है जिसमें सभी shape शामिल हैं।

**रिटर्न:**
com.aspose.slides.IShape[] - एक एरे जिसमें [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स हैं।

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

एक एरे बनाता और लौटाता है जिसमें निर्दिष्ट सीमा के सभी shape शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | वापसी के लिए पहला shape जिसका सूचकांक। |
| count | int | वापसी के लिए shape की संख्या। |

**रिटर्न:**
com.aspose.slides.IShape[] - एक एरे जिसमें [IShape](../../com.aspose.slides/ishape) ऑब्जेक्ट्स हैं।

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

निर्दिष्ट shape को shape संग्रह में नई स्थिति पर ले जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित लक्ष्य सूचकांक जहाँ shape रखा जाएगा। |
| shape | [IShape](../../com.aspose.slides/ishape) | ले जाने के लिए [IShape](../../com.aspose.slides/ishape)। |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

निर्दिष्ट shapes को shape संग्रह में ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित लक्ष्य सूचकांक जहाँ पहला निर्दिष्ट shape रखा जाएगा; बाद के shapes क्रम में रखे जाएंगे। |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | संग्रह में ले जाने के लिए एक या अधिक [IShape](../../com.aspose.slides/ishape) उदाहरण। |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट फॉर्मेटिंग के साथ एक नया auto shape बनाता है और shape संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeType | int | जोड़े जाने वाले auto shape का [ShapeType](../../com.aspose.slides/shapetype)। |

| x | float | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape).  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए ऑटो शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | true से नए शेप पर डिफ़ॉल्ट टेम्पलेट स्टाइल लागू होता है (सादा शैली, केंद्रित टेक्स्ट, और खाली नहीं नाम); false से शेप को सभी प्रॉपर्टी को उनके डिफ़ॉल्ट मानों पर सेट करके बनाया जाता है। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape).  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}  
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

गणितीय सामग्री रखने के लिए एक नया रेक्टैंगल ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

एक नया ऑटो शेप बनाता है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है, डिफ़ॉल्ट टेम्पलेट फ़ॉर्मेटिंग लागू करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | नया ऑटो शेप डालने के लिए शून्य-आधारित इंडेक्स। |
| shapeType | int | डालने के लिए ऑटो शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया ऑटो शेप बनाता है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइल के साथ प्रारंभ करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ऑटो शेप डालने के लिए शून्य-आधारित इंडेक्स। |
| shapeType | int | डालने के लिए ऑटो शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | true से डिफ़ॉल्ट टेम्पलेट स्टाइल लागू होता है (खाली नहीं नाम, सादा शैली, केंद्रित टेक्स्ट); false से शेप को सभी प्रॉपर्टी डिफ़ॉल्ट मानों पर सेट करके बनाया जाता है। |

**रिटर्न:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - नया बनाया गया [IAutoShape](../../com.aspose.slides/iautoshape).  

### addGroupShape() {#addGroupShape--}  
```
public abstract IGroupShape addGroupShape()
```

एक नया खाली ग्रुप शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है। ग्रुप का फ्रेम स्वतः ही उसमें जोड़े गए शेप्स के अनुसार आकार लेगा।  

**रिटर्न:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape).  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}  
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

एक नया ग्रुप शेप बनाता है, निर्दिष्ट SVG इमेज को व्यक्तिगत शेप्स में परिवर्तित करता है, और परिणामी ग्रुप को शेप कलेक्शन के अंत में जोड़ता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | वेक्टर सामग्री वाले [ISvgImage](../../com.aspose.slides/isvgimage) को शेप्स में बदलने के लिए। |
| x | float | ग्रुप के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | ग्रुप के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | ग्रुप के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | ग्रुप के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape).  

### insertGroupShape(int index) {#insertGroupShape-int-}  
```
public abstract IGroupShape insertGroupShape(int index)
```

एक नया खाली ग्रुप शेप बनाता है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है। ग्रुप का फ्रेम स्वतः ही उसमें जोड़े गए शेप्स के अनुसार आकार लेगा।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ग्रुप शेप डालने के लिए शून्य-आधारित इंडेक्स। |

**रिटर्न:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - नया बनाया गया [IGroupShape](../../com.aspose.slides/igroupshape).  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

डिफ़ॉल्ट टेम्पलेट स्टाइल वाला एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | जोड़ने के लिए कनेक्टर शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector).  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइल लागू करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | बनाने के लिए कनेक्टर शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | true से डिफ़ॉल्ट टेम्पलेट स्टाइल लागू होता है (खाली नहीं नाम, सादा शैली); false से कनेक्टर को डिफ़ॉल्ट प्रॉपर्टी मानों के साथ बनाया जाता है। |

**रिटर्न:**  
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है, डिफ़ॉल्ट टेम्पलेट स्टाइल लागू करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | कनेक्टर शेप डालने के लिए शून्य-आधारित इंडेक्स। |
| shapeType | int | डालने के लिए कनेक्टर शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |

**रिटर्न:**  
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइल लागू करता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | कनेक्टर शेप डालने के लिए शून्य-आधारित इंडेक्स। |
| shapeType | int | डालने के लिए कनेक्टर शेप का [ShapeType](../../com.aspose.slides/shapetype)। |
| x | float | कनेक्टर के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | कनेक्टर के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |
| createFromTemplate | boolean | true से डिफ़ॉल्ट टेम्पलेट स्टाइल लागू होता है (खाली नहीं नाम, सादा शैली); false से कनेक्टर को डिफ़ॉल्ट प्रॉपर्टी मानों के साथ बनाया जाता है। |

**रिटर्न:**  
[IConnector](../../com.aspose.slides/iconnector) - नया बनाया गया [IConnector](../../com.aspose.slides/iconnector).  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

निर्दिष्ट इमेज वाला एक नया पिक्चर फ्रेम बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में सम्मिलित शेप टाइप को निर्दिष्ट करता है, सिवाय सभी प्रकार की लाइन्स के:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | पिक्चर फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | पिक्चर फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | पिक्चर फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | पिक्चर फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | पिक्चर फ्रेम में प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**रिटर्न:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

एक नया पिक्चर फ्रेम बनाता है जिसमें निर्दिष्ट इमेज होती है और इसे शेप कलेक्शन में निर्दिष्ट इंडेक्स पर डालता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | पिक्चर फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) में सम्मिलित शेप टाइप को निर्दिष्ट करता है, सिवाय सभी प्रकार की लाइन्स के:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | पिक्चर फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | float | पिक्चर फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | float | पिक्चर फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | float | पिक्चर फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | पिक्चर फ्रेम में प्रदर्शित करने के लिए [IPPImage](../../com.aspose.slides/ippimage)। |

**रिटर्न:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - नया बनाया गया [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}  
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

एक नया टेबल बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।  

**पैरामीटर्स:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | float | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | double[] | टेबल के कॉलम की चौड़ाइयों का डबल एरे, पॉइंट्स में। |
| rowHeights | double[] | टेबल की रो की ऊँचाइयों का डबल एरे, पॉइंट्स में। |

**रिटर्न:**  
[ITable](../../com.aspose.slides/itable) - नया बनाया गया [ITable](../../com.aspose.slides/itable).  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}  
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
एक नया टेबल बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शैप संग्रह में डालता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमांक जिस पर टेबल डालना है। |
| x | float | टेबल का x-निर्देशांक, पॉइंट में। |
| y | float | टेबल का y-निर्देशांक, पॉइंट में। |
| columnWidths | double[] | डबल्स की एक एरे जो टेबल के कॉलमों की चौड़ाई दर्शाती है, पॉइंट में। |
| rowHeights | double[] | डबल्स की एक एरे जो टेबल की पंक्तियों की ऊँचाई दर्शाती है, पॉइंट में। |

**रिटर्न:**
[ITable](../../com.aspose.slides/itable) - नई बनाई गई [ITable](../../com.aspose.slides/itable)।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर स्थित शैप को शैप संग्रह से हटा देता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शैप को हटाने के लिए शून्य-आधारित अनुक्रमांक। |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

शैप संग्रह से निर्दिष्ट शैप की पहली घटना को हटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | हटाने के लिए [IShape](../../com.aspose.slides/ishape)। |

### clear() {#clear--}
```
public abstract void clear()
```

शैप संग्रह से सभी शैप हटाता है।

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे शैप संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए शैप। |
| x | float | क्लोन किए गए शैप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए शैप के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | क्लोन किए गए शैप के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | क्लोन किए गए शैप के फ्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे शैप संग्रह के अंत में जोड़ता है। नया शैप sourceShape की चौड़ाई और ऊँचाई बनाए रखता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए शैप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए शैप के फ्रेम का y-निर्देशांक, पॉइंट में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे शैप संग्रह के अंत में जोड़ता है। क्लोन किया गया शैप मूल की स्थिति और आकार को बनाए रखता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शैप संग्रह में डालता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमांक जिस पर क्लोन किए गए शैप को डालना है। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए शैप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए शैप के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | float | क्लोन किए गए शैप के फ्रेम की चौड़ाई, पॉइंट में। |
| height | float | क्लोन किए गए शैप के फ्रेम की ऊँचाई, पॉइंट में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शैप संग्रह में डालता है। नया शैप sourceShape की चौड़ाई और ऊँचाई बनाए रखता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमांक जिस पर क्लोन किए गए शैप को डालना है। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |
| x | float | क्लोन किए गए शैप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | float | क्लोन किए गए शैप के फ्रेम का y-निर्देशांक, पॉइंट में। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

निर्दिष्ट शैप की एक प्रति बनाता है और इसे निर्दिष्ट अनुक्रमांक पर शैप संग्रह में डालता है। क्लोन किया गया शैप मूल की स्थिति और आकार को बनाए रखता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | शून्य-आधारित अनुक्रमांक जिस पर क्लोन किए गए शैप को डालना है। |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | क्लोन करने के लिए [IShape](../../com.aspose.slides/ishape)। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - नई बनाई गई [IShape](../../com.aspose.slides/ishape)।