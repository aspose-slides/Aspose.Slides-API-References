---
title: IVideoCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة من كائنات Video.
type: docs
url: /ar/com.aspose.slides/ivideocollection/
---
**جميع الواجهات المطبقة:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

يمثل مجموعة من كائنات Video.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | يضيف نسخة من ملف video من عرض تقديمي آخر. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ينشئ ويضيف فيديو إلى عرض تقديمي من stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IVideo](../../com.aspose.slides/ivideo).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

يضيف نسخة من ملف video من عرض تقديمي آخر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | فيديو المصدر. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف فيديو إلى عرض تقديمي من stream.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق لإضافة ملف الفيديو منه. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على الدفق. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| videoData | byte[] | بايتات الفيديو. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة video.