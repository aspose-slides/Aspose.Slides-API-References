---
title: ICachedChartValue
second_title: Aspose.Slides for Java API 参考
description: 表示缓存的图表值，例如 X、Y、气泡大小或主值。
type: docs
url: /zh/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

表示缓存的图表值（例如 X、Y、气泡大小或主值）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getData()](#getData--) | 获取缓存的数据对象。 |
| [toDouble()](#toDouble--) | 将缓存值转换为 double。 |
### getData() {#getData--}
```
public abstract Object getData()
```


获取缓存的数据对象。 只读 Object .

**返回：**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


将缓存值转换为 double。

**返回：**
double - 数值表示，或者如果 Data (\#getData.getData) 为 null 或者无法转换为 double，则为 Double.NaN。