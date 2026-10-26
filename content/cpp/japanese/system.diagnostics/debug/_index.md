---
title: Debug
second_title: Aspose.Slides for C++ API リファレンス
description: 登録されたリスナーへデバッグ情報を送信できるデバッグメソッドのコレクションです。すべての出力関数は Debug のみで動作します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成すべきではありません。
type: docs
weight: 105
url: /ja/system.diagnostics/debug/
---
## デバッグ構造体

Collection of debug methods allowing it sending debug information to registered listeners. All output functions work in [Debug](./) only. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Debug
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | 条件をアサートし、失敗時に情報を送信します。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | 条件をアサートし、失敗時に情報を送信します。 |
| static void [Assert](./assert/)(**bool**, const char *) | 条件をアサートし、失敗時に情報を送信します。 |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 条件をアサートし、失敗時に情報を送信します。 |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | 失敗メッセージを送信します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | リスナーの静的リストにアクセスします。 |
| static void [Print](./print/)(const [String](../../system/string/)\&) | デバッグインターフェイスにメッセージを出力します。 |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | デバッグインターフェイスにメッセージを出力します。 |
| static void [Write](./write/)(const [String](../../system/string/)\&) | デバッグインターフェイスに文字列を書き込みます。 |
| static void [Write](./write/)(const char_t *) | デバッグインターフェイスに文字列を書き込みます。 |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | 条件が真の場合にデバッグインターフェイスに文字列を書き込みます。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | デバッグインターフェイスに行を書き込みます。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | デバッグインターフェイスに行を書き込みます。 |
| static void [WriteLine](./writeline/)(const char_t *) | デバッグインターフェイスに行を書き込みます。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | デバッグインターフェイスに行を書き込みます。 |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | 条件が真の場合にデバッグインターフェイスに行を書き込みます。 |

## 参照

* 名前空間 [System::Diagnostics](../)
* ライブラリ [Aspose.Slides](../../)