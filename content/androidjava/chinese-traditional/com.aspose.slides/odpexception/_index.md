---
title: OdpException
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表標準的內部例外類型。
type: docs
url: /zh-hant/com.aspose.slides/odpexception/
---
**繼承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

代表一種標準的內部例外類型。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [OdpException()](#OdpException--) | Default constructor |
| [OdpException(String message)](#OdpException-java.lang.String-) | Constructor allowing a message to be added to this exception. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Constructor for an exception containing a message and an embedded exception. |
### OdpException() {#OdpException--}
```
public OdpException()
```


Default constructor

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


Constructor allowing a message to be added to this exception.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


Constructor for an exception containing a message and an embedded exception.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | 原始例外 |