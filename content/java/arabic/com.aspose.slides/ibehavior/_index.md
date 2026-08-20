---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: يمثل سلوك الفئة الأساسية للتأثير.
type: docs
url: /ar/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

يمثل سلوك الفئة الأساسية للتأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. |
| [getAdditive()](#getAdditive--) | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. |
| [setAdditive(int value)](#setAdditive-int-) | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. |
| [getProperties()](#getProperties--) | يمثل خصائص السلوك. |
| [getTiming()](#getTiming--) | يمثل خصائص التوقيت لسلوك التأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يمثل خصائص التوقيت لسلوك التأثير. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```


يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```


يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```


يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. قراءة/كتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**القيمة المرجعة:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```


يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. قراءة/كتابة [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```


يمثل خصائص السلوك. قراءة فقط [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**القيمة المرجعة:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


يمثل خصائص التوقيت لسلوك التأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**القيمة المرجعة:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


يمثل خصائص التوقيت لسلوك التأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |