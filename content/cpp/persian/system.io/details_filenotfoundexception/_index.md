---
title: Details_FileNotFoundException
second_title: مرجع API Aspose.Slides برای C++
description: "استثنائی که زمانی که سعی می‌شود به فایلی که روی دیسک وجود ندارد دسترسی پیدا کند، پرتاب می‌شود. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به‌جای آن از کلاس FileNotFoundException استفاده کنید. هرگز نمونه‌های کلاس FileNotFoundException را در System::SmartPtr قرار ندهید."
type: docs
weight: 183
url: /fa/system.io/details_filenotfoundexception/
---
## جزئیات_FileNotFoundException کلاس

استثنائی که زمانی که تلاش برای دسترسی به فایلی که بر روی دیسک وجود ندارد انجام می‌شود، پرتاب می‌شود. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به‌جای آن از کلاس FileNotFoundException استفاده کنید. هرگز نمونه‌های کلاس FileNotFoundException را در [System::SmartPtr](../../system/smartptr/) قرار ندهید.

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | نام فایلی که باعث این استثناء می‌شود را برمی‌گرداند. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## موارد مرتبط

* کلاس [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)