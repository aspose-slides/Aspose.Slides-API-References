---
title: VideoCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از اشیاء Video است.
type: docs
url: /fa/com.aspose.slides/videocollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

نمایانگر مجموعه‌ای از اشیاء Video است.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد فایل‌های ویدئویی در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | یک نسخه از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | یک ویدئوی جدید ایجاد و از جریان به ارائه اضافه می‌کند. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | یک ویدئوی جدید ایجاد و از آرایه بایت به ارائه اضافه می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ویدئوها را به آرایه مشخص شده از ایندکس داده‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌رشته). |
| [getSyncRoot()](#getSyncRoot--) | ریشه همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که مجموعه را پیمایش می‌کند برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد فایل‌های ویدئویی در مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

عنصر را در ایندکس مشخص‌شده دریافت می‌کند. فقط خواندنی [IVideo](../../com.aspose.slides/ivideo).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
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

**بازگشت:**  
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه‌شده.

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

یک ویدئوی جدید ایجاد و از جریان به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریانی که فایل ویدئوی از آن اضافه می‌شود. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**بازگشت:**  
[IVideo](../../com.aspose.slides/ivideo) - اضافه‌شده [IVideo](../../com.aspose.slides/ivideo).

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

یک ویدئوی جدید ایجاد و از آرایه بایت به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | byte[] | بایت‌های ویدئو. |

**بازگشت:**  
[IVideo](../../com.aspose.slides/ivideo) - ویدئوی اضافه‌شده.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ویدئوها را به آرایه مشخص شده از ایندکس داده‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه. |
| index | int | ایندکس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

یک مقدار برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌رشته). فقط خواندنی boolean.

**بازگشت:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

یک enumerator که مجموعه را پیمایش می‌کند برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - یک java.util.Iterator برای کل مجموعه.