---
title: operator=()
second_title: Aspose.Slides for C++ API リファレンス
description: 弱ポインタに値を代入します。SmartPtr_ の特定の代入演算子を呼び出します。
type: docs
weight: 14
url: /ja/system/weakptr/operator_equal/
---
## WeakPtr::operator=(Q\&&) メソッド

Assigns value to weak pointer. Calls into specific assignment operator of SmartPtr_.

```cpp
template<typename Q> WeakPtr & System::WeakPtr<T>::operator=(Q &&value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | [System::SmartPtr](../../smartptr/) の代入演算子がサポートする引数型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | Q\&& | コピー元の値へのポインタ。 |

## 参照

* クラス [WeakPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)