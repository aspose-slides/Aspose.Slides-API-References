---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 352
url: /fa/system.collections.generic.details/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | قابلیت شمارشی که توسط روش‌های افزودنی IEnumerable.Cast() و IEnumerable.OfType() استفاده می‌شود. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | قابلیت شمارشی که توسط روش افزودنی IEnumerable.Select() استفاده می‌شود. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | شمارنده‌ای که توسط روش افزودنی IEnumerable.Cast() استفاده می‌شود. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | شمارنده‌ای که توسط روش افزودنی IEnumerable.OfType() استفاده می‌شود. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | شمارنده‌ای که توسط روش افزودنی IEnumerable.Select() استفاده می‌شود. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## ساختارها

| ساختار | توضیح |
| --- | --- |
| [ComparerType](./comparertype/) | عناصر را با استفاده از معنای 'less' مقایسه می‌کند. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | عناصر را با استفاده از معنای 'less' مقایسه می‌کند. |
| [has_method_compareto](./has_method_compareto/) | بررسی می‌کند که آیا متد CompareTo در نوع مشخص شده وجود دارد یا نه. اگر وجود داشته باشد، از std::true_type ارث می‌برد، در غیر اینصورت از std::false_type ارث می‌برد. می‌تواند در std::enable_if استفاده شود. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | بررسی می‌کند که آیا متد CompareTo(SharedPtr<T>) در نوع مشخص شده وجود دارد یا نه. اگر وجود داشته باشد، از std::true_type ارث می‌برد، در غیر اینصورت از std::false_type ارث می‌برد. می‌تواند در std::enable_if استفاده شود. |
| [IsEqualExist](./isequalexist/) | بررسی می‌کند که آیا نوع عملگر == را فراهم می‌کند. |
## توابع

| تابع | توضیح |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | بررسی می‌کند که آیا اندیس خارج از محدودهٔ کانتینر است، به‌جز اندازهٔ کانتینر. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | بررسی می‌کند که آیا اندیس خارج از محدودهٔ کانتینر است، به‌جز اندازهٔ کانتینر. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | بررسی می‌کند که آیا اندیس خارج از محدودهٔ کانتینر است، شامل اندازهٔ کانتینر. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | بررسی می‌کند که آیا اندیس خارج از محدودهٔ کانتینر است، شامل اندازهٔ کانتینر. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | تابع کمکی برای تعیین اینکه آیا کلاس خاص عملگر == را دارد. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | تابع کمکی برای تعیین اینکه آیا کلاس خاص عملگر == را دارد. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | سعی می‌کند اولین عنصر مجموعه را دریافت کند. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | سعی می‌کند اولین عنصر مجموعه را که شرایط تابع پیش‌شرط را برآورده می‌کند، دریافت کند. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | سعی می‌کند آخرین عنصر مجموعه را دریافت کند. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | تعریف نوع ساختگی برای بررسی وجود عملگر ==. |