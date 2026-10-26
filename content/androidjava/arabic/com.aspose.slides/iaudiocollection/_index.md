---
title: IAudioCollection
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل مجموعة من ملفات الصوت المضمنة.
type: docs
url: /ar/com.aspose.slides/iaudiocollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

يمثل مجموعة من ملفات الصوت المضمنة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | يضيف نسخة من ملف صوت من عرض تقديمي آخر. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ينشئ ويضيف ملف صوت إلى العرض التقديمي من الدفق. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ينشئ ويضيف ملف صوت إلى العرض التقديمي من الدفق. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | ينشئ ويضيف ملف صوت إلى العرض التقديمي من مصفوفة بايت. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

ي يحصل على العنصر في الفهرس المحدد. قراءة فقط [IAudio](../../com.aspose.slides/iaudio).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

يضيف نسخة من ملف صوت من عرض تقديمي آخر.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مصدر الصوت. |

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

ينشئ ويضيف ملف صوت إلى العرض التقديمي من الدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لإضافة الصوت منه. |

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف ملف صوت إلى العرض التقديمي من الدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لإضافة الفيديو الصوتي منه. |
| loadingStreamBehavior | int | ال[LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) الذي سيتم تطبيقه على الدفق. |

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

ينشئ ويضيف ملف صوت إلى العرض التقديمي من مصفوفة بايت.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audioData | byte[] | بايتات الصوت. |

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.