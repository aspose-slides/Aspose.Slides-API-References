---
title: IEnumerableToStr()
second_title: Aspose.Slides for C++ API 参考
description: 通过连接元素的字符串表示，将集合转换为字符串。
type: docs
weight: 40
url: /zh/system/collectionasserthelper/ienumerabletostr/
---
## CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&) 方法

通过连接元素的字符串表示，将集合转换为字符串。

```cpp
template<typename T> static System::String System::CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr<System::Collections::Generic::IEnumerable<T>> &ie)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ie | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 要检查的集合。 |

### 返回值

集合的连接值。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 结构体 [CollectionAssertHelper](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)