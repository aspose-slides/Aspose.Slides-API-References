---
title: BinaryReader
second_title: مرجع API Aspose.Slides برای C++
description: "نمایشی برای یک خواننده که انواع داده‌های اولیه را به‌عنوان داده‌های باینری در یک رمزگذاری خاص می‌خواند. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 92
url: /fa/system.io/binaryreader/
---
## کلاس BinaryReader

نمایشگر (reader)یی را که انواع داده‌های اولیه را به‌عنوان داده‌های باینری در یک رمزگذاری خاص می‌خواند، نمایندگی می‌کند. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را داخل یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class BinaryReader : public System::IDisposable
```

## متدها

| Method | توضیح |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | یک نمونه از کلاس [BinaryReader](./) را می‌سازد که داده‌ها را از جریان مشخص‌شده با استفاده از رمزگذاری UTF-8 می‌خواند. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | یک نمونه از کلاس [BinaryReader](./) را می‌سازد که داده‌ها را از جریان مشخص‌شده با استفاده از رمزگذاری تعیین‌شده می‌خواند. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | یک نمونه از کلاس [BinaryReader](./) را می‌سازد که داده‌ها را از جریان مشخص‌شده با استفاده از رمزگذاری تعیین‌شده می‌خواند. |
| virtual void [Close](./close/)() | شیء [BinaryReader](./) فعلی و جریان ورودی زیربنایی را می‌بندد. |
| void [Dispose](./dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | جریان ورودی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگزار 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| virtual int [PeekChar](./peekchar/)() | یک کاراکتر تک از جریان ورودی می‌خواند بدون تغییر مکان‌نمای خواندن جریان. |
| virtual int [Read](./read/)() | یک کاراکتر تک از جریان ورودی می‌خواند. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد مشخصی بایت را از جریان ورودی می‌خواند و آن‌ها را در آرایهٔ بایتی مشخص‌شده می‌نویسد. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | تعداد مشخصی کاراکتر را از جریان ورودی می‌خواند، آن‌ها را به رمزگذاری UTF-16 تبدیل می‌کند و کاراکترهای UTF-16 حاصل را در آرایهٔ کاراکتری مشخص‌شده از موقعیت مشخص‌شده می‌نویسد. |
| virtual **bool** [ReadBoolean](./readboolean/)() | یک بایت تک از جریان ورودی می‌خواند و نمایندگی منطقی آن را برمی‌گرداند. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | یک بایت تک از جریان ورودی می‌خواند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | تعداد مشخصی بایت را از جریان ورودی می‌خواند. |
| virtual char_t [ReadChar](./readchar/)() | یک کاراکتر تک از جریان ورودی می‌خواند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | تعداد مشخصی کاراکتر را از جریان ورودی می‌خواند و آن‌ها را با رمزگذاری UTF-16 برمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | پیاده‌سازی نشده. |
| virtual **double** [ReadDouble](./readdouble/)() | ۸ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار نقطه شناور با دقت دو برابر (double) برمی‌گرداند. |
| virtual **int16_t** [ReadInt16](./readint16/)() | ۲ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح ۱۶‌بیتی برمی‌گرداند. |
| virtual int [ReadInt32](./readint32/)() | ۴ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح ۳۲‌بیتی برمی‌گرداند. |
| virtual **int64_t** [ReadInt64](./readint64/)() | ۸ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح ۶۴‌بیتی برمی‌گرداند. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | یک بایت تک از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح ۸‌بیتی با علامت برمی‌گرداند. |
| virtual **float** [ReadSingle](./readsingle/)() | ۴ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار نقطه شناور تک‌دقت (float) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | یک رشته از جریان جاری می‌خواند. رشته پیشوندی شامل طول است که به‌صورت یک عدد صحیح هفت بیتی به‌تدریج رمزگذاری می‌شود. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | ۲ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح بدون علامت ۱۶‌بیتی برمی‌گرداند. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | ۴ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح بدون علامت ۳۲‌بیتی برمی‌گرداند. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | ۸ بایت را از جریان ورودی می‌خواند و به‌عنوان مقدار عدد صحیح بدون علامت ۶۴‌بیتی برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابله مرجع برای شیء نوع مقدار با nullptr انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~BinaryReader](./~binaryreader/)() | دست‌سازنده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## مراجع

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)