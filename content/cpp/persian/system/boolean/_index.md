---
title: Boolean
second_title: Aspose.Slides برای C++ مرجع API
description: کلاسی که اعضای ایستا از نوع System.Boolean .Net را نگه می‌دارد.
type: docs
weight: 79
url: /fa/system/boolean/
---
## کلاس Boolean

کلاسی که اعضای ایستا از نوع [System.Boolean](./) .[Net](../../system.net/) را نگه می‌دارد.

```cpp
class Boolean
```

## متدها

| متد | توضیح |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده را به مقدار از نوع bool تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | رشتهٔ مشخص‌شده را به مقدار از نوع bool تبدیل می‌کند. |
## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [FalseString](./falsestring/) | نمایش [String](../string/) از مقدار بولی 'false' |
| static [TrueString](./truestring/) | نمایش [String](../string/) از مقدار بولی 'true' |
## یادداشت‌ها



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // ایجاد متغیر بولی.
  bool isWeekend = false;

  // رشتهٔ ورودی را تجزیه می‌کند و نتیجه را چاپ می‌کند.
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
این مثال کد خروجی زیر را تولید می‌کند:
Is weekend: Yes
*/
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)