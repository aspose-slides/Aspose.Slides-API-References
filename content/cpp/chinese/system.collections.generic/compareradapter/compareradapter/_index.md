---
title: ComparerAdapter()
second_title: Aspose.Slides for C++ API 参考
description: 在没有任何比较器可用的情况下构造适配器。
type: docs
weight: 1
url: /zh/system.collections.generic/compareradapter/compareradapter/
---
## ComparerAdapter::ComparerAdapter() 构造函数

在没有任何比较器可用的情况下构造适配器。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter()
```

## ComparerAdapter::ComparerAdapter(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 构造函数

构造适配器。

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的比较器对象。 |

## 另请参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IComparer](../../icomparer/)
* 结构体 [ComparerAdapter](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)