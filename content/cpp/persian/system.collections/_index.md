---
title: "System::Collections"
second_title: "Aspose.Slides برای C++ مرجع API"
description: 
type: docs
weight: 300
url: /fa/system.collections/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) از بیت‌ها که می‌توانند با اندیس آدرس‌گذاری شوند. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا موجب خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در نشانگر [System::SmartPtr](../system/smartptr/) بسته‌بندی کنید و از این نشانگر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید. |
| [BitArrayPtr](./bitarrayptr/) | اشاره‌گری به [BitArray](./bitarray/). این نوع یک اشاره‌گر برای مدیریت حذف اشیاء دیگر است. باید بر روی پشته تخصیص داده شود و به توابع یا به صورت مقدار یا به صورت مرجع ثابت (const) پاس داده شود. |
| [CollectionBase](./collectionbase/) | یک کلاس پایهٔ انتزاعی برای یک مجموعهٔ با نوع قوی فراهم می‌کند. |
| [ICollection](./icollection/) | رابط مجموعهٔ غیرژنریک را تعریف می‌کند. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) رابط پایه برای همهٔ مجموعه‌های غیرژنریک است که می‌توان آن‌ها را شمارش کرد. |
| [IEnumerator](./ienumerator/) | رابط شمارنده‌ای که می‌تواند برای تکرار بر روی برخی عناصر استفاده شود. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در نشانگر [System::SmartPtr](../system/smartptr/) بسته‌بندی کنید و از این نشانگر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | لفافه‌ای که پیاده‌سازی غیرژنریک [IEnumerator](./ienumerator/) را بر روی Iterator عمومی [IEnumeratorImplRefType](./ienumeratorimplreftype/) ایجاد می‌کند - بسته برای انواع مرجع. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | لفافه‌ای که پیاده‌سازی غیرژنریک [IEnumerator](./ienumerator/) را بر روی Iterator عمومی [IEnumeratorImplRefType](./ienumeratorimplreftype/) ایجاد می‌کند - بسته برای انواع مقدار. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) نمایانگر یک مجموعهٔ غیرژنریک از اشیاء است که می‌توان به‌صورت جداگانه توسط اندیس به آن‌ها دسترسی داشت. |
| [IListImplRefType](./ilistimplreftype/) | قطعه کدی که رابط [System::Collections::IList](./ilist/) را بر روی شیء [System::Collections::Generic::List](../system.collections.generic/list/) پیاده‌سازی می‌کند - پیاده‌سازی برای انواع مرجع. |
| [IListImplValueType](./ilistimplvaluetype/) | قطعه کدی که رابط [System::Collections::IList](./ilist/) را بر روی شیء [System::Collections::Generic::List](../system.collections.generic/list/) پیاده‌سازی می‌کند - پیاده‌سازی برای انواع مقدار. |
| [IListWrapper](./ilistwrapper/) | رابطی برای پشتیبانی از تبدیل از مجموعهٔ عمومی به مجموعهٔ غیرژنریک. |
| [Invalidatable](./invalidatable/) | کلاسی که امکان پیگیری وضعیت فرزندان خود را از طریق اشیاء [InvalidatableTracker](./invalidatabletracker/) فراهم می‌کند. |
| [InvalidatableTracker](./invalidatabletracker/) | کلاسی که ردیاب‌های اشیاء [Invalidatable](./invalidatable/) را پیاده‌سازی می‌کند. |