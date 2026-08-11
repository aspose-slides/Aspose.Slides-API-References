---
title: MakeRelativeUri()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدّد الفرق بين عناوين URI التي يمثلها الكائن الحالي والكائن Uri المحدد.
type: docs
weight: 352
url: /ar/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) طريقة

يحدد الفرق بين عناوين URI التي يمثلها الكائن الحالي والكائن [Uri](../) المحدد.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | المقارنة |

### قيمة الإرجاع

إذا كان اسم المضيف والبروتوكول لعناوين URI التي يمثلها الكائن الحالي و**toUri** متطابقين، فإن هذه الطريقة تُرجع [Uri](../) نسبيًا، والذي عند إلحاقه بمثيل URI الحالي ينتج **toUri**. إذا كان اسم المضيف أو البروتوكول مختلفًا، فإن هذه الطريقة تُرجع كائن [Uri](../) يمثل المعامل **uri**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Uri](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)