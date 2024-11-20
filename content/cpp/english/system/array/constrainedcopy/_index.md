---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API Reference
description: Copies a range of elements from an System.Array starting at the specified source.
type: docs
weight: 690
url: /system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method


Copies a range of elements from an [System.Array](../) starting at the specified source.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | Index in the source array designating the beginning of the range of items to copy |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | Index in destination array to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |
## Remarks


TEMPORARY RAW IMPLEMENTATION WITHOUT ANY UNDONES! 
## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)