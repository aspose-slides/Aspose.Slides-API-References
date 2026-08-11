---
title: "System::StringExtra"
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 911
url: /fa/system.stringextra/
---
## توابع

| تابع | توضیح |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | آرایهٔ string را به هم می‌چسباند. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | رشته‌ها را به هم می‌چسباند. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | رشته‌ها را به هم می‌چسباند. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | رشته‌ها را به هم می‌چسباند. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | اشیاء متعدد را به رشته تبدیل کرده و رشته‌های حاصل را به هم می‌چسباند. تخصیص برای انواع [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | اشیاء متعدد را به رشته تبدیل کرده و رشته‌های حاصل را به هم می‌چسباند. تخصیص برای انواع عددی. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | اشیاء متعدد را به رشته تبدیل کرده و رشته‌های حاصل را به هم می‌چسباند. تخصیص برای ساختارها و سایر انواع مقدار. |