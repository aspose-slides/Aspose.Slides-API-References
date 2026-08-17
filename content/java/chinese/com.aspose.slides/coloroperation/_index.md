---
title: ColorOperation
second_title: Aspose.Slides for Java API 参考
description: 表示用于颜色转换的不同颜色操作。
type: docs
url: /zh/com.aspose.slides/coloroperation/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

表示用于颜色转换的不同颜色操作。不可变对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 创建新的颜色转换操作。 |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 创建新的颜色转换操作。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOperationType()](#getOperationType--) | 返回或设置操作的类型。 |
| [getParameter()](#getParameter--) | 返回操作的参数。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 ColorOperation 实例是否相等。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数，可用于哈希算法和哈希表等数据结构。 |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

创建新的颜色转换操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| op | int | 操作类型。 |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

创建新的颜色转换操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| op | int | 操作类型。 |
| parameter | float | 操作参数。 |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

返回或设置操作的类型。只读 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)。

**返回:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

返回操作的参数。只读 float。

**返回:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 ColorOperation 实例是否相等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 与当前 ColorOperation 比较的 ColorOperation。 |

**返回:**
boolean - **true** 如果指定的 ColorOperation 等于当前 ColorOperation；否则，**false**。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数，可用于哈希算法和哈希表等数据结构。

**返回:**
int