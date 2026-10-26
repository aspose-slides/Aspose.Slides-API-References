---
title: BitConverter
second_title: Aspose.Slides برای مرجع API C++
description: شامل متدهایی است که تبدیل توالی بایت‌ها به یک نوع مقداری و برعکس را انجام می‌دهد. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 66
url: /fa/system/bitconverter/
---
## BitConverter کلاس

Contains methods that perform conversions of sequence of bytes to a value type and vice-versa. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class BitConverter
```

## متدها

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | نشان‌دهندهٔ ترتیب بایت معماری فعلی است. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | یک مقدار عدد صحیح 64-بیتی را برمی‌گرداند که نمایش باینری آن برابر با نمایش باینری مقدار نقطه‌شناور دو دقت مشخص شده است. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | مقدار بولی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | مقدار char_t مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | مقدار عدد صحیح 16-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | مقدار عدد صحیح 32-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | مقدار عدد صحیح 64-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | مقدار عدد صحیح بدون علامت 16-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | مقدار عدد صحیح بدون علامت 32-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | مقدار عدد صحیح بدون علامت 64-بیتی مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | مقدار عدد شناور تک دقت مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | مقدار عدد شناور دو دقت مشخص‌شده را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | یک مقدار عدد شناور دو دقت را برمی‌گرداند که مقدار آن برابر با مقدار داده‌شده است. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | یک بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شود به مقدار بولی تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | یک بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شود به مقدار بولی تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار char_t تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار char_t تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد شناور دو دقت تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد شناور دو دقت تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 16-بیتی تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 16-بیتی تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 32-بیتی تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 32-بیتی تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 64-بیتی تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح 64-بیتی تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد شناور تک دقت تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد شناور تک دقت تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | تمام مقادیر آرایهٔ بایت مشخص‌شده را به رشتهٔ هگزادسیمالشان تبدیل می‌کند. حالت حروف در نمایش هگزادسیمال و جداکننده‌ای که بین هر جفت بایت قرار می‌گیرد از طریق آرگومان‌های مربوطه تعیین می‌شود. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | مقادیر آرایهٔ بایت مشخص‌شده را از اندیس مشخص‌شده به رشتهٔ هگزادسیمالشان تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | بازه‌ای از مقادیر آرایهٔ بایت مشخص‌شده را به رشتهٔ هگزادسیمالشان تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 16-بیتی تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | دو بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 16-بیتی تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 32-بیتی تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | چهار بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 32-بیتی تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 64-بیتی تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | هشت بایت را از آرایهٔ مشخص‌شده که از اندیس مشخص شروع می‌شوند به مقدار عدد صحیح بدون علامت 64-بیتی تبدیل می‌کند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | نشان‌دهندهٔ ترتیب بایت معماری فعلی است. true اگر معماری لِتل-اندین باشد، false در غیر این صورت. |

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
  // ایجاد مقادیر برای چاپ.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // مقدار و بایت‌های آن را چاپ کنید.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)