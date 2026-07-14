---
title: Behavior
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [getAdditive()](#getAdditive--) | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. |
| [setAdditive(int value)](#setAdditive-int-) | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. |
| [getProperties()](#getProperties--) | يمثل خصائص السلوك. |
| [getTiming()](#getTiming--) | يمثل خصائص التوقيت لسلوك التأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يمثل خصائص التوقيت لسلوك التأثير. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. قراءة/كتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**الإرجاع:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. قراءة/كتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**المعلمات:**
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


يمثل خصائص التوقيت لسلوك التأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**الإرجاع:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


يمثل خصائص التوقيت لسلوك التأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |