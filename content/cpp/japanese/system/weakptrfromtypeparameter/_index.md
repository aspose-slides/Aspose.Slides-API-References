---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API リファレンス
description: 引数の型がポインタ型である場合に、弱ポインタへ変換するトレイト構造体です。
type: docs
weight: 2016
url: /ja/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter 構造体


引数の型がポインタ型である場合に、弱ポインタへ変換するトレイト構造体です。

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)