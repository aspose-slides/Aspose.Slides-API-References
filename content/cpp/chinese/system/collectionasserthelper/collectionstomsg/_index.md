---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API 参考文档
description: 将两个集合序列化为消息表示。
type: docs
weight: 53
url: /zh/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) 方法

将两个集合序列化为消息表示。

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 预期的集合元素类型。 |
| T2 | 实际的集合元素类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | 在结果消息中插入在预期值之前的自定义字符串 |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 预期的集合。 |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 实际的集合。 |

### 返回值

关于集合内容的用户友好消息。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 结构体 [CollectionAssertHelper](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)