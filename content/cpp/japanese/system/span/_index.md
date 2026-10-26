---
title: Span
second_title: C++ 用 Aspose.Slides API リファレンス
description: "C++20 の std::span に似た、任意のメモリの連続領域を表します。"
type: docs
weight: 1262
url: /ja/system/span/
---
## Span クラス

任意のメモリの連続領域を表し、C++20 の std::span に似ています。

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | span 内の要素の型。このクラスは、オブジェクトの連続シーケンスを安全に扱う方法を提供します。配列、スタック配列、または生ポインタをラップして境界チェックを維持するために使用できます。[Span](./) は指すメモリを所有しません - 既存のメモリへのビューにすぎません。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Clear](./clear/)() const | span の内容をすべて既定値に設定してクリアします。 |
| void [Fill](./fill/)(const T\&) const | 指定された値で span を埋めます。 |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | 配列を [Span](./) に変換します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)