---
title: get_pointer()
second_title: Aspose.Slides for C++ API リファレンス
description: スマートポインタが参照するオブジェクトを取得します。
type: docs
weight: 2952
url: /ja/system/get_pointer/
---
## System::get_pointer(System::SmartPtr\<T\> const\&) function


スマートポインタが参照するオブジェクトを取得します。

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | ポインタ先の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [System::SmartPtr](../smartptr/)\<T\> const\& | 元のスマートポインタ。 |

### 戻り値

渡されたスマートポインタが参照するオブジェクトへの生ポインタ。

## 参照

* クラス [SmartPtr](../smartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)