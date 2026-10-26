---
title: CreateHttp()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 URI 建立 WebRequest 類別的新執行個體。
type: docs
weight: 79
url: /zh-hant/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) 方法

使用指定的 URI 建立 [WebRequest](../) 類別的新執行個體。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 用於建立 [WebRequest](../) 類別新執行個體的 URI。 |

### 傳回值

新建立的 WebRequest-class 執行個體。

## 備註

當指定的 URI 以除 [http://](http://) 或 [https://](https://) 之外的任何方案開頭時，將拋出 NotSupportedException。

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) 方法

使用指定的 URI 建立 [WebRequest](../) 類別的新執行個體。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 用於建立 [WebRequest](../) 類別新執行個體的 URI。 |

### 傳回值

新建立的 WebRequest-class 執行個體。

## 備註

當指定的 URI 以除 [http://](http://) 或 [https://](https://) 之外的任何方案開頭時，將拋出 NotSupportedException。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [HttpWebRequest](../../httpwebrequest/)
* 類別 [String](../../../system/string/)
* 類別 [WebRequest](../)
* 類別 [Uri](../../../system/uri/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)