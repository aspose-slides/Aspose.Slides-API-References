---
title: ConstrainedCopy()
second_title: Aspose.Slides C++ API 參考
description: 從 System.Array 複製一段元素，起始於指定的來源。
type: docs
weight: 716
url: /zh-hant/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 方法

從 [System.Array](../) 複製一段元素，起始於指定的來源。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| SrcType | 來源陣列中元素的類型 |
| DstType | 目標陣列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 來源陣列 |
| srcIndex | **int64_t** | [Index](../../index/) 在來源陣列中指定要複製之項目範圍的起始位置 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目標陣列 |
| dstIndex | **int64_t** | [Index](../../index/) 在目標陣列中插入已複製項目的起始位置 |
| count | **int64_t** | 要複製的元素數量 |
## 備註

臨時原始實作，未完成任何功能！

## 另請參閱

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [Array](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)