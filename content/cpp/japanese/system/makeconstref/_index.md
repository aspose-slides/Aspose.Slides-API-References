---
title: MakeConstRef
second_title: Aspose.Slides for C++ API リファレンス
description: String または SmartPtr<> 型の場合に、ジェネリック型を \"const reference\" にするトレイトです。
type: docs
weight: 1769
url: /ja/system/makeconstref/
---
## MakeConstRef struct

ジェネリック型が [String](../string/) または SmartPtr<> 型の場合に \"const reference\" を作成するトレイトです。

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)