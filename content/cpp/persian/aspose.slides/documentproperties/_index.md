---
title: DocumentProperties
second_title: Aspose.Slides برای C++ مرجع API
description: خصوصیات یک ارائه را نشان می‌دهد.
type: docs
weight: 794
url: /fa/aspose.slides/documentproperties/
---
## کلاس DocumentProperties

خصوصیات یک ارائه را نمایان می‌سازد.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## متدها

| متد | توضیح |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | تمام خصوصیات builtIn را پاک کرده و مقادیر پیش‌فرض را تنظیم می‌کند. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | تمام خصوصیات سفارشی را حذف می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخه‌ی کپی از شیء کنونی ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | یک نسخه‌ی کپی از شیء کنونی ایجاد می‌کند. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | وجود یک خصوصیت سفارشی با نام مشخص‌شده را بررسی می‌کند. |
| [DocumentProperties](./documentproperties/)() | نمونه‌ی جدیدی از کلاس [DocumentProperties](./) را مقداردهی اولیه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشاری double به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | قالب یک برنامه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | نسخهٔ برنامه را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | نویسندهٔ یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | دستهٔ یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | نظرات یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | خصوصیت شرکت را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | وضعیت محتوا یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | نوع محتوا یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | تعداد واقعی خصوصیات سفارشی موجود در یک مجموعه را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. ببینید [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | گروه‌بندی قسمت‌های سند و تعداد قسمت‌ها در هر گروه را نشان می‌دهد. فقط-خواندنی [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | تعداد اسلایدهای مخفی در سند ارائه را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | خصوصیت HyperlinkBase سند را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | مشخص می‌کند که یک یا چند پیوند در این بخش به‌طور انحصاری توسط یک تولیدکننده به‌روز شده‌اند. تولیدکنندهٔ بعدی که این سند را باز می‌کند، روابط پیوندها را با پیوندهای جدید مشخص‌شده در این بخش به‌روز خواهد کرد. فقط-خواندنی **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | کلیدواژه‌های یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | تاریخی که ارائه آخرین بار چاپ شده است را برمی‌گرداند. ببینید [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | نام آخرین فردی که ارائه را اصلاح کرده است را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | تاریخ آخرین اصلاح ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط-خواندنی در صورت [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (چون در طول فرآیند ذخیره‌سازی شیء [IPresentation](../ipresentation/) به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونهٔ [DocumentProperties](./) که توسط متد [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) برگردانده می‌شود، تغییر یابد. لطفاً مثال را در خلاصهٔ متد [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) ببینید. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | مشخص می‌کند که آیا پیوندهای یک سند به‌روز هستند یا نه. برای نشان دادن به‌روزرسانی پیوندها، این عنصر را به **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند، این عنصر را به **false** تنظیم کنید. فقط-خواندنی **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | خصوصیت مدیر را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | تعداد کل کلیپ‌های صوتی یا ویدئویی موجود در سند را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | نام برنامه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | تعداد اسلایدهای ارائه‌ای که حاوی یادداشت هستند را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | تعداد کل پاراگراف‌های یافت‌شده در یک سند (در صورت امکان) را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | قالب مورد نظر یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | شمارهٔ بازنگری ارائه را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | حالت نمایش تصویر بندانگشتی سند را مشخص می‌کند. برای فعال‌سازی مقیاس‌گذاری تصویر بندانگشتی به نمایش، این عنصر را به **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشتی به‌طوری‌که فقط بخش‌های متناسب با نمایش نشان داده شوند، این عنصر را به **false** تنظیم کنید. فقط-خواندنی **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | مشخص می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. فقط-خواندنی **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | تعداد کل اسلایدهای موجود در سند ارائه را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | موضوع یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | عنوان یک ارائه را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه نمایه‌های مفهومی از بخش‌های سند هستند. فقط-خواندنی [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | کل زمان ویرایش یک ارائه. ببینید [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | تعداد کل کلمات موجود در یک سند را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | نام یک خصوصیت سفارشی را در ایندکس مشخص‌شده بازمی‌گرداند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | مقدار بولی با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | مقدار عدد صحیح با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | مقدار DateTime با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | مقدار رشته‌ای با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | مقدار float با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | مقدار double با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | یک آرایه از برچسب‌های حساسیت را از خصوصیات سفارشی سند دریافت می‌کند (متادیتای Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | خصوصیت سفارشی مرتبط با نام مشخص‌شده را برمی‌گرداند. ببینید [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | خصوصیت سفارشی مرتبط با نام مشخص‌شده را تنظیم می‌کند. بنویسید [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | یک خصوصیت سفارشی مرتبط با نام مشخص‌شده را حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | قالب یک برنامه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | نویسندهٔ یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | دستهٔ یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | نظرات یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | خصوصیت شرکت را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | وضعیت محتوا یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | نوع محتوا یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. بنویسید [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | خصوصیت سند HyperlinkBase را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | مشخص می‌کند که یک یا چند پیوند در این بخش به‌طور انحصاری توسط یک تولیدکننده به‌روز شده‌اند. تولیدکنندهٔ بعدی که این سند را باز می‌کند، روابط پیوندها را با پیوندهای جدید مشخص‌شده در این بخش به‌روز خواهد کرد. بنویسید **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | کلیدواژه‌های یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | تاریخ آخرین چاپ ارائه را برمی‌گرداند. بنویسید [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | نام آخرین فردی که ارائه را اصلاح کرده است را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | تاریخ آخرین اصلاح ارائه را برمی‌گرداند. مقادیر به زمان UTC هستند. فقط-خواندنی در صورت [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (زیرا در طول فرآیند ذخیره‌سازی شیء [IPresentation](../ipresentation/) به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونهٔ [DocumentProperties](./) که توسط متد [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) برگردانده می‌شود، تغییر یابد. لطفاً مثال را در خلاصهٔ متد [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) ببینید. بنویسید. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | مشخص می‌کند که آیا پیوندهای یک سند به‌روز هستند یا نه. برای نشان دادن به‌روزرسانی پیوندها، این عنصر را به **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند، این عنصر را به **false** تنظیم کنید. بنویسید **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | خصوصیت مدیر را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | نام برنامه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | قالب مورد نظر یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | شمارهٔ بازنگری ارائه را تنظیم می‌کند. بنویسید **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | حالت نمایش تصویر بندانگشتی سند را مشخص می‌کند. برای فعال‌سازی مقیاس‌گذاری تصویر بندانگشتی به نمایش، این عنصر را به **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشتی به‌طوری‌که فقط بخش‌های متناسب با نمایش نشان داده شوند، این عنصر را به **false** تنظیم کنید. بنویسید **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | مشخص می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا نه. بنویسید **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | موضوع یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | عنوان یک ارائه را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | کل زمان ویرایش یک ارائه را تنظیم می‌کند. بنویسید [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | یک خصوصیت سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | یک خصوصیت سفارشی عدد صحیح با نام مشخص را تنظیم می‌کند. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | یک خصوصیت سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | یک خصوصیت سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | یک خصوصیت سفارشی float با نام مشخص را تنظیم می‌کند. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | یک خصوصیت سفارشی double با نام مشخص را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگمان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را آزاد می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## توضیحات

مثال زیر نشان می‌دهد چگونه به خصوصیات پیش‌فرض PowerPoint [Presentation](../presentation/) دسترسی پیدا کنید.

```cpp
// نمونه‌سازی کلاس Presentation که نمایانگر ارائه است
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
مثال زیر نشان می‌دهد چگونه خصوصیات پیش‌فرض PowerPoint [Presentation](../presentation/) را تغییر دهید.

```cpp
// نمونه‌سازی کلاس Presentation که نمایانگر Presentation است
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// ایجاد یک ارجاع به شیء IDocumentProperties مرتبط با Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Set the builtin properties
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Save your presentation to a file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## مراجع

* کلاس [IDocumentProperties](../idocumentproperties/)
* کلاس [IGenericCloneable](../igenericcloneable/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)