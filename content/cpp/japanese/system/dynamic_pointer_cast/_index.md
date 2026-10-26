---
title: dynamic_pointer_cast()
second_title: Aspose.Slides for C++ API リファレンス
description: dynamic_cast を使用してスマートポインタをキャストします。
type: docs
weight: 2926
url: /ja/system/dynamic_pointer_cast/
---
## System::dynamic_pointer_cast(SmartPtr\<X\> const\&) 関数


dynamic_cast を使用してスマート ポインタをキャストします。

```cpp
template<class Y,class X> SmartPtr<Y> System::dynamic_pointer_cast(SmartPtr<X> const &x)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | ソース ポインタの指し示す型。 |
| Y | 対象ポインタの指し示す型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | ソース ポインタ。 |

### 返り値

キャスト後のポインタ。

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)