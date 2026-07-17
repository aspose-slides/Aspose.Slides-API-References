---
title: GetChildRows()
second_title: Aspose.Slides for C++ API 参考
description: 获取通过指定关系被视为子行的行。
type: docs
weight: 27
url: /zh/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) 方法

获取通过指定关系被视为子行的行。

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | 用于指定父行-子行关系的对象。 |

### 返回值

返回检索到的子行[Array](../../../system/array/)。

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [DataRow](../)
* 类 [DataRelation](../../datarelation/)
* 命名空间 [System::Data](../../)
* 库 [Aspose.Slides](../../../)