---
title: CellInvalidFormulaException
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 当计算公式不正确或未被解析时抛出的异常。
type: docs
url: /zh/com.aspose.slides/cellinvalidformulaexception/
---
**继承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

当计算公式不正确或未被解析时抛出的异常。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例。 |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | 使用指定的错误消息初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例。 |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | 使用指定的错误消息和指向导致此异常的内部异常的引用来初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例。 |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | 使用指定的错误消息和包含无效公式的单元格引用来初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getReference()](#getReference--) | 获取包含无效公式的单元格引用。 |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例。

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例，使用指定的错误消息。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例，使用指定的错误消息和指向导致此异常的内部异常的引用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| innerException | java.lang.RuntimeException | 导致当前异常的内部异常。 |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 类的新实例，使用指定的错误消息和包含无效公式的单元格引用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述错误的字符串。 |
| reference | java.lang.String | 描述对内部异常的引用的字符串。 |

### getReference() {#getReference--}
```
public final String getReference()
```

获取包含无效公式的单元格引用。

**返回值：**
java.lang.String