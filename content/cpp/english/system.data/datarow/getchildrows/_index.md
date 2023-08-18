---
title: GetChildRows()
second_title: Aspose.Slides for C++ API Reference
description: Gets rows which are considered child through specified relation.
type: docs
weight: 27
url: /system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) method


Gets rows which are considered child through specified relation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Relation object to specify parent row - child row relation. |

### Return Value

[Array](../../../system/array/) of child rows retreived.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DataRow](../)
* Class [DataRelation](../../datarelation/)
* Namespace [System::Data](../../)
* Library [Aspose.Slides](../../../)