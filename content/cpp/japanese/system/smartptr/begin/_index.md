---
title: begin()
second_title: Aspose.Slides for C++ API リファレンス
description: 基礎コレクションの begin() メソッドへのアクセサーです。SmartPtr_ が begin() メソッドを持つ特殊化型である場合にのみコンパイルされます。
type: docs
weight: 378
url: /ja/system/smartptr/begin/
---
## SmartPtr::begin() メソッド

Accessor for [begin()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### 戻り値

iterator to the begin of collection

## SmartPtr::begin() const メソッド

Accessor for [begin()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### 戻り値

iterator to the begin of collection

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)