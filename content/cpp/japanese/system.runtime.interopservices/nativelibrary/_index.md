---
title: NativeLibrary
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 40
url: /ja/system.runtime.interopservices/nativelibrary/
---
## NativeLibrary クラス




```cpp
class NativeLibrary
```

## メソッド

| Method | 説明 |
| --- | --- |
| static void [Free](./free/)(IntPtr) | 動的ライブラリのロードを解除します。 |
| static IntPtr [GetExport](./getexport/)(IntPtr, const [String](../../system/string/)\&) | 指定されたライブラリ項目のアドレスを取得します。 |
| static IntPtr [Load](./load/)(const [String](../../system/string/)\&) | ネイティブ動的ライブラリをロードします。エラーが発生した場合は例外をスローします。 |
| static **bool** [TryLoad](./tryload/)(const [String](../../system/string/)\&, IntPtr\&) | ネイティブ動的ライブラリをロードします。 |
## 参照

* 名前空間 [System::Runtime::InteropServices](../)
* ライブラリ [Aspose.Slides](../../)