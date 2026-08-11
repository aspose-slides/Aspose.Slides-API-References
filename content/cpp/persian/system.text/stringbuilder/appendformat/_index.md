---
title: AppendFormat()
second_title: Aspose.Slides برای مرجع API C++
description: یک رشته قالب‌بندی‌شده را به سازنده اضافه می‌کند.
type: docs
weight: 131
url: /fa/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) متد

یک رشته فرمت‌شده را به سازنده اضافه می‌کند.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TArgs | نوع آرگومان‌ها. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | رشته قالب. |
| args | const TArgs\&... | آرگومان‌هایی که در موقعیت‌های رشته قالب قرار می‌گیرند. |

### مقدار بازگشتی

این اشاره‌گر.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs&...) متد

یک رشته فرمت‌شده را به سازنده اضافه می‌کند.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TArgs | نوع آرگومان‌ها. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | فراهم‌کننده قالب؛ نادیده گرفته می‌شود. |
| format | const [String](../../../system/string/)\& | رشته قالب. |
| args | const TArgs\&... | آرگومان‌هایی که در موقعیت‌های رشته قالب قرار می‌گیرند. |

### مقدار بازگشتی

این اشاره‌گر.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [StringBuilder](../)
* کلاس [String](../../../system/string/)
* کلاس [IFormatProvider](../../../system/iformatprovider/)
* فضازمان [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)