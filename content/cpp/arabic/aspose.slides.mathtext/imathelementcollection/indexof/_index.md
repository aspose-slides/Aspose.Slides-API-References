---
title: IndexOf()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد الفهرس لعنصر رياضي محدد في المجموعة.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) method

يحدد الفهرس لعنصر رياضي محدد في المجموعة.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الذي سيتم تحديد موقعه في المجموعة. |

### قيمة الإرجاع

الفهرس للـ *item* إذا وجد في المجموعة؛ وإلا -1.
## ملاحظات

مثال:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathElementCollection](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)