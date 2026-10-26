---
title: operator!=()
second_title: Aspose.Slides for C++ API リファレンス
description: 参照されたオブジェクトが null でないかどうかを確認します。
type: docs
weight: 66
url: /ja/system/weakreference_tmpl_t__end_tmpl/operator_not_equal/
---
## WeakReference< T >::operator!=(std::nullptr_t) const メソッド

参照されたオブジェクトが null でないかどうかを確認します。

```cpp
bool System::WeakReference<T>::operator!=(std::nullptr_t) const
```

### 戻り値

参照されたオブジェクトが null でない場合は true、そうでない場合は false を返します。

## WeakReference< T >::operator!=(const WeakReference\<T\>\&) const メソッド

参照されたオブジェクトを別の WeakReference クラスのインスタンスと比較します。

```cpp
bool System::WeakReference<T>::operator!=(const WeakReference<T> &other) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) と比較する。 |

### 戻り値

比較されたオブジェクトが異なるオブジェクトを参照している場合は true、同じオブジェクトを参照している場合は false を返します。

## 参照

* メソッド [WeakReference](../weakreference/)
* クラス [WeakReference< T >](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)