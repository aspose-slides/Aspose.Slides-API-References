---
title: operator==()
second_title: Aspose.Slides for C++ APIリファレンス
description: 'equals' セマンティクスを使用して 2 つのキーと値のペアを比較します。キーと値の両方に対して operator == または EqualsTo メソッドが定義されている方を使用します。
type: docs
weight: 690
url: /ja/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 関数

2つのキーと値のペアを 'equals' セマンティクスで比較します。キーと値の両方に対して operator == または EqualsTo メソッドが定義されている方を使用します。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TKey | キーの型。 |
| TValue | 値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 左側オペランド。 |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 右側オペランド。 |

### 戻り値

キーと値の両方が一致すれば true、そうでなければ false。

## 参照

* クラス [KeyValuePair](../keyvaluepair/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)