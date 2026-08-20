---
title: IBaseChartValue
second_title: Aspose.Slides 的 Java API 參考
description: 表示圖表的值。
type: docs
url: /zh-hant/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

表示圖表的值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定 AsCell 或 AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定 AsCell 或 AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [getData()](#getData--) | 讀/寫 Object。 |
| [setData(Object value)](#setData-java.lang.Object-) | 讀/寫 Object。 |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

指定 AsCell 或 AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換句話說，它指定 Data 屬性的值類型。此屬性為唯讀。若要變更此屬性的值，您可以使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。讀/寫 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**傳回值:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

指定 AsCell 或 AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換句話說，它指定 Data 屬性的值類型。此屬性為唯讀。若要變更此屬性的值，您可以使用 ChartDataPointCollection.DataSourceTypeFor<...> 屬性之一。讀/寫 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

讀/寫 Object。

**傳回值:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

讀/寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |