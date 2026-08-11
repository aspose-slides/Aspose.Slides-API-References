---
title: ModernComment
second_title: مرجع API Aspose.Slides برای C++
description: یک نظر را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 4512
url: /fa/aspose.slides/moderncomment/
---
## کلاس ModernComment

یک نظر را بر روی اسلاید نشان می‌دهد.

```cpp
class ModernComment : public Aspose::Slides::Comment,
                      public Aspose::Slides::IModernComment
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../comment/get_author/)() override | نویسنده‌ی یک نظر را برمی‌گرداند. فقط-خواندنی [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](../comment/get_createdtime/)() override | زمان ایجاد یک نظر را برمی‌گرداند. تنظیم این ویژگی به [DateTime::MinValue](../../system/datetime/minvalue/) به این معنی است که زمان نظری تنظیم نشده است. فقط [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../comment/get_parentcomment/)() override | نظر والد را دریافت می‌کند. فقط [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../comment/get_position/)() override | موقعیت یک نظر روی اسلاید را برمی‌گرداند. فقط [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() override | یک شکل مرتبط با نظر را برمی‌گرداند. فقط-خواندنی [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../comment/get_slide/)() override | اسلاید والد یک نظر را برمی‌گرداند. فقط-خواندنی [ISlide](../islide/). |
| [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() override | وضعیت نظر را دریافت می‌کند. فقط [ModernCommentStatus](../moderncommentstatus/). |
| [System::String](../../system/string/) [get_Text](../comment/get_text/)() override | متن ساده یک نظر اسلاید را برمی‌گرداند. فقط [System::String](../../system/string/). |
| **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() override | طول انتخاب متن در فریم متن را دریافت می‌کند اگر نظر با [AutoShape](../autoshape/) مرتبط باشد. فقط **int32_t**. |
| **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() override | موقعیت شروع انتخاب متن در فریم متن را دریافت می‌کند اگر نظر با [AutoShape](../autoshape/) مرتبط باشد. فقط **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های فرزند را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| void [Remove](../comment/remove/)() override | نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_CreatedTime](../comment/set_createdtime/)([System::DateTime](../../system/datetime/)) override | زمان ایجاد نظر را تنظیم می‌کند. تنظیم این ویژگی به [DateTime::MinValue](../../system/datetime/minvalue/) به این معنی است که زمان نظری تنظیم نشده است. نوشتن [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](../comment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | نظر والد را تنظیم می‌کند. نوشتن [IComment](../icomment/). |
| void [set_Position](../comment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | موقعیت نظر روی اسلاید را تنظیم می‌کند. نوشتن [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) override | وضعیت نظر را تنظیم می‌کند. نوشتن [ModernCommentStatus](../moderncommentstatus/). |
| void [set_Text](../comment/set_text/)([System::String](../../system/string/)) override | متن ساده نظر اسلاید را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) override | طول انتخاب متن در فریم متن را تنظیم می‌کند اگر نظر با [AutoShape](../autoshape/) مرتبط باشد. نوشتن **int32_t**. |
| void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) override | موقعیت شروع انتخاب متن در فریم متن را تنظیم می‌کند اگر نظر با [AutoShape](../autoshape/) مرتبط باشد. نوشتن **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو n'th را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | به‌کارگیری سازه typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## یادداشت‌ها



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## مراجع

* کلاس [Comment](../comment/)
* کلاس [IModernComment](../imoderncomment/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)