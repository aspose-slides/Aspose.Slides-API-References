---
title: AudioCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از فایل‌های صوتی جاسازی‌شده است.
type: docs
url: /fa/com.aspose.slides/audiocollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

نمایانگر یک مجموعه از فایل‌های صوتی جاسازی‌شده است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد فایل‌های صوتی موجود در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در شاخص تعیین‌شده را دریافت می‌کند. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | یک کپی از فایل صوتی را از یک ارائه دیگر اضافه می‌کند. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | صداها را به آرایه مشخص‌شده کپی می‌کند، شروع از شاخص معین. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان‌دهنده این است که دسترسی به مجموعه همگام‌سازی شده (امن برای چندنخی) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که مجموعه را پیمایش می‌کند، برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک ایترِتور جاوا برای کل مجموعه برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد فایل‌های صوتی موجود در مجموعه را برمی‌گرداند. فقط‌قابل‌خواندن int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


عنصر موجود در شاخص تعیین‌شده را دریافت می‌کند. فقط‌قابل‌خواندن [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


یک کپی از فایل صوتی را از یک ارائه دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | صوت منبع. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صدا اضافه‌شده.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که صوت از آن اضافه می‌شود. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صدا اضافه‌شده.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که صوت از آن اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صدا اضافه‌شده.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audioData | byte[] | بایت‌های صوتی. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صدا اضافه‌شده.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


صداها را به آرایه مشخص‌شده کپی می‌کند، شروع از شاخص معین.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه. |
| index | int | شاخص. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چندنخی) است. فقط‌قابل‌خواندن boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌قابل‌خواندن Object.

**بازگشت:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


یک شمارشگر که مجموعه را پیمایش می‌کند، برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


یک ایترِتور جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - یک java.util.Iterator برای کل مجموعه.