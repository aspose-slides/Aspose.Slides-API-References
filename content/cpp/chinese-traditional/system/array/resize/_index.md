---
title: Resize()
second_title: Aspose.Slides for C++ API 參考
description: 將指定陣列的大小變更為指定的值，或以指定的大小建立新陣列。
type: docs
weight: 768
url: /zh-hant/system/array/resize/
---
## Array::Resize(ArrayPtr\<Type\>\&, int) 方法

將指定陣列的大小變更為指定的值，或以指定的大小建立新陣列。

```cpp
template<typename Type> static void System::Array<T>::Resize(ArrayPtr<Type> &arr, int new_size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | [Array](../) 以調整大小。如果 **arr** 為空指標，將建立新的陣列 |
| new_size | int | 陣列的新大小；如果 **arr** 為空，則為新陣列的大小 |

## 另請參閱

* 型別別名 [ArrayPtr](../../arrayptr/)
* 方法 [Type](../../object/type/)
* 類別 [Array](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)