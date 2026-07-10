---
title: OdpException
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种标准的内部异常类型。
type: docs
url: /zh/com.aspose.slides/odpexception/
---
**继承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

表示一种标准的内部异常类型。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OdpException()](#OdpException--) | 默认构造函数 |
| [OdpException(String message)](#OdpException-java.lang.String-) | 允许向此异常添加消息的构造函数。 |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | 用于包含消息和嵌入异常的构造函数。 |

### OdpException() {#OdpException--}
```
public OdpException()
```

默认构造函数

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

允许向此异常添加消息的构造函数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 消息 |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

用于包含消息和嵌入异常的构造函数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 消息 |
| exception | java.lang.RuntimeException | 原始异常 |