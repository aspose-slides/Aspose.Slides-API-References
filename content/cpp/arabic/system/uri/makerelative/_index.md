---
title: MakeRelative()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد الفرق بين مثالي Uri.
type: docs
weight: 365
url: /ar/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) طريقة

يحدد الفرق بين مثيلين من [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | معرف URI للمقارنة مع معرف URI الحالي |

### قيمة الإرجاع

إذا كان اسم المضيف والمخطط للـ URIs التي يمثلها الكائن الحالي و**toUri** متطابقين، فإن هذه الطريقة تُرجع [String](../../string/) يمثل مسارًا نسبياً [Uri](../)، وعند إلحاقه بنسخة الـ URI الحالية ينتج **toUri**. إذا كان اسم المضيف أو المخطط مختلفًا، فإن هذه الطريقة تُرجع [String](../../string/) يمثل المعامل **uri**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Uri](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)