---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 参考
description: 在已排序的数组中执行二分查找。
type: docs
weight: 612
url: /zh/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) 方法


执行已排序数组的二分查找。

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | 要进行搜索的已排序数组 |
| item | const T\& | 要搜索的项 |

### 返回值

如果找到则返回搜索项的索引；如果未找到，则返回一个负整数，该负整数为大于搜索项的下一个元素索引的按位取反；如果不存在更大的元素，则为数组中元素数量的按位取反。

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) 方法


未实现。

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 类 [Array](../)
* 类 [IComparer](../../../system.collections.generic/icomparer/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)