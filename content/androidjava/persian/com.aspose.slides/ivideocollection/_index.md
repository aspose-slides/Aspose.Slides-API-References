---
title: IVideoCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از اشیاء Video.
type: docs
url: /fa/com.aspose.slides/ivideocollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

نمایش‌دهندهٔ مجموعه‌ای از اشیاء Video.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص دریافت می‌کند. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | یک کپی از فایل ویدئویی را از ارائه‌ای دیگر اضافه می‌کند. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | یک ویدئو را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | یک ویدئو را از آرایه بایت ایجاد و به ارائه اضافه می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


عنصر را در ایندکس مشخص دریافت می‌کند. فقط‌خواندنی [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


یک کپی از فایل ویدئویی را از ارائه‌ای دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدئوی منبع. |

**بازگشت:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه‌شده.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


یک ویدئو را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که فایل ویدئو از آن اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**بازگشت:**
[IVideo](../../com.aspose.slides/ivideo) - اضافه‌شده [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


یک ویدئو را از آرایه بایت ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | byte[] | بایت‌های ویدئو. |

**بازگشت:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه‌شده.