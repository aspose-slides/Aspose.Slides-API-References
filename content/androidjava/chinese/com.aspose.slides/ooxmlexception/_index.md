---
title: OOXMLException
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示一种与 Office Open XML 文件格式相关的标准内部异常类型。
type: docs
url: /zh/com.aspose.slides/ooxmlexception/
---
**继承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

表示一种与 Office Open XML 文件格式相关的标准内部异常类型。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | 默认构造函数。 |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | 允许向此异常添加消息的构造函数。 |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | 包含消息和嵌入式异常的异常构造函数。 |

### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

默认构造函数。

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

允许向此异常添加消息的构造函数。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | message |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

包含消息和嵌入式异常的异常构造函数。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | 原始异常 |