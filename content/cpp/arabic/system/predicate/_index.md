---
title: Predicate
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مؤشرًا إلى شرط - كيانًا قابلاً للاستدعاء يقبل معاملًا واحدًا ويعيد قيمة منطقية.
type: docs
weight: 4187
url: /ar/system/predicate/
---
## تعريف نوع الشرط


يمثل مؤشرًا إلى شرط - كيانًا قابلاً للاستدعاء يقبل معاملًا واحدًا ويعيد قيمة منطقية.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## ملاحظات



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // ملء المصفوفة.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // إنشاء الشرط الذي يعيد عنصرًا في المصفوفة أكبر من 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // البحث عن العنصر الأول في المصفوفة باستخدام الشرط المنشأ وطباعة النتيجة.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
5
*/
```

## انظر أيضًا

* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)