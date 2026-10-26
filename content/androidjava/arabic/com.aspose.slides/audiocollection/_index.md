---
title: AudioCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من ملفات الصوت المضمنة.
type: docs
url: /ar/com.aspose.slides/audiocollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)  
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

يمثل مجموعة من ملفات الصوت المضمنة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد ملفات الصوت في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | يضيف نسخة من ملف صوت من عرض تقديمي آخر. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ينشئ ويضيف ملف صوت إلى عرض تقديمي من تدفق. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ينشئ ويضيف ملف صوت إلى عرض تقديمي من تدفق. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | ينشئ ويضيف ملف صوت إلى عرض تقديمي من مصفوفة بايت. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ ملفات الصوت إلى المصفوفة المحددة بدءًا من الفهرس المحدد. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
| [iterator()](#iterator--) | يعيد مُعدادًا يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرر Java للمجموعة بالكامل. |

### size() {#size--}
```
public final int size()
```

يعيد عدد ملفات الصوت في المجموعة. قابل للقراءة فقط int.

**الإرجاع:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد. قابل للقراءة فقط [IAudio](../../com.aspose.slides/iaudio).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio)

### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

يضيف نسخة من ملف صوت من عرض تقديمي آخر.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | الصوت المصدر. |

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.

### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

ينشئ ويضيف ملف صوت إلى عرض تقديمي من تدفق.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة الصوت منه. |

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.

### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف ملف صوت إلى عرض تقديمي من تدفق.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق لإضافة الصوت من الفيديو. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على التدفق. |

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.

### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

ينشئ ويضيف ملف صوت إلى عرض تقديمي من مصفوفة بايت.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audioData | byte[] | بايتات الصوت. |

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio) - الصوت المضاف.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ ملفات الصوت إلى المصفوفة المحددة بدءًا من الفهرس المحدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة. |
| index | int | الفهرس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قابل للقراءة فقط boolean.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. قابل للقراءة فقط Object.

**الإرجاع:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

يعيد مُعدادًا يتجول عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - مُعداد IGenericEnumerator يمكن استخدامه للتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

يعيد مكرر Java للمجموعة بالكامل.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - مكرر java.util.Iterator للمجموعة بالكامل.