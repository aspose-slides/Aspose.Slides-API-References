---
title: ValueType
second_title: Aspose.Slides for C++ API リファレンス
description: "指し示された配列の格納型です。T が System::Array の特殊化である場合のみ意味があります。"
type: docs
weight: 508
url: /ja/system/smartptr/valuetype/
---
## ValueType typedef


指し示された配列の格納型です。T が [System::Array](../../array/) の特殊化である場合のみ意味があります。

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)