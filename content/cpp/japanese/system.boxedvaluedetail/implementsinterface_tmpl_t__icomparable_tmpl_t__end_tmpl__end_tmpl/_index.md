---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides C++ API リファレンス
description: ボックス化されたオブジェクトが IComparable インターフェイスを自ら実装すべきかどうかを確認するテンプレート述語です。
type: docs
weight: 53
url: /ja/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


ボックス化されたオブジェクトが [IComparable](../../system/icomparable/) インターフェイスを自ら実装すべきかどうかを確認するテンプレート述語です。

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## 参照

* 名前空間 [System::BoxedValueDetail](../)
* ライブラリ [Aspose.Slides](../../)