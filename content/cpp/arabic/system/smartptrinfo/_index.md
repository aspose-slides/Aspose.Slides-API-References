---
title: SmartPtrInfo
second_title: دليل API لـ Aspose.Slides للغة C++
description: فئة خدمة لاختبار وتعديل محتويات SmartPtr دون معرفة النوع النهائي. تُستخدم لجمع القمامة واكتشاف مراجع الحلقات، إلخ. فكر فيها كـ 'pointer to pointer'. لا يمكننا استخدام النوع الأساسي لـ SmartPtr لأنه غير موجود؛ بدلاً من ذلك، نستخدم فئة 'info' هذه.
type: docs
weight: 1249
url: /ar/system/smartptrinfo/
---
## SmartPtrInfo فئة

فئة خدمة لاختبار وتعديل محتويات [SmartPtr](../smartptr/) دون معرفة النوع النهائي. تُستخدم لجمع القمامة واكتشاف مراجع الحلقات، إلخ. فكر فيها كـ 'مؤشر إلى مؤشر'. لا يمكننا استخدام النوع الأساسي لـ [SmartPtr](../smartptr/) لأنه غير موجود؛ بدلاً من ذلك، نستخدم فئة 'info' هذه.

```cpp
class SmartPtrInfo
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | يحصل على الكائن الخام الذي يشير إليه المؤشر المرجعي. |
| [Object](../object/) * [getObject](./getobject/)() const | يحصل على الكائن الذي يشير إليه المؤشر المرجعي. |
| [Object](../object/) * [getOwned](./getowned/)() const | يحصل على مؤشر الكائن المملوك. |
|  [operator bool](./operator_bool/)() const | يتحقق مما إذا كان كائن info يشير إلى مؤشر غير فارغ. |
| **bool** [operator!](./operator_not/)() const | يتحقق مما إذا كان كائن info لا يشير إلى مؤشر غير فارغ. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | يسمح باستدعاء طرق [Object](../object/) التي يشير إليها المؤشر المرجعي. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | يقارن قيم المؤشرات المرجعية بين كائنين من نوع info باستخدام مقارنة أقل. |
|  [SmartPtrInfo](./smartptrinfo/)() | ينشئ كائن [SmartPtrInfo](./) فارغ. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | ينشئ كائن [SmartPtrInfo](./) مع معلومات حول مؤشر ذكي محدد. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)