---
title: CellCircularReferenceException
second_title: Aspose.Slides for Android via Java API 参考
description: 当检测到一个或多个循环引用时抛出的异常，其中公式直接或间接引用了其自身的单元格。
type: docs
url: /zh/com.aspose.slides/cellcircularreferenceexception/
---
**继承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

当检测到一个或多个循环引用时抛出的异常，其中公式直接或间接引用了其自身的单元格。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | 初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。 |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 使用指定的错误消息初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。 |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 使用指定的错误消息和指向导致此异常的内部异常的引用初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。 |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 使用指定的错误消息和循环单元格引用初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getReference()](#getReference--) | 获取循环单元格引用。 |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

使用指定的错误消息初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

使用指定的错误消息和指向导致此异常的内部异常的引用初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| innerException | java.lang.RuntimeException | 导致当前异常的异常。 |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

使用指定的错误消息和循环单元格引用初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 类的新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| reference | java.lang.String | 循环单元格引用。 |

### getReference() {#getReference--}
```
public final String getReference()
```

获取循环单元格引用。

**返回:**  
java.lang.String