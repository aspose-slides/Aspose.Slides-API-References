---
title: AudioCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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
| [size()](#size--) | يعطي عدد ملفات الصوت في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | يضيف نسخة من ملف صوت من عرض تقديمي آخر. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | إنشاء وإضافة صوت إلى عرض تقديمي من مصفوفة بايت. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ الأصوات إلى المصفوفة المحددة بدءًا من الفهرس المحدد. |
| [isSynchronized()](#isSynchronized--) | يعطي قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعطي جذر التزامن. |
| [iterator()](#iterator--) | يعطي عدادًا يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعطي مكرِّر Java للمجموعة بأكملها. |
### size() {#size--}
```
public final int size()
```

يعطي عدد ملفات الصوت في المجموعة. عدد صحيح للقراءة فقط.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد. للقراءة فقط [IAudio](../../com.aspose.slides/iaudio).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

يضيف نسخة من ملف صوت من عرض تقديمي آخر.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مصدر الصوت. |

**القيمة المرجعة:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة الصوت منه. |

**القيمة المرجعة:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من تدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق لإضافة الفيديو الصوت منه. |
| loadingStreamBehavior | int | السلوك الذي سيُطبق على التدفق. |

**القيمة المرجعة:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

ينشئ ويضيف صوتًا إلى عرض تقديمي من مصفوفة بايت.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| audioData | byte[] | بايتات الصوت. |

**القيمة المرجعة:**
[IAudio](../../com.aspose.slides/iaudio) - Added audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ الأصوات إلى المصفوفة المحددة بدءًا من الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة. |
| index | int | فهرس. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعطي قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قيمة منطقية للقراءة فقط.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعطي جذر التزامن. كائن للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

يعطي عدادًا يتكرر عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

يعطي مكرِّر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - An java.util.Iterator for the entire collection.