---
title: WriteLine()
second_title: Aspose.Slides の C++ API リファレンス
description: デバッグ インターフェイスに行を書き込みます。
type: docs
weight: 27
url: /ja/system.diagnostics/debug/writeline/
---
## Debug::WriteLine(const String\&) メソッド

Writes line to debug interface.

```cpp
static void System::Diagnostics::Debug::WriteLine(const String &message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 書き込むメッセージ。 |

## Debug::WriteLine(const String\&, const String\&) メソッド

Writes line to debug interface.

```cpp
static void System::Diagnostics::Debug::WriteLine(const String &message, const String &message2)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | const [String](../../../system/string/)\& | 書き込むメッセージ。 |
| message2 | const [String](../../../system/string/)\& | 追加のメッセージ。 |

## Debug::WriteLine(const char_t *) メソッド

Writes line to debug interface.

```cpp
static void System::Diagnostics::Debug::WriteLine(const char_t *message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | const char_t * | 書き込むメッセージ。 |

## Debug::WriteLine(const SharedPtr\<Object\>\&) メソッド

Writes line to debug interface.

```cpp
static void System::Diagnostics::Debug::WriteLine(const SharedPtr<Object> &obj)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) をダンプする。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* 構造体 [Debug](../)
* 名前空間 [System::Diagnostics](../../)
* ライブラリ [Aspose.Slides](../../../)