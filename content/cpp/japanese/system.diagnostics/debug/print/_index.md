---
title: Print()
second_title: Aspose.Slides for C++ API リファレンス
description: デバッグ インターフェイスにメッセージを出力します。
type: docs
weight: 79
url: /ja/system.diagnostics/debug/print/
---
## Debug::Print(const String\&) メソッド

Print message to debug interface.

```cpp
static void System::Diagnostics::Debug::Print(const String &message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 書き込むメッセージ。 |

## Debug::Print(const String\&, const System::ArrayPtr\<SharedPtr\<System::Object\>\>\&) メソッド

Print message to debug interface.

```cpp
static void System::Diagnostics::Debug::Print(const String &format, const System::ArrayPtr<SharedPtr<System::Object>> &args)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 書式文字列。 |
| args | const [System::ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\>\& | 書式文字列に置換する引数。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* 構造体 [Debug](../)
* 名前空間 [System::Diagnostics](../../)
* ライブラリ [Aspose.Slides](../../../)