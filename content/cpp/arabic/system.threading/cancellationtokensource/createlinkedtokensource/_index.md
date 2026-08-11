---
title: CreateLinkedTokenSource()
second_title: مرجع API Aspose.Slides لـ C++
description: إنشاء مصدر رمز مرتبط يُلغى عندما يُلغى أي من الرموز المقدَّمة.
type: docs
weight: 66
url: /ar/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method


ينشئ مصدر رمز مرتبط يُلغى عندما يُلغى أي من الرموز المقدَّمة.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | رمز الإلغاء الأول للمراقبة. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | رمز الإلغاء الثاني للمراقبة. |

### قيمة الإرجاع

مصدر رمز جديد سيُلغى عندما يُلغي أي من رمزي الإدخال.

## ملاحظات



المصدر المعاد سيُلغى فوراً إذا كان أي من رمزي الإدخال مُلغى بالفعل. 

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [CancellationTokenSource](../)
* الفئة [CancellationToken](../../cancellationtoken/)
* النطاق [System::Threading](../../)
* Library [Aspose.Slides](../../../)