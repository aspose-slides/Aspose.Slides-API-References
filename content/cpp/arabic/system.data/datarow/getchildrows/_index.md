---
title: GetChildRows()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الصفوف التي تُعتبر فرعية عبر العلاقة المحددة.
type: docs
weight: 27
url: /ar/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) طريقة

يحصل على الصفوف التي تُعتبر فرعية عبر العلاقة المحددة.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | كائن العلاقة لتحديد علاقة الصف الأصلي - الصف الفرعي. |

### قيمة الإرجاع

[Array](../../../system/array/) من الصفوف الفرعية المسترجعة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [DataRow](../)
* فئة [DataRelation](../../datarelation/)
* نطاق [System::Data](../../)
* Library [Aspose.Slides](../../../)