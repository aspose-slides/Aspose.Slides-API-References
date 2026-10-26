---
title: Behavior
second_title: Aspose.Slides للغة Java - مرجع API
description: يمثل سلوك الفئة الأساسية للتأثير.
type: docs
url: /ar/com.aspose.slides/behavior/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

يمثل سلوك الفئة الأساسية للتأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [getAdditive()](#getAdditive--) | يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسومات متحركة أخرى قيد التشغيل. |
| [setAdditive(int value)](#setAdditive-int-) | يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسومات متحركة أخرى قيد التشغيل. |
| [getProperties()](#getProperties--) | يمثل خصائص السلوك. |
| [getTiming()](#getTiming--) | يمثل خصائص التوقيت لسلوك التأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يمثل خصائص التوقيت لسلوك التأثير. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قابل للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسومات متحركة أخرى قيد التشغيل. قابل للقراءة والكتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**الإرجاع:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

يمثل ما إذا تم دمج سلوك الرسوم المتحركة الحالي مع رسومات متحركة أخرى قيد التشغيل. قابل للقراءة والكتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

يمثل خصائص السلوك. للقراءة فقط [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**الإرجاع:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

يمثل خصائص التوقيت لسلوك التأثير. قابل للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**الإرجاع:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

يمثل خصائص التوقيت لسلوك التأثير. قابل للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |