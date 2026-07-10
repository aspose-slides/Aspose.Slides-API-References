---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API 参考
description: 提供对折线图或股票图的上/下柱的访问。
type: docs
url: /zh/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

提供对折线图或股票图的上/下柱的访问。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | 返回上柱的格式。 |
| [getDownBarsFormat()](#getDownBarsFormat--) | 返回下柱的格式。 |
| [hasUpDownBars()](#hasUpDownBars--) | 确定图表是否具有上/下柱。 |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | 确定图表是否具有上/下柱。 |
| [getGapWidth()](#getGapWidth--) | 返回或设置间隙宽度。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 返回或设置间隙宽度。 |

### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

返回上柱的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

返回下柱的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

确定图表是否具有上/下柱。可读写布尔值。

**返回：**
boolean

### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

确定图表是否具有上/下柱。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

返回或设置间隙宽度。可读写整数。

**返回：**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

返回或设置间隙宽度。可读写整数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |