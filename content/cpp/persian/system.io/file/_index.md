---
title: File
second_title: Aspose.Slides برای مرجع API C++
description: روش‌هایی برای دستکاری فایل‌ها فراهم می‌کند. این یک نوع ایستای بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وسیله‌ای از آن نمونه بسازید.
type: docs
weight: 261
url: /fa/system.io/file/
---
## کلاس File


متدهایی برای دستکاری فایل‌ها فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وسیله‌ای از آن نمونه بسازید.

```cpp
class File
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | رشته‌ها را از مجموعهٔ مشخص‌شدهٔ رشته‌ها به فایل مشخص‌شده اضافه می‌کند با استفاده از رمزگذاری مشخص، به‌طوری که هر رشته در یک خط جدید نوشته می‌شود. اگر فایل مشخص‌شده وجود نداشته باشد، ساخته می‌شود. پس از نوشتن تمام رشته‌ها، فایل بسته می‌شود. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | رشتهٔ مشخص‌شده را به فایل مشخص‌شده اضافه می‌کند با استفاده از رمزگذاری مشخص. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | یک شیء [StreamWriter](../streamwriter/) ایجاد می‌کند که متن را به فایل مشخص‌شده اضافه می‌کند با استفاده از رمزگذاری UTF-8. اگر فایل مشخص‌شده وجود نداشته باشد، ساخته می‌شود. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | فایل مشخص‌شده را به مکان مشخص‌شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، یک پارامتر تعیین می‌کند که آیا باید بازنویسی شود یا نه. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | فایل جدیدی ایجاد می‌کند (یا موجود را بازنویسی می‌کند) و آن را برای دسترسی خواندن و نوشتن با استفاده از اندازهٔ بافر و گزینه‌های مشخص شده باز می‌کند. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | فایل جدیدی ایجاد می‌کند یا فایل موجود را برای نوشتن متن با رمزگذاری UTF-8 باز می‌کند. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | پیاده‌سازی نشده. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | فایل یا دایرکتوری مشخص‌شده را حذف می‌کند. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | پیاده‌سازی نشده. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | تشخیص می‌دهد آیا مسیر مشخص‌شده به فایلی موجود اشاره دارد یا خیر. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | ویژگی‌های موجودیت مشخص‌شده را برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | زمان ایجاد موجودیت مشخص‌شده را به‌صورت زمان محلی برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | زمان ایجاد موجودیت مشخص‌شده را به‌صورت زمان UTC برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | آخرین زمان دسترسی به موجودیت مشخص‌شده را به‌صورت زمان محلی برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | آخرین زمان دسترسی به موجودیت مشخص‌شده را به‌صورت زمان UTC برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | آخرین زمان نوشتن به موجودیت مشخص‌شده را به‌صورت زمان محلی برمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | آخرین زمان نوشتن به موجودیت مشخص‌شده را به‌صورت زمان UTC برمی‌گرداند. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | فایل مشخص‌شده را به مکان جدید منتقل می‌کند. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | فایل مشخص‌شده را در حالت مشخص برای خواندن و نوشتن باز می‌کند و بدون به‌اشتراک‌گذاری. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | فایل مشخص‌شده را در حالت مشخص، با نوع دسترسی مشخص و گزینهٔ به‌اشتراک‌گذاری مشخص باز می‌کند. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | فایل مشخص‌شده را فقط برای خواندن، در حالت 'Open' با دسترسی مشترک برای خواندن باز می‌کند. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | فایل موجود مشخص‌شده را برای خواندن متن با استفاده از رمزگذاری UTF-8 و بدون به‌اشتراک‌گذاری باز می‌کند. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | فایل مشخص‌شده را فقط برای نوشتن، در حالت 'OpenOrCreate' و بدون به‌اشتراک‌گذاری باز می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | محتویات فایل باینری مشخص‌شده را به یک آرایهٔ بایت می‌خواند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | محتویات فایل متنی مشخص‌شده را خط به خط به آرایه‌ای از رشته‌ها می‌خواند با استفاده از رمزگذاری کاراکتری مشخص. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | محتویات فایل متنی مشخص‌شده را به یک شیء واحد [String](../../system/string/) می‌خواند با استفاده از رمزگذاری کاراکتری مشخص. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | محتویات فایل متنی مشخص‌شده را خط به خط می‌خواند با استفاده از رمزگذاری کاراکتری مشخص و مجموعه‌ای قابل شمارش از رشته‌ها را برمی‌گرداند که هرکدام نمایانگر یک خط از محتویات فایل هستند. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | محتویات یک فایل را با فایل دیگر جایگزین می‌کند و یک نسخهٔ پشتیبان از فایل جایگزین‌شده ایجاد می‌کند. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | ویژگی‌های مشخص‌شده را بر روی فایل مشخص‌شده تنظیم می‌کند. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | پیاده‌سازی نشده. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | پیاده‌سازی نشده. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | پیاده‌سازی نشده. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | پیاده‌سازی نشده. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیت مشخص‌شده را به‌صورت زمان محلی تنظیم می‌کند. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیت مشخص‌شده را به‌صورت زمان UTC تنظیم می‌کند. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | فایل باینری مشخص‌شده را بازنویسی می‌کند و بایت‌های مشخص‌شده را در آن می‌نویسد. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | یک فایل متنی جدید ایجاد می‌کند یا موجود را بازنویسی می‌کند و تمام رشته‌ها را از مجموعهٔ قابل شمارش مشخص به آن می‌نویسد، به‌طوری که هر رشته در یک خط جدید باشد، با استفاده از رمزگذاری مشخص. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | یک فایل متنی جدید ایجاد می‌کند یا موجود را بازنویسی می‌کند و تمام رشته‌ها را از آرایهٔ مشخص‌شدهٔ رشته‌ها به آن می‌نویسد، به‌طوری که هر رشته در یک خط جدید باشد، با استفاده از رمزگذاری مشخص. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | یک فایل متنی جدید ایجاد می‌کند یا موجود را بازنویسی می‌کند و محتویات رشتهٔ مشخص‌شده را به آن می‌نویسد با استفاده از رمزگذاری مشخص. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | مقدار پیش‌فرض تعداد بایت‌های بافرشده هنگام خواندن از و نوشتن به یک فایل. |

## موارد مرتبط

* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)