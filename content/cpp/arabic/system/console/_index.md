---
title: Console
second_title: مرجع API لـ Aspose.Slides للغة C++
description: توفر طرقًا لإخراج البيانات إلى تدفق الإخراج القياسي. هذه فئة ثابتة لا توفر خدمات مثيلات. لا ينبغي عليك أبدًا إنشاء مثيلات منها بأي وسيلة.
type: docs
weight: 196
url: /ar/system/console/
---
## فئة Console

توفر طرقًا لإخراج البيانات إلى تدفق الإخراج القياسي. هذه فئة ثابتة لا توفر خدمات مثيلات. لا يجب عليك أبدًا إنشاء مثيلات منها بأي وسيلة.

```cpp
class Console
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static void [Beep](./beep/)() | غير مطبق. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | إرجاع مؤشر مشترك يشير إلى الكائن الذي يمثل تدفق الأخطاء القياسي. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | إرجاع مؤشر مشترك يشير إلى الكائن الذي يمثل تدفق الإدخال القياسي. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | إرجاع مؤشر مشترك يشير إلى الكائن الذي يمثل تدفق الإخراج القياسي. |
| static void [Mute](./mute/)(**bool**) | يكتم أو يلغي كتم تدفق الإخراج القياسي. |
| static void [ReadKey](./readkey/)() | غير مطبق. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | يضبط عنوان نافذة وحدة التحكم. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | يعين الكائن المحدد إلى خاصية Error في الفئة. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | يضبط خاصية In إلى كائن TextReader المحدد. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | يعين الكائن المحدد إلى خاصية Out في الفئة. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يطبع تمثيل النص للكائن المحدد إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**bool**) | يطبع تمثيل النص لقيمة منطقية إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(char_t) | يطبع قيمة الحرف المحدد إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | يطبع تمثيل النص لمصفوفة الأحرف المحددة إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | يطبع تمثيل النص لقيمة [Decimal](../decimal/) إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**double**) | يطبع تمثيل النص لقيمة ذات دقة مزدوجة إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**float**) | يطبع تمثيل النص لقيمة ذات دقة أحادية إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**int32_t**) | يطبع تمثيل النص لقيمة عدد صحيح 32-بت إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**int64_t**) | يطبع تمثيل النص لقيمة عدد صحيح 64-بت إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [String](../string/)\&) | يطبع كائن السلسلة المحدد إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const char_t *) | يطبع سلسلة C المحددة إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | يطبع تمثيل النص لقيمة [TypeInfo](../typeinfo/) إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**uint32_t**) | يطبع تمثيل النص لقيمة عدد صحيح غير موقّع 32-بت إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(**uint64_t**) | يطبع تمثيل النص لقيمة عدد صحيح غير موقّع 64-بت إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | يطبع تمثيل النص للنطاق المحدد من مصفوفة الأحرف المحددة إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | يطبع تمثيل النص للمعطيات المحددة مُنسَّقة وفقًا للتنسيق المحدد إلى تدفق الإخراج القياسي. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | يطبع فاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يطبع تمثيل النص للكائن المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**bool**) | يطبع تمثيل النص لقيمة منطقية متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(char_t) | يطبع قيمة الحرف المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | يطبع تمثيل النص لمصفوفة الأحرف المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | يطبع تمثيل النص لقيمة [Decimal](../decimal/) متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**double**) | يطبع تمثيل النص لقيمة ذات دقة مزدوجة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**float**) | يطبع تمثيل النص لقيمة ذات دقة أحادية متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**int32_t**) | يطبع تمثيل النص لقيمة عدد صحيح 32-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**int64_t**) | يطبع تمثيل النص لقيمة عدد صحيح 64-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | يطبع كائن السلسلة المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const char_t *) | يطبع سلسلة C المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | يطبع تمثيل النص لقيمة [TypeInfo](../typeinfo/) متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**uint32_t**) | يطبع تمثيل النص لقيمة عدد صحيح غير موقّع 32-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(**uint64_t**) | يطبع تمثيل النص لقيمة عدد صحيح غير موقّع 64-بت متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | يطبع تمثيل النص للنطاق المحدد من مصفوفة الأحرف المحددة متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | يطبع تمثيل النص لكائن Exception المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | يطبع تمثيل النص للمعطيات المحددة المُنسَّقة وفقًا للتنسيق المحدد متبوعًا بفاصل السطر الحالي إلى تدفق الإخراج القياسي. |
| static void [WriteLine](./writeline/)(const char *) |  |

## ملاحظات

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // طباعة رسالة الترحيب.
  Console::WriteLine(u"Hello, world!");

  // إنشاء مثيل من الفئة 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // طباعة عناصر المصفوفة.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
مثال الشيفرة هذا ينتج المخرجات التالية:
Hello, world!
1 2 3 4 5
*/
```

## أنظر أيضًا

* مساحة الأسماء [System](../)
* مكتبة [Aspose.Slides](../../)