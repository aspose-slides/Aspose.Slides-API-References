---
title: Read()
second_title: Aspose.Slides for C++ مرجع API
description: یک نویسهٔ واحد را از جریان می‌خواند.
type: docs
weight: 40
url: /fa/system.io/textreader/read/
---
## TextReader::Read() متد

یک نویسهٔ واحد را از جریان می‌خواند.

```cpp
virtual int System::IO::TextReader::Read()
```

### مقدار بازگشت

نویسه‌ای که با رمزگذاری UTF-16 کدگذاری شده است را می‌خواند؛ اگر نویسه خوانده شده توسط دو کدپوینت در رمزگذاری UTF-16 نمایان شود، تنها سوارگت بالاتر برگردانده می‌شود.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) متد

تعداد مشخصی از نویسه‌ها را از جریان می‌خواند و آن‌ها را در آرایهٔ کاراکتر مشخص شده، از موقعیت مشخص شده، می‌نویسد.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | آرایهٔ کاراکتر UTF-16 که نویسه‌های خوانده شده از جریان در آن نوشته می‌شوند |
| index | int | یک اندیس ۰-پایه در **buffer** که نوشتن از آنجا آغاز می‌شود |
| count | int | تعداد نویسه‌هایی که از جریان خوانده می‌شوند |

### مقدار بازگشت

تعداد نویسه‌های خوانده‌شده از جریان

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)