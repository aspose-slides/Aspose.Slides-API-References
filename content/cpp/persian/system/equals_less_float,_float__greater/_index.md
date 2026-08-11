---
title: Equals< float, float >()
second_title: مرجع API Aspose.Slides برای C++
description: "تخصیص ویژه برای مقادیر عدد شناور تک‌دقت. اگرچه دو NaN عدد شناور توسط IEC 60559:1989 به‌صورت دائم به‌عنوان نامساوی تعریف شده‌اند، قرارداد برای System.Object.Equals، می‌طلبد که بازنویسی‌ها الزامات یک عملگر هم‌ارزی را برآورده کنند. بنابراین، System.Double.Equals و System.Single.Equals هنگام مقایسه دو NaN مقدار True را برمی‌گردانند، در حالی که عملگر برابری در آن حالت مقدار False را بازمی‌گرداند، همان‌طور که استاندارد می‌طلبد."
type: docs
weight: 2705
url: /fa/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) function

تخصیص ویژه برای مقادیر عدد شناور تک‌دقت. اگرچه دو NaN عدد شناور توسط IEC 60559:1989 به‌عنوان نامساوی تعریف شده‌اند، قرارداد برای [System.Object.Equals](../object/equals/) می‌طلبد که بازنویسی‌ها الزامات یک عملگر همپایداری را برآورده کنند. بنابراین، System.Double.Equals و System.Single.Equals در مقایسه دو NaN مقدار True را بازمی‌گردانند، در حالی که عملگر برابری در این حالت مقدار False را بازمی‌گرداند، همان‌طور که استاندارد می‌طلبد.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| a | const **float**\& | اولین مقایسه‌شونده |
| b | const **float**\& | دومین مقایسه‌شونده |

### مقدار بازگشت

True اگر هر دو مقدار NaN باشند یا برابر باشند، در غیر این صورت - false

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)