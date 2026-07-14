---
title: VideoCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مجموعة من كائنات Video.
type: docs
url: /ar/com.aspose.slides/videocollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

يمثل مجموعة من كائنات Video.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يرجع عدد ملفات الفيديو في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | يضيف نسخة من ملف فيديو من عرض تقديمي آخر. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | ينشئ ويضيف فيديو إلى عرض تقديمي من تدفق. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ الفيديوهات إلى المصفوفة المحددة بدءًا من الفهرس المحدد. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرر java للمجموعة بأكملها. |
### size() {#size--}
```
public final int size()
```


يرجع عدد ملفات الفيديو في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد. [IVideo](../../com.aspose.slides/ivideo) للقراءة فقط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


يضيف نسخة من ملف فيديو من عرض تقديمي آخر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | فيديو المصدر. |

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo) - الفيديو المضاف.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


ينشئ ويضيف فيديو إلى عرض تقديمي من تدفق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة ملف الفيديو منه. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على التدفق. |

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo) - تم إضافة [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| videoData | byte[] | بايتات الفيديو. |

**الإرجاع:**
[IVideo](../../com.aspose.slides/ivideo) - الفيديو المضاف.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


ينسخ الفيديوهات إلى المصفوفة المحددة بدءًا من الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة. |
| index | int | فهرس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). منطقي للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


يرجع جذر المزامنة. كائن للقراءة فقط.

**الإرجاع:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


يرجع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


يرجع مكرر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator للمجموعة بأكملها.