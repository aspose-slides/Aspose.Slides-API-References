---
title: IMasterSlideHeaderFooterManager
second_title: مرجع برنامه‌نویسی Aspose.Slides برای C++
description: نماینده‌ای که رفتار پاورقی اسلاید اصلی، نگهدارنده‌های تاریخ-زمان، شماره صفحه و تمام نگهدارنده‌های فرزند را حفظ می‌کند. نگهدارنده‌های فرزند به این معنا هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند.
type: docs
weight: 2952
url: /fa/aspose.slides/imasterslideheaderfootermanager/
---
## IMasterSlideHeaderFooterManager کلاس


Represents manager which holds behavior of the master slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending layout slides and depending slides. Depending layout slides and slides use and depend on master slide.

```cpp
class IMasterSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | دریافت مقدار نشان‌دهندهٔ وجود یک نگهدارنده تاریخ-زمان. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | دریافت مقدار نشان‌دهندهٔ وجود یک نگهدارنده پاورقی. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | دریافت مقدار نشان‌دهندهٔ وجود یک نگهدارنده شماره صفحه. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده‌است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C#. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شیء. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به وسیلهٔ مقایسهٔ ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | متن را در نگهدارندهٔ تاریخ-زمان اسلاید اصلی و تمام نگهدارنده‌های تاریخ-زمان فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ تاریخ-زمان اسلاید اصلی و تمام نگهدارنده‌های تاریخ-زمان فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | متن را در نگهدارندهٔ تاریخ-زمان اسلاید تنظیم می‌کند. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ تاریخ-زمان اسلاید را تغییر می‌دهد. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | متن را در نگهدارندهٔ پاورقی اسلاید اصلی و تمام نگهدارنده‌های پاورقی فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ پاورقی اسلاید اصلی و تمام نگهدارنده‌های پاورقی فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | متن را در نگهدارندهٔ پاورقی اسلاید تنظیم می‌کند. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ پاورقی اسلاید را تغییر می‌دهد. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ شماره صفحه اسلاید اصلی و تمام نگهدارنده‌های شماره صفحه فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | قابلیت دیده شدن نگهدارندهٔ شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب شمارهٔ n را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارندهٔ مرجع مشترک. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش و بازگرداندن شمارندهٔ مرجع مشترک. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() در C#. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارندهٔ مرجع ضعیف. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارندهٔ مرجع ضعیف. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)