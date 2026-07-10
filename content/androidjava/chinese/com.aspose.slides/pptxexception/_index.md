---
title: PptxException
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示一种标准的内部异常类型。
type: docs
url: /zh/com.aspose.slides/pptxexception/
---
**继承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

表示一种标准的内部异常类型。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PptxException()](#PptxException--) | 默认构造函数。 |
| [PptxException(String message)](#PptxException-java.lang.String-) | 允许向此异常添加消息的构造函数。 |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | 用于包含消息和内部异常的构造函数。 |

### PptxException() {#PptxException--}
```
public PptxException()
```

默认构造函数。

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

允许向此异常添加消息的构造函数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 消息 |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

用于包含消息和内部异常的构造函数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 消息 |
| exception | java.lang.RuntimeException | 原始异常 |