---
title: CellInvalidReferenceException
second_title: Aspose.Slides Android 版 Java API 参考
description: 当遇到无效的单元格引用时抛出的异常。
type: docs
url: /zh/com.aspose.slides/cellinvalidreferenceexception/
---
**继承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

当遇到无效的单元格引用时抛出的异常。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | 初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。 |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | 使用指定的错误消息初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。 |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | 使用指定的错误消息和导致此异常的内部异常引用，初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。 |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | 使用指定的错误消息和无效的单元格引用，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getReference()](#getReference--) | 获取无效的单元格引用。 |

### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

使用指定的错误消息初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

使用指定的错误消息和导致此异常的内部异常引用，初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| innerException | java.lang.RuntimeException | 导致当前异常的异常。 |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

使用指定的错误消息和无效的单元格引用，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| reference | java.lang.String | 无效的单元格引用。 |

### getReference() {#getReference--}
```
public final String getReference()
```

获取无效的单元格引用。

**返回：**
java.lang.String