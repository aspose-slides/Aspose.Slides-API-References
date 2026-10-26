---
title: end()
second_title: Aspose.Slides for C++ API リファレンス
description: 基になるコレクションの end() メソッドへのアクセサです。SmartPtr_ が end() メソッドを持つ特殊化型の場合にのみコンパイルされます。
type: docs
weight: 391
url: /ja/system/smartptr/end/
---
## SmartPtr::end() メソッド

基になるコレクションの[end()](./)メソッドへのアクセサです。SmartPtr_ が[end()](./)メソッドを持つ特殊化型の場合のみコンパイルされます。

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### 戻り値

コレクションの終端イテレータ

## SmartPtr::end() const メソッド

基になるコレクションの[end()](./)メソッドへのアクセサです。SmartPtr_ が[end()](./)メソッドを持つ特殊化型の場合のみコンパイルされます。

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### 戻り値

コレクションの終端イテレータ

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)