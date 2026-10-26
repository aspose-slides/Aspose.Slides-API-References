---
title: ReadOnlySpan
second_title: Aspose.Slides の C++ API リファレンス
description: Span クラス内で使用するために転送されます。
type: docs
weight: 1210
url: /ja/system/readonlyspan/
---
## ReadOnlySpan クラス

Forward to use within [Span](../span/) クラス.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | スパン内の要素の型です。このクラスは、読み取り専用の方法でオブジェクトの連続シーケンスを安全に扱う手段を提供します。配列、スタック配列、または生ポインタをラップし、境界チェックを維持できます。[ReadOnlySpan](./) は指すメモリを所有しません - 既存のメモリへのビューです。 |
## メソッド

| Method | Description |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | 通常のスパンから読み取り専用スパンを構築します。 |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | 配列を[ReadOnlySpan](./)に変換します。 |
## 備考

任意のメモリの読み取り専用連続領域を表します。

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)