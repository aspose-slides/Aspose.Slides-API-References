---
title: ICommandEffect
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل تأثير أمر لسلوك الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/icommandeffect/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

يمثل تأثير أمر لسلوك الرسوم المتحركة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحدد نوع تأثير الأمر للسلوك. |
| [setType(byte value)](#setType-byte-) | يحدد نوع تأثير الأمر للسلوك. |
| [getCommandString()](#getCommandString--) | يحدد سلسلة الأمر. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | يحدد سلسلة الأمر. |
| [getShapeTarget()](#getShapeTarget--) | يحدد هدف الشكل لتأثير الأمر. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | يحدد هدف الشكل لتأثير الأمر. |
### getType() {#getType--}
```
public abstract byte getType()
```


يحدد نوع تأثير الأمر للسلوك. قراءة/كتابة [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**الإرجاع:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


يحدد نوع تأثير الأمر للسلوك. قراءة/كتابة [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```


يحدد سلسلة الأمر. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```


يحدد سلسلة الأمر. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```


يحدد هدف الشكل لتأثير الأمر. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```


يحدد هدف الشكل لتأثير الأمر. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |