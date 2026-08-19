---
title: AudioCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از فایل‌های صوتی جاسازی‌شده.
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

نمایانگر مجموعه‌ای از فایل‌های صوتی جاسازی‌شده.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد فایل‌های صوتی در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص شده دریافت می‌کند. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | یک نسخه از فایل صوتی را از ارائه‌ای دیگر اضافه می‌کند. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | یک صوت را از یک جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | یک صوت را از یک جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | صداها را به آرایه مشخص شده، شروع از اندیس تعیین‌شده، کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (امن از نظر چندنخی) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمان‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد فایل‌های صوتی در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

عنصر را در اندیس مشخص‌شده دریافت می‌کند. فقط-خواندنی [IAudio](../../com.aspose.slides/iaudio).

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

یک نسخه از فایل صوتی را از ارائه‌ای دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | صوت منبع. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.

### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

یک صوت را از یک جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که صوت از آن اضافه می‌شود. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.

### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

یک صوت را از یک جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که صوت ویدئو از آن اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.

### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audioData | byte[] | بایت‌های صوت. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

صداها را به آرایه مشخص شده، شروع از اندیس تعیین‌شده، کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه. |
| index | int | اندیس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (امن از نظر چندنخی) است یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همزمان‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - یک IGenericEnumerator که می‌توان از آن برای پیمایش در مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - یک java.util.Iterator برای کل مجموعه.