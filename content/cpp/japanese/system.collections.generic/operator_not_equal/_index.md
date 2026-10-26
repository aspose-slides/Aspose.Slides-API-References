---
title: operator!=()
second_title: Aspose.Slides for C++ API リファレンス
description: 逆の 'equals' セマンティクスを使用して 2 つのキーと値のペアを比較します。
type: docs
weight: 703
url: /ja/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 関数

逆の「equals」セマンティクスを使用して 2 つのキーと値のペアを比較します。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### テンプレートパラメータ

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

キーと値の両方が一致しない場合は True、そうでない場合は false。

## 関連項目

* クラス [KeyValuePair](../keyvaluepair/)
* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)