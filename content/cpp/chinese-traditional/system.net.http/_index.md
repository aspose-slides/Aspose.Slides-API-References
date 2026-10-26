---
title: "System::Net::Http"
second_title: Aspose.Slides C++ API 參考文件
description: 
type: docs
weight: 677
url: /zh-hant/system.net.http/
---
## 類別

| 類別 | 說明 |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | 將 HTTP 內容表示為位元組陣列。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [Details_HttpRequestException](./details_httprequestexception/) | 基礎例外類別由 [HttpClient](./httpclient/) 和 [HttpMessageHandler](./httpmessagehandler/) 類別拋出。切勿手動建立此類別的實例。請改用 HttpRequestException 類別。切勿將 HttpRequestException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [HttpClient](./httpclient/) | 表示用於發送請求與接收回應的 HTTP 客戶端基底類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpClientHandler](./httpclienthandler/) | 表示 [HttpClient](./httpclient/) 類別使用的預設訊息處理程序。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpContent](./httpcontent/) | 表示 HTTP 實體的內容。[Object](../system/object/) 此類別應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpMessageHandler](./httpmessagehandler/) | 表示 HTTP 訊息處理程序的基礎類型。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpMessageInvoker](./httpmessageinvoker/) | 允許應用程式在 HTTP 處理程序鏈上呼叫 Send 方法。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpMethod](./httpmethod/) | 表示 HTTP 方法。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpRequestMessage](./httprequestmessage/) | 表示 HTTP 請求訊息。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpResponseMessage](./httpresponsemessage/) | 表示 HTTP 回應訊息。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |
| [HttpUtilities](./httputilities/) | 包含實用方法。 |
| [StringContent](./stringcontent/) | 將 HTTP 內容表示為字串。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。 |

## 函式

| 函式 | 說明 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | 指示何時應完成 [HttpClient](./httpclient/) 操作。 |
| [HttpParseResult](./httpparseresult/) | 指示解析結果。 |

## 型別定義

| 型別定義 | 說明 |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |