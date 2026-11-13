---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: चार्ट श्रेणियों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

चार्ट श्रेणियों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
|---|---|
| [getUseCell()](#getUseCell--) | यदि true है तो AsCell प्रॉपर्टी वास्तविक है। |
| [getAsCell()](#getAsCell--) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getAsLiteral()](#getAsLiteral--) | यदि UseCell false है तो AsLiteral को लौटाता है या सेट करता है। |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | यदि UseCell false है तो AsLiteral को लौटाता है या सेट करता है। |
| [getValue()](#getValue--) | यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। |
| [getCachedValue()](#getCachedValue--) | एक चार्ट श्रेणी का कैश किया गया मान प्राप्त करता है। |
| [getGroupingLevels()](#getGroupingLevels--) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। |
| [remove()](#remove--) | श्रेणी को चार्ट से हटाता है। |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

यदि true है तो AsCell प्रॉपर्टी वास्तविक है। दूसरे शब्दों में, वर्कशीट श्रेणी को संग्रहीत करने के लिए उपयोग की जाती है (यह केस मल्टी-लेवल श्रेणी का समर्थन करता है)। यदि false है तो AsLiteral प्रॉपर्टी वास्तविक है। दूसरे शब्दों में, वर्कशीट श्रेणी को संग्रहीत करने के लिए उपयोग नहीं की जाती (और यह केस मल्टी-लेवल श्रेणियों का समर्थन नहीं करता)। पढ़ने-केवल बूलियन।

--------------------

इस प्रॉपर्टी का मान बदलने के लिए (सभी श्रेणियों के संग्रह में) नया मान [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) प्रॉपर्टी में सेट करें।

**रिटर्न:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी मल्टी-लेवल है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग होता है। पढ़ने/लिखने योग्य [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी मल्टी-लेवल है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट का उपयोग होता है। पढ़ने/लिखने योग्य [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
|---|---|---|
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

यदि UseCell false है तो AsLiteral को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Object।

**रिटर्न:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

यदि UseCell false है तो AsLiteral को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Object।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
|---|---|---|
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। यदि UseCell false है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाती है। पढ़ने/लिखने योग्य Object।

**रिटर्न:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

यदि UseCell true है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी को दर्शाती है। यदि UseCell false है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी को दर्शाती है। पढ़ने/लिखने योग्य Object।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
|---|---|---|
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

एक चार्ट श्रेणी का कैश किया गया मान प्राप्त करता है। केवल-पढ़ने योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // सभी कैश किए गए चार्ट श्रेणी मान प्रिंट करें।
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। मल्टी-लेवल श्रेणी में एक से अधिक समूह स्तर होते हैं। समूह स्तरों का इंडेक्सिंग शून्य-आधारित है। केवल-पढ़ने योग्य [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)।

**रिटर्न:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

श्रेणी को चार्ट से हटाता है।