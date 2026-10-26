---
title: Size
second_title: 适用于 Android 的 Aspose.Slides 通过 Java API 参考
description: 用于描述宽度和高度维度（以任意单位）的类。
type: docs
url: /zh/com.aspose.slides.android/size/
---
**继承：**
java.lang.Object
```
public class Size
```

用于描述宽度和高度维度（以任意单位）的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | 创建一个新的 Size 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取 Size 的宽度。 |
| [getHeight()](#getHeight--) | 获取 Size 的高度。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查此 Size 是否等于另一个 Size。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 返回以 "WxH" 格式表示的 Size 字符串 |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


创建一个新的 Size 实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | The width of the size |
| height | int | The height of the size |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取 Size 的宽度。

**返回值：**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取 Size 的高度。

**返回值：**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查此 Size 是否等于另一个 Size。

当且仅当两个 Size 的宽度和高度都相等时，它们才相等。

Size 对象永远不等于任何其他类型的对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**返回值：**
boolean -  true  如果对象相等，则返回 true；否则返回 false
### hashCode() {#hashCode--}
```
public int hashCode()
```




**返回值：**
int
### toString() {#toString--}
```
public String toString()
```


返回以 "WxH" 格式表示的 Size 字符串

**返回值：**
java.lang.String - Size 的字符串表示