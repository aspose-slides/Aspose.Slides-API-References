---
title: Resize()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された配列のサイズを指定された値に変更するか、指定されたサイズの新しい配列を作成します。
type: docs
weight: 768
url: /ja/system/array/resize/
---
## Array::Resize(ArrayPtr\<Type\>\&, int) メソッド

指定された配列のサイズを指定された値に変更するか、指定されたサイズの新しい配列を作成します。

```cpp
template<typename Type> static void System::Array<T>::Resize(ArrayPtr<Type> &arr, int new_size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | [Array](../) をサイズ変更の対象。**arr** がヌルポインタの場合、新しい配列が作成されます |
| new_size | int | 配列の新しいサイズ、または **arr** がヌルの場合の新しい配列のサイズ |

## 関連項目

* 型定義 [ArrayPtr](../../arrayptr/)
* メソッド [Type](../../object/type/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)