---
title: BitConverter
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتضمن طرقًا تقوم بتحويل تسلسل من البايتات إلى نوع قيمة والعكس. هذا نوع ثابت لا يحتوي على خدمات كائنات. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.
type: docs
weight: 66
url: /ar/system/bitconverter/
---
## BitConverter فئة

يتضمن طرقًا تقوم بتحويل تسلسل من البايتات إلى نوع قيمة والعكس. هذا نوع ثابت لا يحتوي على خدمات كائنات. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.

```cpp
class BitConverter
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | تشير إلى ترتيب البايتات (endianness) للمعمارية الحالية. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | إرجاع قيمة عدد صحيح 64-بت تمثله الثنائي يساوي التمثيل الثنائي للقيمة ذات الفاصلة العائمة ذات الدقة المزدوجة المحددة. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | تحويل القيمة البوليانية المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | تحويل القيمة char_t المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | تحويل القيمة الصحيحة 16-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | تحويل القيمة الصحيحة 32-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | تحويل القيمة الصحيحة 64-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | تحويل القيمة الصحيحة غير الموقعة 16-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | تحويل القيمة الصحيحة غير الموقعة 32-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | تحويل القيمة الصحيحة غير الموقعة 64-بت المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | تحويل القيمة ذات الفاصلة العائمة ذات الدقة المفردة المحددة إلى مصفوفة من البايتات. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | تحويل القيمة ذات الفاصلة العائمة ذات الدقة المزدوجة المحددة إلى مصفوفة من البايتات. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | إرجاع قيمة ذات الفاصلة العائمة ذات الدقة المزدوجة تكون قيمتها مساوية للقيمة. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل بايت واحد من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة بوليانية. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل بايت واحد من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة بوليانية. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة ذات الفاصلة العائمة ذات الدقة المزدوجة. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة ذات الفاصلة العائمة ذات الدقة المزدوجة. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 16-بت. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 16-بت. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 32-بت. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 32-بت. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 64-بت. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة 64-بت. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة ذات الفاصلة العائمة ذات الدقة المفردة. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة ذات الفاصلة العائمة ذات الدقة المفردة. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | تحويل جميع قيم مصفوفة البايتات المحددة إلى تمثيلها كسلسلة سداسية عشرية. حالة الأحرف المستخدمة في الترميز السداسي عشر وفاصل يُدرج بين كل زوج من البايتات المتجاورة يتم تحديدهما من خلال المعاملات المقابلة. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل قيم مصفوفة البايتات المحددة إلى تمثيلها كسلسلة سداسية عشرية بدءًا من الفهرس المحدد. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | تحويل نطاق من قيم مصفوفة البايتات المحددة إلى تمثيلها كسلسلة سداسية عشرية. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 16-بت. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 16-بت. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 32-بت. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 32-بت. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 64-بت. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة صحيحة غير موقعة 64-بت. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | تشير إلى ترتيب البايتات (endianness) للمعمارية الحالية. true إذا كانت المعمارية ذات ترتيب بايتات little endian، false غير ذلك. |

## ملاحظات

```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // إنشاء القيم للطباعة.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // طباعة القيمة و بايتاتها.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
يعرض مثال الشيفرة هذا النتيجة التالية:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## انظر أيضًا

* مساحة الأسماء [System](../)
* مكتبة [Aspose.Slides](../../)