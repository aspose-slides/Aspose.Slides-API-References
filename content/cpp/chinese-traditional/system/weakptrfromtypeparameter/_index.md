---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API 參考
description: 特徵結構，用於將參數類型轉換為弱指標，如果它是指標類型。
type: docs
weight: 2016
url: /zh-hant/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter 結構


特徵結構，用於將參數類型轉換為弱指標，如果它是指標類型。

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)