---
title: "System::BoxedValueDetail"
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 287
url: /fa/system.boxedvaluedetail/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [Comparable](./comparable/) | پیاده‌سازی سادهٔ IComparable<> |
| [NonComparable](./noncomparable/) | نوع پایهٔ ساختگی برای انواع جعبه‌ای که IComparable<> را پیاده‌سازی نمی‌کنند |
## ساختارها

| ساختار | توضیح |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | قالب شرطی که بررسی می‌کند آیا شیء جعبه‌ای باید خود به‌تنهایی اینترفیس داده شده را پیاده‌سازی کند. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) پیاده‌سازی می‌کند [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | قالب شرطی که بررسی می‌کند آیا شیء جعبه‌ای باید خود به‌تنهایی اینترفیس [IComparable](../system/icomparable/) را پیاده‌سازی کند. |
## توابع

| تابع | توضیح |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | برابری مقدار مشخص‌شده را با استفاده از [operator==()](../system/operator_equal_equal/) تعیین می‌کند. |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | برابری مقدار مشخص‌شده را با استفاده از متد [System::Object::Equals()](../system/object/equals/) تعیین می‌کند. |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | دو مقدار عددی ممیز شناور تک دقت را مقایسه می‌کند. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | دو مقدار عددی ممیز شناور دو دقت را مقایسه می‌کند. |