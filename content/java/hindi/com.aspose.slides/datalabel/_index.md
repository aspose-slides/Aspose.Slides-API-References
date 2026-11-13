---
title: DataLabel
second_title: Aspose.Slides for Java API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/datalabel/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।

## निर्माताओं

| निर्माता | विवरण |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel क्लास की एक नई इंस्टेंस बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | माता चार्ट लौटाता है। |
| [isVisible()](#isVisible--) | False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-फ़्लैग (ShowValue, ...) गलत हैं)। |
| [hide()](#hide--) | सभी Show*-फ़्लैग (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा दें। |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | पैरामीटर “text” में दिए गए टेक्स्ट के साथ TextFrameForOverriding को प्रारंभ करता है। |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | एक समृद्ध फ़ॉर्मेटेड टेक्स्ट रख सकता है। |
| [getTextFormat()](#getTextFormat--) | टेक्स्ट फ़ॉर्मेट लौटाता है। |
| [getX()](#getX--) | चार्ट की चौड़ाई के अनुपात में शीर्षक के x निर्देशांक को लौटाता या सेट करता है। |
| [setX(float value)](#setX-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक के x निर्देशांक को लौटाता या सेट करता है। |
| [getY()](#getY--) | चार्ट की ऊँचाई के अनुपात में शीर्षक के y निर्देशांक को लौटाता या सेट करता है। |
| [setY(float value)](#setY-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक के y निर्देशांक को लौटाता या सेट करता है। |
| [getWidth()](#getWidth--) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई को लौटाता या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई को लौटाता या सेट करता है। |
| [getHeight()](#getHeight--) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई को लौटाता या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई को लौटाता या सेट करता है। |
| [getRight()](#getRight--) | दाएँ। |
| [getBottom()](#getBottom--) | नीचे। |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल फ़ॉर्मेट लौटाता है। |
| [getValueFromCell()](#getValueFromCell--) | कार्यपुस्तिक डेटा सेल प्राप्त करता या सेट करता है। |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | कार्यपुस्तिक डेटा सेल प्राप्त करता या सेट करता है। |
| [getLabelShapeType()](#getLabelShapeType--) | डेटा लेबल के आकार प्रकार को प्राप्त करता या सेट करता है। |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | डेटा लेबल के आकार प्रकार को प्राप्त करता या सेट करता है। |
| [getActualX()](#getActualX--) | चार्ट तत्व की वास्तविक x स्थिति (बाएँ) को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) | FillFormat के मूल स्लाइड को लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की मूल प्रस्तुति को लौटाता है। |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel क्लास की एक नई इंस्टेंस बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | मूल ChartDataPoint। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate वस्तु लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न्स:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

माता चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न्स:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False का अर्थ है कि डेटा लेबल दृश्यमान नहीं है (और इसलिए सभी Show*-फ़्लैग (ShowValue, ...) गलत हैं)। केवल-पढ़ने योग्य बूलियन।

--------------------

यदि डेटा लेबल दृश्यमान है तो आप इसे Hide() विधि से छिपा सकते हैं। लेकिन यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false है) तो आप Show*-फ़्लैग (ShowValue, ...) को true स्थिति में सेट करके लेबल को दृश्यमान बना सकते हैं।

**रिटर्न्स:**
boolean

### hide() {#hide--}
```
public final void hide()
```

सभी Show*-फ़्लैग (ShowValue, ...) को false स्थिति में सेट करके डेटा लेबल को छिपा दें। इस के बाद IsVisible false रहेगा।

--------------------

यदि डेटा लेबल दृश्यमान नहीं है (IsVisible false है) तो आप Show*-फ़्लैग (ShowValue, ...) को true स्थिति में सेट करके लेबल को दृश्यमान बना सकते हैं।

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है।

**रिटर्न्स:**
java.lang.String - The java.lang.String object।

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

पैरामीटर “text” में दिए गए टेक्स्ट के साथ TextFrameForOverriding को प्रारंभ करता है। यदि TextFrameForOverriding पहले से प्रारंभ है तो केवल इसका टेक्स्ट बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नई TextFrameForOverriding के लिए टेक्स्ट। |

**रिटर्न्स:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

एक समृद्ध फ़ॉर्मेटेड टेक्स्ट रख सकता है। यदि यह प्रॉपर्टी null नहीं है तो यह फ़ॉर्मेटेड टेक्स्ट मान डेटा लेबल के स्वचालित-जेनरेटेड टेक्स्ट को ओवरराइड करता है। स्वचालित-जेनरेटेड टेक्स्ट वह होता है जो ShowSeriesName, ShowValue, … प्रॉपर्टीज़ द्वारा प्रबंधित होता है और TextFormatManager.TextFormat प्रॉपर्टी से फ़ॉर्मेट किया जाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न्स:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../../com.aspose.slides/icharttextformat)।

**रिटर्न्स:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक के x निर्देशांक को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**रिटर्न्स:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक के x निर्देशांक को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक के y निर्देशांक को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**रिटर्न्स:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक के y निर्देशांक को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**रिटर्न्स:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

चार्ट की चौड़ाई के अनुपात में शीर्षक की चौड़ाई को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**रिटर्न्स:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

चार्ट की ऊँचाई के अनुपात में शीर्षक की ऊँचाई को लौटाता या सेट करता है। केवल-पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

दाएँ। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

नीचे। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**रिटर्न्स:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

कार्यपुस्तिक डेटा सेल प्राप्त करता या सेट करता है। लागू होता है यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है।

**रिटर्न्स:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

कार्यपुस्तिक डेटा सेल प्राप्त करता या सेट करता है। लागू होता है यदि IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

डेटा लेबल के आकार प्रकार को प्राप्त करता या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहले डेटा लेबल का आकार प्रकार Ellipse पर सेट करें।
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न्स:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

डेटा लेबल के आकार प्रकार को प्राप्त करता या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहले डेटा लेबल का आकार प्रकार Ellipse पर सेट करें।
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट तत्व की वास्तविक x स्थिति (बाएँ) को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये IChart.ValidateChartLayout() विधि को पहले कॉल करें। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ-ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये IChart.ValidateChartLayout() विधि को पहले कॉल करें। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये IChart.ValidateChartLayout() विधि को पहले कॉल करें। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिये IChart.ValidateChartLayout() विधि को पहले कॉल करें। केवल-पढ़ने योग्य float।

**रिटर्न्स:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat की मूल स्लाइड को लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न्स:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की मूल प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न्स:**
[IPresentation](../../com.aspose.slides/ipresentation)