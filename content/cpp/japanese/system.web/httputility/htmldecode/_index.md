---
title: HtmlDecode()
second_title: Aspose.Slides for C++ API リファレンス
description: Html フラグメントをデコードします。
type: docs
weight: 27
url: /ja/system.web/httputility/htmldecode/
---
## HttpUtility::HtmlDecode(const String\&) method


Html フラグメントをデコードします。

```cpp
static String System::Web::HttpUtility::HtmlDecode(const String &str)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | デコードする Html フラグメント。 |

### 戻り値

デコードされた Html フラグメント。

## HttpUtility::HtmlDecode(const String\&, const SharedPtr\<IO::TextWriter\>\&) method


Html フラグメントをデコードします。

```cpp
static void System::Web::HttpUtility::HtmlDecode(const String &str, const SharedPtr<IO::TextWriter> &output)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | デコードする Html フラグメント。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 出力用の TextWriter オブジェクト。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [HttpUtility](../)
* クラス [TextWriter](../../../system.io/textwriter/)
* 名前空間 [System::Web](../../)
* ライブラリ [Aspose.Slides](../../../)