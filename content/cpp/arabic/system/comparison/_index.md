---
title: Comparison
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل مؤشرًا إلى الطريقة التي تقارن كائنين من نفس النوع. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr لإدارة كائنات من هذا النوع."
type: docs
weight: 183
url: /ar/system/comparison/
---
## فئة المقارنة

يمثل مؤشرًا إلى الطريقة التي تقارن كائنين من نفس النوع. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات من هذا النوع.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائنات التي تقارنها الطريقة |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | يقوم باستدعاء الكائن القابل للاستدعاء المشار إليه بواسطة الكائن الحالي. |

## ملاحظات

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// الفئة القالبية التي تمثل مصفوفة ديناميكية.
template <typename T>
class MyArray
{
  // تستخدم لتخزين بيانات المصفوفة.
  std::vector<T> m_data;

public:
  // يبني مثيًراً جديداً من المصفوفة الديناميكية الخاصة بنا.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // تستخدم لفرز بيانات المصفوفة. هذه الطريقة تقبل مثيًراً من
  // فئة القالب 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // يرجع عدد العناصر التي تخزنها المصفوفة الديناميكية لدينا.
  size_t get_Size()
  {
    return m_data.size();
  }

  // تستخدم للحصول على عنصر عند الفهرس المحدد.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // أنشئ مثيًراً من فئة MyArray بالعناصر المحددة.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // افرز بترتيب تصاعدي لعناصر المصفوفة الديناميكية.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // اطبع عناصر المصفوفة الديناميكية.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرج التالي:
a
b
c
d
e
*/
```

## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)