---
title: Paragraph
second_title: مرجع API Aspose.Slides برای C++
description: یک پاراگراف متن را نمایندگی می‌کند.
type: docs
weight: 4616
url: /fa/aspose.slides/paragraph/
---
## کلاس Paragraph

Represents a paragraph of text.

```cpp
class Paragraph : public Aspose::Slides::IParagraph,
                  public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر حسب IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر حسب IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_EndParagraphPortionFormat](./get_endparagraphportionformat/)() override | ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\> [get_ParagraphFormat](./get_paragraphformat/)() override | شیء قالب‌بندی برای این پاراگراف را باز می‌گرداند. فقط خواندنی [IParagraphFormat](../iparagraphformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortion](../iportion/)\> [get_Portion](./get_portion/)(**int32_t**) override | یک بخش متن را در اندیس مشخص‌شده باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionCollection](../iportioncollection/)\> [get_Portions](./get_portions/)() override | مجموعه‌ای از بخش‌های متن را باز می‌گرداند. فقط خواندنی [IPortionCollection](../iportioncollection/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | متن ساده یک پاراگراف را دریافت می‌کند. خواندن [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دستگاه شمارش مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| **int32_t** [GetLinesCount](./getlinescount/)() override | تعداد خطوط در یک پاراگراف را دریافت می‌کند. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](./getrect/)() override | مختصات مستطیلی که پاراگراف را محاصره می‌کند را دریافت می‌کند. این مستطیل شامل تمام خطوط متن در پاراگراف، از جمله خطوط خالی، است. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نماینده یک نمونه از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | دنباله‌های با قالب‌بندی یکسان را ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌شدن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌کند. |
|  [Paragraph](./paragraph/)() | نمونه جدیدی از کلاس [Paragraph](./) را با ویژگی‌های پیش‌فرض مقداردهی اولیه می‌کند. |
|  [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Paragraph](./)\>) | سازنده کپی که یک نمونه جدید از کلاس [Paragraph](./) را مقداردهی اولیه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر اساس مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع به‌اشتراک‌گذاری‌شده را به مقدار مشخص کاهش می‌دهد. |
| void [set_EndParagraphPortionFormat](./set_endparagraphportionformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | متن ساده یک پاراگراف را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع به‌اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندانه‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را کاهش می‌دهد و مقدار آن را باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندانه‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری توسط عبارت C# lock() را غیرفعال می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندانه‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندانه‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IParagraph](../iparagraph/)
* کلاس [IDOMObject](../idomobject/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)