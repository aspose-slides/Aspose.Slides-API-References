---
title: VideoCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌گر مجموعه‌ای از اشیاء Video است.
type: docs
url: /fa/com.aspose.slides/videocollection/
---
**ارث-بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

نمایش‌گر مجموعه‌ای از اشیاء Video است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد فایل‌های ویدئویی در مجموعه را باز می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص شده دریافت می‌کند. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | یک نسخه از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ویدئویی را از جریان ایجاد و به یک ارائه اضافه می‌کند. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ویدئوت‌ها را به آرایه مشخص شده از ایندکس داده شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را باز می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امنیت در برابر نخ) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشه همگام‌سازی را باز می‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه مرور می‌کند را باز می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را باز می‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد فایل‌های ویدئویی در مجموعه را باز می‌گرداند. فقط خواندنی int.

**باز می‌گردد:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


عنصر را در ایندکس مشخص شده دریافت می‌کند. فقط خواندنی [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گردد:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


یک نسخه از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدئوی منبع. |

**باز می‌گردد:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه شده.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


ویدئویی را از جریان ایجاد و به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که فایل ویدئویی از آن اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**باز می‌گردد:**
[IVideo](../../com.aspose.slides/ivideo) - [IVideo](../../com.aspose.slides/ivideo) اضافه شد.
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


ویدئویی را از آرایه بایت ایجاد و به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | byte[] | بایت‌های ویدئو. |

**باز می‌گردد:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه شده.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


ویدئوت‌ها را به آرایه مشخص شده از ایندکس داده شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه. |
| index | int | ایندکس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را باز می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امنیت در برابر نخ) است. فقط خواندنی boolean.

**باز می‌گردد:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشه‌ای برای همگام‌سازی را باز می‌گرداند. فقط خواندنی Object.

**باز می‌گردد:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


یک شمارنده که از طریق مجموعه مرور می‌کند را باز می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - یک IGenericEnumerator که می‌تواند برای مرور مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


یک iterator جاوا برای کل مجموعه را باز می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - یک java.util.Iterator برای کل مجموعه.