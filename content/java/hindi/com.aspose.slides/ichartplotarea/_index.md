---
title: IChartPlotArea
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartplotarea/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) | प्लॉट एरिया का स्वरूप लौटाता है। |
| [getLayoutTargetType()](#getLayoutTargetType--) | यदि प्लॉट एरिया का लेआउट मैन्युअली परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (धुरी और धुरी लेबल को छोड़कर) या बाहर (धुरी और धुरी लेबल सहित) लेआउट किया जाए। |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | यदि प्लॉट एरिया का लेआउट मैन्युअली परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (धुरी और धुरी लेबल को छोड़कर) या बाहर (धुरी और धुरी लेबल सहित) लेआउट किया जाए। |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

प्लॉट एरिया का स्वरूप लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**  
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

यदि प्लॉट एरिया का लेआउट मैन्युअली परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (धुरी और धुरी लेबल को छोड़कर) या बाहर (धुरी और धुरी लेबल सहित) लेआउट किया जाए। पढ़ने/लिखने योग्य [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**वापसी:**  
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

यदि प्लॉट एरिया का लेआउट मैन्युअली परिभाषित किया गया है तो यह प्रॉपर्टी निर्धारित करती है कि प्लॉट एरिया को उसके अंदर (धुरी और धुरी लेबल को छोड़कर) या बाहर (धुरी और धुरी लेबल सहित) लेआउट किया जाए। पढ़ने/लिखने योग्य [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |