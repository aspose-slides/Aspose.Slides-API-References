---
title: ChartCategory
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट श्रेणियों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartcategory/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

चार्ट श्रेणियों का प्रतिनिधित्व करता है।  
## विधियाँ

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | यदि true हो तो AsCell प्रॉपर्टी वास्तविक है। |
| [getAsCell()](#getAsCell--) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getValue()](#getValue--) | यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी प्रतिनिधित्व करती है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी प्रतिनिधित्व करती है। |
| [getGroupingLevels()](#getGroupingLevels--) | चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। |
| [getCachedValue()](#getCachedValue--) | एक चार्ट श्रेणी का कैश किया हुआ मान प्राप्त करता है। |
| [remove()](#remove--) | श्रेणी को चार्ट से हटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

यदि true हो तो AsCell प्रॉपर्टी वास्तविक है। अन्य शब्दों में, वर्कशीट श्रेणी को संग्रहीत करने के लिए उपयोग की जाती है (यह केस मल्टी-लेवल श्रेणी का समर्थन करता है)। यदि false हो तो AsLiteral प्रॉपर्टी वास्तविक है। अन्य शब्दों में, वर्कशीट श्रेणी को संग्रहीत करने के लिए उपयोग नहीं की जाती (और यह केस मल्टी-लेवल श्रेणियों का समर्थन नहीं करता)। Read-only बूलियन.

--------------------

इस प्रॉपर्टी का मान बदलने के लिए (संग्रह में सभी श्रेणियों के लिए) ChartCategoryCollection.UseCells प्रॉपर्टी को नया मान सेट करें।

**रिटर्न:**  
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी मल्टी-लेवल है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**रिटर्न:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell ऑब्जेक्ट को लौटाता है या सेट करता है। यदि श्रेणी मल्टी-लेवल है तो स्तर "0" के लिए IChartDataCell ऑब्जेक्ट उपयोग किया जाता है। पढ़ें/लिखें [IChartDataCell](../../com.aspose.slides/ichartdatacell)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object।

**रिटर्न:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें Object।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी प्रतिनिधित्व करती है। यदि UseCell असत्य है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी प्रतिनिधित्व करती है। पढ़ें/लिखें Object।

**रिटर्न:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

यदि UseCell सत्य है तो यह प्रॉपर्टी AsCell.Value प्रॉपर्टी प्रतिनिधित्व करती है। यदि UseCell असत्य है तो यह प्रॉपर्टी AsLiteral प्रॉपर्टी प्रतिनिधित्व करती है। पढ़ें/लिखें Object।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

चार्ट श्रेणी समूह स्तरों के मानों का प्रबंधित कंटेनर। मल्टी-लेवल श्रेणी में एक से अधिक समूह स्तर होते हैं। समूह स्तरों की अनुक्रमण शून्य-आधारित है। केवल-पढ़ने-योग्य [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)।

**रिटर्न:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

एक चार्ट श्रेणी का कैश किया हुआ मान प्राप्त करता है। केवल-पढ़ने-योग्य [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)।

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // सभी कैश किए गए चार्ट श्रेणी मानों को प्रदर्शित करें।
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**रिटर्न:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```

श्रेणी को चार्ट से हटाता है।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को लौटाता है। केवल-पढ़ने-योग्य IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject