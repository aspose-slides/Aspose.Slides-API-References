---
title: HtmlEncode()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML フラグメントをエンコードします。
type: docs
weight: 40
url: /ja/system.web/httputility/htmlencode/
---
## HttpUtility::HtmlEncode(const String\&) メソッド


HTML フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const String &str)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードする HTML フラグメント。 |

### 戻り値

エンコードされた HTML フラグメント。

## HttpUtility::HtmlEncode(const SharedPtr\<Object\>\&) メソッド


HTML フラグメントをエンコードします。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const SharedPtr<Object> &value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | エンコードする HTML フラグメント。 |

### 戻り値

エンコードされた HTML フラグメント。

## HttpUtility::HtmlEncode(const String\&, const SharedPtr\<IO::TextWriter\>\&) メソッド


HTML フラグメントをエンコードします。

```cpp
static void System::Web::HttpUtility::HtmlEncode(const String &str, const SharedPtr<IO::TextWriter> &output)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | エンコードする HTML フラグメント。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 出力用の TextWriter オブジェクト。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [HttpUtility](../)
* クラス [Object](../../../system/object/)
* クラス [TextWriter](../../../system.io/textwriter/)
* 名前空間 [System::Web](../../)
* ライブラリ [Aspose.Slides](../../../)