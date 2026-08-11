---
title: operator==()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عامل المساواة لـ ResultValueTask.
type: docs
weight: 131
url: /ar/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const method


عامل المساواة لـ [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | [ResultValueTask](../) الآخر للمقارنة مع هذه المثيلة. |

### قيمة الإرجاع

bool صحيح إذا كانت كلتا المهمتين لهما نفس قيمة النتيجة أو تشير إلى نفس المهمة الأساسية؛ وإلا، خطأ.
## ملاحظات



إذا كانت أي من المثيلات تحتوي على قيمة نتيجة مباشرة، يتم مقارنة القيم مباشرة. وإلا، يتم مقارنة مؤشرات المهمة الأساسية. 
## انظر أيضًا

* الفئة [ResultValueTask](../)
* النطاق [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)