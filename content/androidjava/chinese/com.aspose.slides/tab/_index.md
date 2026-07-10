---
title: Tab
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示文本的制表符。
type: docs
url: /zh/com.aspose.slides/tab/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

表示文本的制表符。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | 创建新的 Tab |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 返回或设置制表符的位置。 |
| [setPosition(double value)](#setPosition-double-) | 返回或设置制表符的位置。 |
| [getAlignment()](#getAlignment--) | 返回或设置制表符的对齐样式。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或设置制表符的对齐样式。 |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 将当前实例与同类型的另一个对象进行比较。 |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

创建新的 Tab

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | double | 制表符位置。 |
| align | int | 对齐方式。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

返回或设置制表符的位置。分配此属性可能会更改制表符在集合中的索引并使 Enumerator 失效。可读写 double。

**返回：**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

返回或设置制表符的位置。分配此属性可能会更改制表符在集合中的索引并使 Enumerator 失效。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

返回或设置制表符的对齐样式。可读写 [TabAlignment](../../com.aspose.slides/tabalignment)。

**返回：**
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

**返回：**
int - 一个 32 位整数，用于指示比较对象的相对顺序。返回值的含义如下：

 * < 0 - 此实例小于 obj。
 * = 0 - 此实例等于 obj。
 * > 0 - 此实例大于 obj。