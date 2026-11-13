---
title: ICachedChartValue
second_title: Aspose.Slides for Java API 參考文件
description: 表示已快取的圖表值，例如 X、Y、氣泡大小或主要值。
type: docs
url: /zh-hant/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

表示已快取的圖表值（例如 X、Y、氣泡大小或主要值）。
## 方法

| Method | Description |
| --- | --- |
| [getData()](#getData--) | 取得已快取的資料物件。 |
| [toDouble()](#toDouble--) | 將已快取的值轉換為 double。 |
### getData() {#getData--}
```
public abstract Object getData()
```


取得已快取的資料物件。唯讀  Object .

**返回值：**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


將已快取的值轉換為 double。

**返回值：**
double - 數值表示，若 Data (\#getData.getData) 為 null 或無法轉換為 double，則為 Double.NaN。