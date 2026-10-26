---
title: Create()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 URI 建立 WebRequest 類別的新實例。
type: docs
weight: 53
url: /zh-hant/system.net/webrequest/create/
---
## WebRequest::Create(String) 方法


建立使用指定 URI 的 [WebRequest](../) 類別的新實例。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(String requestUriString)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 用於建立 [WebRequest](../) 類別的新實例的 URI。 |

### 返回值

新建立的 WebRequest 類別實例。

## WebRequest::Create(System::SharedPtr\<Uri\>) 方法


建立使用指定 URI 的 [WebRequest](../) 類別的新實例。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(System::SharedPtr<Uri> requestUri)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於建立 [WebRequest](../) 類別的新實例的 URI。 |

### 返回值

新建立的 WebRequest 類別實例。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [WebRequest](../)
* 類別 [String](../../../system/string/)
* 類別 [Uri](../../../system/uri/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)