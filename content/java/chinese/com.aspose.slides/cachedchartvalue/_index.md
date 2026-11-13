---
title: CachedChartValue
second_title: Aspose.Slides for Java API 参考
description: 表示缓存的图表值，例如 X、Y、气泡大小或主值。
type: docs
url: /zh/com.aspose.slides/cachedchartvalue/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

表示缓存的图表值（例如 X、Y、气泡大小或主值）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [toString()](#toString--) | 返回缓存值的字符串表示形式。 |
| [toDouble()](#toDouble--) | 将缓存值转换为 double。 |
| [getData()](#getData--) | 获取缓存的数据对象。 |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

返回缓存值的字符串表示形式。

**返回值：**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```

将缓存值转换为 double。

**返回值：**
double - 数值表示，或如果 Data (\#getData.getData/\#setData(Object).setData(Object)) 为 null 或无法转换为 double，则为 Double.NaN。
### getData() {#getData--}
```
public final Object getData()
```

获取缓存的数据对象。只读  Object .

**返回值：**
java.lang.Object