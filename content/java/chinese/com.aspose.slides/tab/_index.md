---
title: Tab
second_title: Aspose.Slides Java API 参考
description: 表示文本的制表符。
type: docs
url: /zh/com.aspose.slides/tab/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已实现的接口：**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

表示文本的制表符。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

创建新的 Tab

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Align. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值：**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

返回或设置制表符的位置。分配此属性可能会更改集合中制表符的索引并使 Enumerator 失效。可读写 double。

**返回值：**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

返回或设置制表符的位置。分配此属性可能会更改集合中制表符的索引并使 Enumerator 失效。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

返回或设置制表符的对齐样式。可读写 [TabAlignment](../../com.aspose.slides/tabalignment)。

**返回值：**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

返回或设置制表符的对齐样式。可读写 [TabAlignment](../../com.aspose.slides/tabalignment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

比较当前实例与同类型的另一个对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的对象。 |

**返回值：**
int - A 32-bit integer that indicates the relative order of the comparands. The return value has these meanings: 

 *  < 0 - This instance is less than obj.
 *  = 0 - This instance is equal to obj.
 *  > 0 - This instance is greater than obj.