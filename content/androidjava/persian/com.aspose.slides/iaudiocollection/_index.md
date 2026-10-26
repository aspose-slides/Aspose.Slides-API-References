---
title: IAudioCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از فایل‌های صوتی توکار.
type: docs
url: /fa/com.aspose.slides/iaudiocollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

نمایش‌دهندهٔ مجموعه‌ای از فایل‌های صوتی توکار.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را در اندیس مشخص‌شده دریافت می‌کند. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | کپی‌ای از یک فایل صوتی را از یک ارائه دیگر اضافه می‌کند. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

عنصری را در اندیس مشخص‌شده دریافت می‌کند. فقط-خواندنی [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

کپی‌ای از یک فایل صوتی را از یک ارائه دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | صوت منبع. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه‌کردن صوت. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

یک صوت را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه‌کردن صوت ویدیو. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) که بر روی جریان اعمال خواهد شد. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

یک صوت را از آرایه بایت ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audioData | byte[] | بایت‌های صوت. |

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio) - صوت اضافه‌شده.