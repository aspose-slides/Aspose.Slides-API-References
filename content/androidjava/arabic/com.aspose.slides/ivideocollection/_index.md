---
title: IVideoCollection
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل مجموعة من كائنات Video.
type: docs
url: /ar/com.aspose.slides/ivideocollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

يمثل مجموعة من كائنات Video.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يسترجع العنصر في الفهرس المحدد. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | يضيف نسخة من ملف فيديو من عرض تقديمي آخر. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ينشئ ويضيف فيديو إلى عرض تقديمي من تدفق. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

يسترجع العنصر في الفهرس المحدد. للقراءة فقط [IVideo](../../com.aspose.slides/ivideo).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

يضيف نسخة من ملف فيديو من عرض تقديمي آخر.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | فيديو المصدر. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة الفيديو.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف فيديو إلى عرض تقديمي من تدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة ملف الفيديو منه. |
| loadingStreamBehavior | int | السلوك الذي سيطبق على التدفق. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| videoData | byte[] | بايتات الفيديو. |

**القيمة المرجعة:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة الفيديو.