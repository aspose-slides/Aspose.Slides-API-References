---
title: ToLower()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたカルチャーを使用して文字を小文字に変換します。
type: docs
weight: 443
url: /ja/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 関数

指定されたカルチャーを使用して文字を小文字に変換します。

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Arguments

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 変換する元の文字スパン |
| destination | [Span](../../system/span/)\<char16_t\>\& | 変換された文字を格納する宛先スパン |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 変換に使用するカルチャー（現在のカルチャーの場合はnullptr） |

### 戻り値

変換された文字数、または宛先が小さすぎる場合は -1

## 関連項目

* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* クラス [Span](../../system/span/)
* クラス [CultureInfo](../../system.globalization/cultureinfo/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)