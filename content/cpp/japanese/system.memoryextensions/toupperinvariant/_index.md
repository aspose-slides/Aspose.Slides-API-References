---
title: ToUpperInvariant()
second_title: Aspose.Slides for C++ API リファレンス
description: 不変カルチャーを使用して文字を大文字に変換します。
type: docs
weight: 482
url: /ja/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 関数

不変カルチャーを使用して文字を大文字に変換します。

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 変換対象の文字スパン |
| destination | [Span](../../system/span/)\<char16_t\>\& | 変換された文字を格納する宛先スパン |

### 戻り値

変換された文字数、または宛先が小さすぎる場合は -1

## 関連項目

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)