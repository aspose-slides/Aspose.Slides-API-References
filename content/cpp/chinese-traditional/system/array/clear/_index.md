---
title: Clear()
second_title: Aspose.Slides for C++ API 參考文件
description: 不支援，因為目前物件所代表的陣列是唯讀的。
type: docs
weight: 53
url: /zh-hant/system/array/clear/
---
## Array::Clear() 方法

Not supported because the array represented by the current object is read-only.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) 方法

Replaces **count** values starting at the **startIndex** index in the specified array with default values.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Type | 目標陣列中元素的類型 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目標陣列 |
| startIndex | int | [Index](../../index/) 表示開始取代項目的位置 |
| count | int | 要取代的項目數量 |

## 參見

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)