---
title: Details_WebException()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新實例。
type: docs
weight: 40
url: /zh-hant/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() 建構函式

建立新實例。

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) 建構函式

建立新實例。

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 錯誤描述。 |

## Details_WebException::Details_WebException(String, Exception) 建構函式

建立新實例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |

## Details_WebException::Details_WebException(String, WebExceptionStatus) 建構函式

建立新實例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 狀態碼。 |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) 建構函式

建立新實例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外訊息。 |
| innerException | [Exception](../../../system/exception/) | 內部例外。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 狀態碼。 |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | 與當前例外相關聯的 Web 回應。 |

## 另請參閱

* 列舉 [WebExceptionStatus](../../webexceptionstatus/)
* 型別別名 [Exception](../../../system/exception/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Details_WebException](../)
* 類別 [String](../../../system/string/)
* 類別 [WebResponse](../../webresponse/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)