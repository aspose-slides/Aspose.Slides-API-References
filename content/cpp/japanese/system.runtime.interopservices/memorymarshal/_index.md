---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API リファレンス
description: メモリーマーシャリングの実装を提供します。C++ 側ではマネージドコードがサポートされていないため、翻訳されたコードとの互換性のためだけに提供されます。これはインスタンスサービスを持たない static 型です。あらゆる手段でインスタンスを作成すべきではありません。
type: docs
weight: 27
url: /ja/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal クラス

メモリーマーシャリングの実装を提供します。C++ 側ではマネージドコードがサポートされていないため、翻訳されたコードとの互換性のためだけに提供されます。これはインスタンスサービスを持たない static 型です。あらゆる手段でインスタンスを作成すべきではありません。

```cpp
class MemoryMarshal
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | プリミティブ型 T の [Span](../../system/span/) をバイトの [Span](../../system/span/) にキャストします。 |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | プリミティブ型 TFrom の [Span](../../system/span/) を別のプリミティブ型 TTo にキャストします。 |

## 参照

* 名前空間 [System::Runtime::InteropServices](../)
* ライブラリ [Aspose.Slides](../../)