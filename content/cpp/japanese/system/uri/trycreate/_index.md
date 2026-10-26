---
title: TryCreate()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI を表す Uri オブジェクトを構築します。引数は URI の種類を指定します。
type: docs
weight: 508
url: /ja/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) メソッド


指定された URI を表す [Uri](../) オブジェクトを構築します。引数は URI の種類を指定します。

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | 構築されるオブジェクトが表す文字列形式の URI |
| uriKind | [UriKind](../../urikind/) | URI の種類を指定します |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 構築が成功した場合に、メソッドの戻り値として新しく構築された [Uri](../) オブジェクトを指す出力引数 |

### 戻り値

構築が成功した場合は true、そうでない場合は false です

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) メソッド


指定された [Uri](../) オブジェクト（ベース URI を表す）と相対 URI の文字列表現から [Uri](../) オブジェクトを構築します。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI |
| relativeUri | const [String](../../string/)\& | ベース URI に追加される相対 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 構築が成功した場合に、メソッドの戻り値として新しく構築された [Uri](../) オブジェクトを指す出力引数 |

### 戻り値

構築が成功した場合は true、そうでない場合は false です

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) メソッド


指定されたベース URI と相対 URI から [Uri](../) オブジェクトを構築します。

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ベース URI に追加される相対 URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 構築が成功した場合に、メソッドの戻り値として新しく構築された [Uri](../) オブジェクトを指す出力引数 |

### 戻り値

構築が成功した場合は true、そうでない場合は false です

## 参照

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Uri](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)