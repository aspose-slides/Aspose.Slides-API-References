---
title: CachedChartValue
second_title: Aspose.Slides for Java API 參考文件
description: 表示快取的圖表值，例如 X、Y、氣泡大小或主要值。
type: docs
url: /zh-hant/com.aspose.slides/cachedchartvalue/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)  
```
public class CachedChartValue implements ICachedChartValue
```

表示快取的圖表值（例如 X、Y、氣泡大小或主要值）。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [toString()](#toString--) | 返回快取值的字串表示形式。 |
| [toDouble()](#toDouble--) | 將快取值轉換為 double。 |
| [getData()](#getData--) | 取得快取資料物件。 |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

返回快取值的字串表示形式。

**傳回:**  
java.lang.String

### toDouble() {#toDouble--}
```
public final double toDouble()
```

將快取值轉換為 double。

**傳回:**  
double - 數值表示形式，或如果 Data (\#getData.getData/\#setData(Object).setData(Object)) 為 null 或無法轉換為 double，則為 Double.NaN。

### getData() {#getData--}
```
public final Object getData()
```

取得快取資料物件。唯讀 Object 。

**傳回:**  
java.lang.Object