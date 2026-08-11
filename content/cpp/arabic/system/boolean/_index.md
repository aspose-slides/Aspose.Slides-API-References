---
title: Boolean
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: الفئة التي تحتفظ بالأعضاء الثابتة من نوع System.Boolean في .Net.
type: docs
weight: 79
url: /ar/system/boolean/
---
## فئة Boolean

الفئة التي تحتفظ بالأعضاء الثابتة من نوع [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | تحول السلسلة المحددة إلى قيمة من نوع bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | تحول السلسلة المحددة إلى قيمة من نوع bool. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) تمثيل القيمة المنطقية 'false'. |
| static [TrueString](./truestring/) | [String](../string/) تمثيل القيمة المنطقية 'true'. |

## ملاحظات

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // إنشاء المتغير المنطقي.
  bool isWeekend = false;

  // تحليل السلسلة المدخلة وطباعة النتيجة.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
مثال الشيفرة هذا ينتج المخرجات التالية:
Is weekend: Yes
*/
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)