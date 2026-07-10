---
title: ColorOperation
second_title: Aspose.Slides for Android via Java API 参考
description: 表示用于颜色转换的不同颜色操作。
type: docs
url: /zh/com.aspose.slides/coloroperation/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)  
```
public class ColorOperation implements IColorOperation
```

表示用于颜色转换的不同颜色操作。不可变对象。

## Constructors

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 创建新的颜色变换操作。 |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 创建新的颜色变换操作。 |

## Methods

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | 返回或设置操作的类型。 |
| [getParameter()](#getParameter--) | 返回操作的参数。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 ColorOperation 实例是否相等。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。 |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

创建新的颜色变换操作。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | 操作类型。 |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

创建新的颜色变换操作。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | 操作类型。 |
| parameter | float | 操作参数。 |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

返回或设置操作的类型。只读 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)。

**Returns:**  
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

返回操作的参数。只读 float。

**Returns:**  
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 ColorOperation 实例是否相等。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 要与当前 ColorOperation 比较的对象。 |

**Returns:**  
boolean - **true** 如果指定的 ColorOperation 等于当前 ColorOperation；否则，**false**。

### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。

**Returns:**  
int