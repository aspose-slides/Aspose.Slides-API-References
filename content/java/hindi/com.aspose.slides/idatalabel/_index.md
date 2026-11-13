---
title: IDataLabel
second_title: Aspose.Slides for Java API संदर्भ
description: एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idatalabel/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

एक श्रृंखला लेबल का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [isVisible()](#isVisible--) | False का अर्थ है कि डेटा लेबल दिखाई नहीं देता (और इसलिए सभी Show*-flags (ShowValue, ...) false होते हैं). |
| [hide()](#hide--) | सभी Show*-flags (ShowValue, ...) को false स्थिति पर सेट करके डेटा लेबल को छिपा दें। |
| [getDataLabelFormat()](#getDataLabelFormat--) | डेटा लेबल का फ़ॉर्मेट लौटाता है। |
| [getValueFromCell()](#getValueFromCell--) | वर्कबुक डेटा सेल को प्राप्त या सेट करता है। |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | वर्कबुक डेटा सेल को प्राप्त या सेट करता है। |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है। |
| [getLabelShapeType()](#getLabelShapeType--) | डेटा लेबल के आकार प्रकार को प्राप्त या सेट करता है। |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | डेटा लेबल के आकार प्रकार को प्राप्त या सेट करता है। |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False का अर्थ है कि डेटा लेबल दिखाई नहीं देता (और इसलिए सभी Show*-flags (ShowValue, ...) false होते हैं). केवल पढ़ने योग्य boolean.

--------------------

यदि डेटा लेबल दिखाई देता है तो आप इसे Hide() मेथड से छिपा सकते हैं। लेकिन यदि डेटा लेबल नहीं दिखता (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति पर सेट करके डेटा लेबल को दिखाई दे सकता है।

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

सभी Show*-flags (ShowValue, ...) को false स्थिति पर सेट करके डेटा लेबल को छिपा दें। इससे बाद में IsVisible false होगा।

--------------------

यदि डेटा लेबल नहीं दिखता (IsVisible false है) तो आप Show*-flags (ShowValue, ...) को true स्थिति पर सेट करके डेटा लेबल को दिखा सकते हैं।

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

डेटा लेबल का फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)।

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

वर्कबुक डेटा सेल को प्राप्त या सेट करता है। यह तब लागू होता है जब IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true के बराबर हो।

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

वर्कबुक डेटा सेल को प्राप्त या सेट करता है। यह तब लागू होता है जब IDataLabelFormat.ShowLabelValueFromCell प्रॉपर्टी true के बराबर हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat सेटिंग्स या TextFrameForOverriding.Text मान के आधार पर वास्तविक लेबल टेक्स्ट लौटाता है।

**Returns:**
java.lang.String - वास्तविक लेबल टेक्स्ट String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

डेटा लेबल के आकार प्रकार को प्राप्त या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहली डेटा लेबल का आकार प्रकार Ellipse सेट करें.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

डेटा लेबल के आकार प्रकार को प्राप्त या सेट करता है। यदि कोई आकार परिभाषित नहीं है तो [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) लौटाता है।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // पहले डेटा लेबल का आकार प्रकार Ellipse सेट करें.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |