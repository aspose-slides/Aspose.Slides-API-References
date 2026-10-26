---
title: const_pointer_cast()
second_title: Aspose.Slides for C++ API リファレンス
description: const_cast を使用してスマートポインタをキャストします。
type: docs
weight: 2939
url: /ja/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) 関数

const_cast を使用してスマートポインタをキャストします。

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | ソース ポインタの指す型。 |
| Y | ターゲット ポインタの指す型。 |

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