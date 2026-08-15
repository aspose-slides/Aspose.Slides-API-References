---
title: TryCreate()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個表示指定 URI 的 Uri 物件；參數指定 URI 的類型。
type: docs
weight: 508
url: /zh-hant/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) 方法


建立一個 [Uri](../) 物件，用於表示指定的 URI；參數指定 URI 類型。

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 要由所建構的物件表示的字串 URI |
| uriKind | [UriKind](../../urikind/) | 指定 URI 類型 |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 輸出參數；若建構成功，於方法返回時指向新建的 [Uri](../) 物件 |

### 傳回值

若建構成功則傳回 True，否則傳回 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) 方法


從指定的 [Uri](../) 物件（表示基礎 URI）以及相對 URI 的字串表示，建立一個 [Uri](../) 物件。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基礎 URI |
| relativeUri | const [String](../../string/)\& | 要加入基礎 URI 的相對 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 輸出參數；若建構成功，於方法返回時指向新建的 [Uri](../) 物件 |

### 傳回值

若建構成功則傳回 True，否則傳回 false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) 方法


從指定的基礎 URI 與相對 URI 建立一個 [Uri](../) 物件。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基礎 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 要加入基礎 URI 的相對 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 輸出參數；若建構成功，於方法返回時指向新建的 [Uri](../) 物件 |

### 傳回值

若建構成功則傳回 True，否則傳回 false

## 另請參閱

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)