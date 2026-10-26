---
title: static_pointer_cast()
second_title: C++ 用 Aspose.Slides API リファレンス
description: static_cast を使用してスマート ポインタをキャストします。
type: docs
weight: 2913
url: /ja/system/static_pointer_cast/
---
## System::static_pointer_cast(SmartPtr\<X\> const\&) function


static_cast を使用してスマート ポインタをキャストします。

```cpp
template<class Y,class X> SmartPtr<Y> System::static_pointer_cast(SmartPtr<X> const &x)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | ソース ポインタが指す型。 |
| Y | ターゲット ポインタが指す型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | ソース ポインタ。 |

### 戻り値

キャスト後のポインタ。

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)