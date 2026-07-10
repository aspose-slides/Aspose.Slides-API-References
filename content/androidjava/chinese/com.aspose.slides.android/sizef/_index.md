---
title: SizeF
second_title: Aspose.Slides for Android via Java API 参考
description: 用于以任意单位的浮点值描述宽度和高度的类。
type: docs
url: /zh/com.aspose.slides.android/sizef/
---
**继承:**
java.lang.Object
```
public class SizeF
```

用于以任意单位的浮点值描述宽度和高度的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | 创建一个新的 SizeF 实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取尺寸的宽度。 |
| [getHeight()](#getHeight--) | 获取尺寸的高度。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查此尺寸是否等于另一个尺寸。 |
| [hashCode()](#hashCode--) | {@inheritDoc} |
| [toString()](#toString--) | 返回以 “WxH” 格式表示的尺寸字符串。 |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

创建一个新的 SizeF 实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 尺寸的宽度 |
| height | float | 尺寸的高度 |

### getWidth() {#getWidth--}
```
public float getWidth()
```

获取尺寸的宽度。

**返回值:**
float - 宽度

### getHeight() {#getHeight--}
```
public float getHeight()
```

获取尺寸的高度。

**返回值:**
float - 高度

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

检查此尺寸是否等于另一个尺寸。

当且仅当两个尺寸的宽度和高度全部相同时，它们视为相等。

为此，如果对每个尺寸的宽度/高度浮点值调用 Float#floatToIntBits(float) 方法返回相同的 int 值，则认为它们相等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**返回值:**
boolean - 如果对象相等则为 true，否则为 false

### hashCode() {#hashCode--}
```
public int hashCode()
```

**返回值:**
int

### toString() {#toString--}
```
public String toString()
```

返回以 “WxH” 格式表示的尺寸字符串。

**返回值:**
java.lang.String - 尺寸的字符串表示