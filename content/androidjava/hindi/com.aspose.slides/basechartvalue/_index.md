---
title: BaseChartValue
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक चार्ट का मान दर्शाता है।
type: docs
url: /hi/com.aspose.slides/basechartvalue/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

चार्ट का मान दर्शाता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | निर्देशित करता है कि AsCell, AsCells, AsLiteralString या AsLiteralDouble प्रॉपर्टी वंशजों में वास्तविक है या नहीं। |
| [setDataSourceType(int value)](#setDataSourceType-int-) | निर्देशित करता है कि AsCell, AsCells, AsLiteralString या AsLiteralDouble प्रॉपर्टी वंशजों में वास्तविक है या नहीं। |
| [getData()](#getData--) | डेटा। |
| [setData(Object value)](#setData-java.lang.Object-) | डेटा। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

निर्देशित करता है कि AsCell, AsCells, AsLiteralString या AsLiteralDouble प्रॉपर्टी वंशजों में वास्तविक है या नहीं। दूसरे शब्दों में यह Data प्रॉपर्टी के मान के प्रकार को निर्धारित करता है। पढ़ने/लिखने [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection में बिंदुओं के लिए यह प्रॉपर्टी केवल पढ़ने योग्य है। इस स्थिति में इस प्रॉपर्टी का मान बदलने के लिए आप ChartDataPointCollection.DataSourceTypeFor<...> प्रॉपर्टियों में से एक का उपयोग कर सकते हैं।

**वापसी:**
int

### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

निर्देशित करता है कि AsCell, AsCells, AsLiteralString या AsLiteralDouble प्रॉपर्टी वंशजों में वास्तविक है या नहीं। दूसरे शब्दों में यह Data प्रॉपर्टी के मान के प्रकार को निर्धारित करता है। पढ़ने/लिखने [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection में बिंदुओं के लिए यह प्रॉपर्टी केवल पढ़ने योग्य है। इस स्थिति में इस प्रॉपर्टी का मान बदलने के लिए आप ChartDataPointCollection.DataSourceTypeFor<...> प्रॉपर्टियों में से एक का उपयोग कर सकते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

डेटा। पढ़ने/लिखने Object।

**वापसी:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

डेटा। पढ़ने/लिखने Object।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject