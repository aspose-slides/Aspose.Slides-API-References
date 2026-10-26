---
title: Uri()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI を表す Uri オブジェクトを構築します。
type: docs
weight: 287
url: /ja/system/uri/uri/
---
## Uri::Uri(const String\&) コンストラクタ

指定された URI を表す [Uri](../) オブジェクトを構築します。

```cpp
System::Uri::Uri(const String &uriString)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | オブジェクトが表す文字列 URI |

## Uri::Uri(const String\&, bool) コンストラクタ

指定された URI を表す [Uri](../) オブジェクトを構築します。引数は URI をエスケープするかどうかを指定します。

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | オブジェクトが表す文字列 URI |
| dontEscape | **bool** | URI をエスケープしないかどうかを指定します |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) コンストラクタ

ベース URI を表す [Uri](../) オブジェクトと相対 URI の文字列表現から [Uri](../) オブジェクトを構築します。引数は URI をエスケープするかどうかを指定します。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI |
| relativeUri | const [String](../../string/)\& | ベース URI に追加される相対 URI |
| dontEscape | **bool** | URI をエスケープしないかどうかを指定します |

## Uri::Uri(const String\&, UriKind) コンストラクタ

指定された URI を表す [Uri](../) オブジェクトを構築します。引数は URI の種類を指定します。

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | オブジェクトが表す文字列 URI |
| uriKind | [UriKind](../../urikind/) | URI の種類を指定します |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) コンストラクタ

指定されたベース URI と相対 URI から [Uri](../) オブジェクトを構築します。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI |
| relativeUri | const [String](../../string/)\& | ベース URI に追加される相対 URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) コンストラクタ

指定されたベース URI と相対 URI から [Uri](../) オブジェクトを構築します。

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI に追加される相対 URI |

## 参照

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Uri](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)