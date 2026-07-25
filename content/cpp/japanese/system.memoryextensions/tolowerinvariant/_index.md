---
title: ToLowerInvariant()
second_title: Aspose.Slides の C++ API リファレンス
description: 不変カルチャーを使用して文字を小文字に変換します。
type: docs
weight: 456
url: /ja/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 関数

文字を不変のカルチャーで小文字に変換します。

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 変換する元の文字スパン |
| destination | [Span](../../system/span/)\<char16_t\>\& | 変換された文字を格納する宛先スパン |

### 戻り値

変換された文字数、または宛先が小さすぎる場合は -1

## 参照

* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* ネームスペース [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)