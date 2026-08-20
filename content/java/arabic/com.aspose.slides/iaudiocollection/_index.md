---
title: IAudioCollection
second_title: مرجع API ل Aspose.Slides للغة Java
description: يمثل مجموعة من ملفات الصوت المضمنة.
type: docs
url: /ar/com.aspose.slides/iaudiocollection/
---
**كل الواجهات التي تم تنفيذها:**
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
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ينشئ ويضيف صوتًا إلى عرض تقديمي من الدفق. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ينشئ ويضيف صوتًا إلى عرض تقديمي من الدفق. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | ينشئ ويضيف صوتًا إلى عرض تقديمي من مصفوفة بايت. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيم المرتجعة:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

يضيف نسخة من ملف صوت من عرض تقديمي آخر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | الصوت المصدر. |

**القيم المرتجعة:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من الدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لإضافة الصوت منه. |

**القيم المرتجعة:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من الدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | الدفق لإضافة فيديو الصوت منه. |
| loadingStreamBehavior | int | الـ [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) الذي سيتم تطبيقه على الدفق. |

**القيم المرتجعة:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من مصفوفة بايت.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audioData | byte[] | بايتات الصوت. |

**القيم المرتجعة:**
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.