---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a value of a chart.
type: docs
url: /hi/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

चार्ट का मान दर्शाता है।
## विधियां

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | दर्शाता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं। |
| [setDataSourceType(int value)](#setDataSourceType-int-) | दर्शाता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं। |
| [getData()](#getData--) | पढ़ें/लिखें Object. |
| [setData(Object value)](#setData-java.lang.Object-) | पढ़ें/लिखें Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

दर्शाता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं। दूसरे शब्दों में यह Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। यह प्रॉपर्टी केवल पढ़ने योग्य है। इस प्रॉपर्टी का मान बदलने के लिए आप ChartDataPointCollection.DataSourceTypeFor<...> प्रॉपर्टीज़ में से कोई एक उपयोग कर सकते हैं। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))।

**रिटर्न:**  
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

दर्शाता है कि AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं। दूसरे शब्दों में यह Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। यह प्रॉपर्टी केवल पढ़ने योग्य है। इस प्रॉपर्टी का मान बदलने के लिए आप ChartDataPointCollection.DataSourceTypeFor<...> प्रॉपर्टीज़ में से कोई एक उपयोग कर सकते हैं। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))।

**परामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

पढ़ें/लिखें Object.

**रिटर्न:**  
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

पढ़ें/लिखें Object.

**परामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |