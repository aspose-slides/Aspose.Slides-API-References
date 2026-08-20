---
title: OdpException
second_title: Aspose.Slides for Java API 參考
description: 表示一種標準的內部例外類型。
type: docs
url: /zh-hant/com.aspose.slides/odpexception/
---
**繼承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception  
```
public class OdpException extends System.Exception
```

表示一種標準的內部例外類型。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [OdpException()](#OdpException--) | 預設建構函式 |
| [OdpException(String message)](#OdpException-java.lang.String-) | 允許向此例外新增訊息的建構函式。 |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | 用於包含訊息與嵌入例外的建構函式。 |

### OdpException() {#OdpException--}
```
public OdpException()
```

預設建構函式

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

允許向此例外新增訊息的建構函式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 訊息 |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

用於包含訊息與嵌入例外的建構函式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 訊息 |
| exception | java.lang.RuntimeException | 原始例外 |