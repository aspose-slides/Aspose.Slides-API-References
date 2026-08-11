---
title: JoinBlock()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بضم كتلة رياضية أخرى إلى هذه
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) طريقة

يقوم بضم كتلة رياضية أخرى إلى هذه

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | كتلة الانضمام |

### قيمة الإرجاع

هذه الكتلة الرياضية بعد الانضمام
## ملاحظات

مثال: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## راجع أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathBlock](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)