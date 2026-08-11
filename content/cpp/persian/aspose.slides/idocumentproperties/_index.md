---
title: IDocumentProperties
second_title: Aspose.Slides برای C++ مرجع API
description: خواص یک ارائه را نشان می‌دهد.
type: docs
weight: 1977
url: /fa/aspose.slides/idocumentproperties/
---
## IDocumentProperties کلاس

خواص یک ارائه را نشان می‌دهد.

```cpp
class IDocumentProperties : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | مقادیر پیش‌فرض را برای تمام ویژگی‌های builtIn پاک و تنظیم می‌کند. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | تمام ویژگی‌های custom را حذف می‌کند. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | وجود یک ویژگی custom با نام مشخص را بررسی می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارزش را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | قالب یک برنامه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | نسخه برنامه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | نویسنده یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | دسته‌بندی یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | نظرات یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | ویژگی شرکت را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | وضعیت محتوای یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | نوع محتوای یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | تعداد ویژگی‌های custom که در یک مجموعه وجود دارند را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط-خواندنی [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. فقط-خواندنی [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | تعداد اسلایدهای مخفی در یک سند ارائه را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | ویژگی HyperlinkBase سند را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | مشخص می‌کند که یک یا چند پیوند در این قسمت به‌صورت انحصاری توسط یک تولیدکننده به‌روز شده‌اند. تولیدکننده بعدی که این سند را باز می‌کند باید روابط پیوندها را با پیوندهای جدیدی که در این قسمت مشخص شده‌اند به‌روز کند. فقط **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | کلیدواژه‌های یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. فقط-خواندنی [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط-خواندنی در مورد Presentation.DocumentProperties (زیرا در حین فرآیند ذخیره‌سازی شیء [IPresentation](../ipresentation/) به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونه [DocumentProperties](../documentproperties/) که توسط متد [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) برگردانده می‌شود تغییر یابد. لطفاً مثال در خلاصهٔ متد [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) را ببینید. |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | نشان می‌دهد آیا پیوندهای یک سند به‌روز هستند یا نه. برای نشان دادن به‌روزرسانی پیوندها این عنصر را به **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند این عنصر را به **false** تنظیم کنید. فقط **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | ویژگی manager را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | تعداد کل کلیپ‌های صوتی یا ویدئویی موجود در سند را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | نام برنامه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | تعداد اسلایدهای یک ارائه که حاوی یادداشت هستند را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | تعداد کل پاراگراف‌های یافت‌شده در یک سند (در صورت وجود) را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | قالب موردنظر یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | شمارهٔ بازبینی ارائه را برمی‌گرداند. فقط **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | حالت نمایش تصویر کوچک سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌گذاری تصویر کوچک به نمایش این عنصر را به **true** تنظیم کنید. برای فعال‌سازی برش تصویر کوچک به‌طوری که فقط قسمت‌های متناسب با نمایش نشان داده شوند این عنصر را به **false** تنظیم کنید. فقط **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | مشخص می‌کند آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. فقط **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | تعداد کل اسلایدهای یک سند ارائه را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | موضوع یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | عنوان یک ارائه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه نمایه‌های مفهومی از بخش‌های سند هستند. فقط-خواندنی [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | کل زمان ویرایش یک ارائه. فقط-خواندنی [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | کل تعداد واژه‌های موجود در یک سند را مشخص می‌کند. فقط-خواندنی **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | نام یک ویژگی custom را در شاخص مشخص برمی‌گرداند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | مقدار بولی نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | مقدار عدد صحیح نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | مقدار DateTime نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | مقدار رشته‌ای نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | مقدار float نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | مقدار double نام‌دار را از ویژگی‌های custom دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء custom را فعال می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های custom سند دریافت می‌کند (متادیتای Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | ویژگی custom مرتبط با یک نام مشخص را برمی‌گرداند. فقط-خواندنی [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | ویژگی custom مرتبط با یک نام مشخص را تنظیم می‌کند. نوشتنی [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع custom را فراهم می‌آورد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های مشتق‌شده از طریق کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های مشتق‌شده از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع ارزش را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | یک ویژگی custom مرتبط با یک نام مشخص را حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به میزان مقدار مشخص کاهش می‌دهد. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | قالب یک برنامه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | نویسنده یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | دسته‌بندی یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | نظرات یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | ویژگی شرکت را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | وضعیت محتوای یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | نوع محتوای یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. نوشتنی [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | ویژگی HyperlinkBase سند را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | مشخص می‌کند که یک یا چند پیوند در این قسمت به‌صورت انحصاری توسط یک تولیدکننده به‌روز شده‌اند. تولیدکننده بعدی که این سند را باز می‌کند باید روابط پیوندها را با پیوندهای جدیدی که در این قسمت مشخص شده‌اند به‌روز کند. نوشتنی **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | کلیدواژه‌های یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | تاریخ آخرین چاپ یک ارائه را برمی‌گرداند. نوشتنی [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | نام آخرین شخصی که یک ارائه را تغییر داده است را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط-خواندنی در مورد Presentation.DocumentProperties (زیرا در حین فرآیند ذخیره‌سازی شیء [IPresentation](../ipresentation/) به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونه [DocumentProperties](../documentproperties/) که توسط متد [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) برگردانده می‌شود تغییر یابد. لطفاً مثال در خلاصهٔ متد [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) را ببینید. |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | نشان می‌دهد آیا پیوندهای یک سند به‌روز هستند یا نه. برای نشان دادن به‌روز بودن پیوندها این عنصر را به **true** تنظیم کنید. برای نشان دادن منقضی شدن پیوندها این عنصر را به **false** تنظیم کنید. نوشتنی **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | ویژگی manager را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | نام برنامه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | قالب موردنظر یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | شمارهٔ بازبینی ارائه را تنظیم می‌کند. نوشتنی **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | حالت نمایش تصویر کوچک سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌گذاری تصویر کوچک به نمایش این عنصر را به **true** تنظیم کنید. برای فعال‌سازی برش تصویر کوچک به‌طوری که فقط بخش‌های متناسب با نمایش نشان داده شوند این عنصر را به **false** تنظیم کنید. نوشتنی **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | مشخص می‌کند آیا ارائه بین چندین نفر به‌اشتراک گذاشته شده است یا نه. نوشتنی **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | موضوع یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | عنوان یک ارائه را تنظیم می‌کند. نوشتنی [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | کل زمان ویرایش یک ارائه. نوشتنی [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | یک ویژگی بولی نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | یک ویژگی عدد صحیح نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | یک ویژگی DateTime نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | یک ویژگی رشته‌ای نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | یک ویژگی float نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | یک ویژگی double نام‌دار custom را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به یک اشاره‌گر ضعیف (به‌جای اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار کنونی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء custom به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستور C# lock() را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)