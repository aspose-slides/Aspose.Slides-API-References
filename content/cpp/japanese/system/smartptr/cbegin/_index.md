---
title: cbegin()
second_title: Aspose.Slides for C++ API リファレンス
description: 基になるコレクションの cbegin() メソッドへのアクセッサです。SmartPtr_ が cbegin() メソッドを持つ特殊化型である場合にのみコンパイルされます。
type: docs
weight: 404
url: /ja/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const メソッド


[cbegin()](./) メソッドへのアクセッサで、基になるコレクションの要素にアクセスします。 SmartPtr_ が [cbegin()](./) メソッドを持つ特殊化型の場合のみコンパイルされます。

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### 戻り値

コレクションの先頭へのイテレータ

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)