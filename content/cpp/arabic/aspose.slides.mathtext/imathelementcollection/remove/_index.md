---
title: Remove()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل الظهور الأول لكائن محدد من المجموعة.
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) طريقة

يزيل الظهور الأول لكائن محدد من المجموعة.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الكائن المراد إزالته من المجموعة. |

### قيمة الإرجاع

true إذا تم إزالة *item* بنجاح من المجموعة؛ وإلا false. هذه الطريقة تُعيد false أيضًا إذا لم يتم العثور على *item* في المجموعة الأصلية.

## ملاحظات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)