---
title: idx_get()
second_title: Aspose.Slides C++ API 参考
description: 获取具名项。
type: docs
weight: 1
url: /zh/system.data.common/dbdatareader/idx_get/
---
## DbDataReader::idx_get(String) 方法


获取具名项。

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(String name)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 项名称。 |

### 返回值

装箱的项值。

## DbDataReader::idx_get(int) 方法


通过索引获取项。

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(int ordinal)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ordinal | int | 项索引。 |

### 返回值

装箱的项值。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [DbDataReader](../)
* 命名空间 [System::Data::Common](../../)
* 库 [Aspose.Slides](../../../)