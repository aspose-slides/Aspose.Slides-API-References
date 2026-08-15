---
title: Uri()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個代表指定 URI 的 Uri 物件。
type: docs
weight: 287
url: /zh-hant/system/uri/uri/
---
## Uri::Uri(const String\&) 建構函式

建構一個代表指定 URI 的 [Uri](../) 物件。

```cpp
System::Uri::Uri(const String &uriString)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 將由被構造的物件所表示的字串 URI |

## Uri::Uri(const String\&, bool) 建構函式

建構一個代表指定 URI 的 [Uri](../) 物件；可透過參數指定是否要對 URI 進行跳脫。

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 將由被構造的物件所表示的字串 URI |
| dontEscape | **bool** | 指定是否不對 URI 進行跳脫 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) 建構函式

建構一個 [Uri](../) 物件，使用指定的代表基礎 URI 的 [Uri](../) 物件以及相對 URI 的字串表示；可透過參數指定是否要對 URI 進行跳脫。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基礎 URI |
| relativeUri | const [String](../../string/)\& | 要加入基礎 URI 的相對 URI |
| dontEscape | **bool** | 指定是否不對 URI 進行跳脫 |

## Uri::Uri(const String\&, UriKind) 建構函式

建構一個代表指定 URI 的 [Uri](../) 物件；可透過參數指定 URI 的類型。

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 將由被構造的物件所表示的字串 URI |
| uriKind | [UriKind](../../urikind/) | 指定 URI 的類型 |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) 建構函式

建構一個 [Uri](../) 物件，使用指定的基礎 URI 與相對 URI。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基礎 URI |
| relativeUri | const [String](../../string/)\& | 要加入基礎 URI 的相對 URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 建構函式

建構一個 [Uri](../) 物件，使用指定的基礎 URI 與相對 URI。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 基礎 URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 要加入基礎 URI 的相對 URI |

## 參見

* 列舉 [UriKind](../../urikind/)
* 類型定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Uri](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)