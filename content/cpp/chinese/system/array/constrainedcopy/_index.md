---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API 参考
description: 从指定源的 System.Array 复制一段元素。
type: docs
weight: 716
url: /zh/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) method

从指定源的 [System.Array](../) 复制一段元素。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| SrcType | 源数组中元素的类型 |
| DstType | 目标数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 源数组 |
| srcIndex | **int64_t** | 源数组中指定复制范围起始位置的索引 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 目标数组 |
| dstIndex | **int64_t** | 目标数组中开始插入复制项的索引 |
| count | **int64_t** | 要复制的元素数量 |

## 备注

临时原始实现，尚未完成任何撤销！

## 另见

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)