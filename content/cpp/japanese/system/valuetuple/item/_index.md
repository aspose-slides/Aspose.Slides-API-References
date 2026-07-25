---
title: Item()
second_title: Aspose.Slides for C++ API リファレンス
description: ValueTuple オブジェクトのコンポーネントの値への参照を取得します。
type: docs
weight: 14
url: /ja/system/valuetuple/item/
---
## ValueTuple::Item() メソッド

[ValueTuple](../) オブジェクトのコンポーネントの値への参照を取得します。

```cpp
template<std::size_t> std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item()
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Index | クラスが返すべき項目の番号です。 |

## ValueTuple::Item() const メソッド

[ValueTuple](../) オブジェクトのコンポーネントの値を取得します。

```cpp
template<std::size_t> const std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item() const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Index | クラスが返すべき項目の番号です。 |

## 参照

* クラス [Index](../../index/)
* クラス [ValueTuple](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)