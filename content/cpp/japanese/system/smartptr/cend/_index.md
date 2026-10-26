---
title: cend()
second_title: Aspose.Slides for C++ API リファレンス
description: 基底コレクションの cend() メソッドへのアクセッサです。SmartPtr_ が cend() メソッドを持つ特殊化タイプの場合にのみコンパイルされます。
type: docs
weight: 417
url: /ja/system/smartptr/cend/
---
## SmartPtr::cend() const メソッド


Accessor for [cend()](./) メソッド of an underling collection. Only compiles if SmartPtr_ is specialization type with [cend()](./) メソッド.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```


### 戻り値

iterator to the end of collection

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)