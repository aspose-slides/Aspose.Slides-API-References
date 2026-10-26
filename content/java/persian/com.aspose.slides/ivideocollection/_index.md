---
title: IVideoCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک مجموعه از اشیاء Video است.
type: docs
url: /fa/com.aspose.slides/ivideocollection/
---
**همه رابط‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

نمایانگر مجموعه‌ای از اشیاء Video است.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر در ایندکس مشخص شده را دریافت می‌کند. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | یک کپی از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | یک ویدئو را از جریان ساخته و به ارائه اضافه می‌کند. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | یک ویدئو را از آرایه بایت ساخته و به ارائه اضافه می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

عنصر در ایندکس مشخص شده را دریافت می‌کند. فقط خواندنی [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

یک کپی از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدئوی منبع. |

**بازگرداندن:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئو اضافه شد.

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

یک ویدئو را از جریان ساخته و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که از آن فایل ویدئو اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**بازگرداندن:**
[IVideo](../../com.aspose.slides/ivideo) - اضافه شده [IVideo](../../com.aspose.slides/ivideo).

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

یک ویدئو را از آرایه بایت ساخته و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | byte[] | بایت‌های ویدئو. |

**بازگرداندن:**
[IVideo](../../com.aspose.slides/ivideo) - ویدئو اضافه شد.