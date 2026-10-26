---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: يحدد حجم منطقة الشريحة (العرض عندما يكون عنصرًا تابعًا لـ restoredTop والارتفاع عندما يكون عنصرًا تابعًا لـ restoredLeft) في العرض العادي عندما تكون المنطقة ذات حجم مستعاد متغيّر (لا تكون مصغرة ولا موسعة).
type: docs
url: /ar/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

يحدد حجم منطقة الشريحة ((العرض عندما يكون عنصرًا تابعًا لـ restoredTop، الارتفاع عندما يكون عنصرًا تابعًا لـ restoredLeft) في العرض العادي، عندما تكون المنطقة ذات حجم مستعاد متغيّر (لا تكون مصغرة ولا موسعة)).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | يحدد حجم منطقة الشريحة (العرض عندما يكون عنصرًا تابعًا لـ RestoredTop، الارتفاع عندما يكون عنصرًا تابعًا لـ RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | يحدد حجم منطقة الشريحة (العرض عندما يكون عنصرًا تابعًا لـ RestoredTop، الارتفاع عندما يكون عنصرًا تابعًا لـ RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | يحدد ما إذا كان يجب أن تعوّض منطقة المحتوى الجانبية عن الحجم الجديد عند تغيير حجم النافذة التي تحتوي على العرض داخل التطبيق. قراءة/كتابة boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | يحدد ما إذا كان يجب أن تعوّض منطقة المحتوى الجانبية عن الحجم الجديد عند تغيير حجم النافذة التي تحتوي على العرض داخل التطبيق. قراءة/كتابة boolean. |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

يحدد حجم منطقة الشريحة (العرض عندما يكون عنصرًا تابعًا لـ RestoredTop، الارتفاع عندما يكون عنصرًا تابعًا لـ RestoredLeft). قراءة/كتابة float.

**الإرجاع:**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

يحدد حجم منطقة الشريحة (العرض عندما يكون عنصرًا تابعًا لـ RestoredTop، الارتفاع عندما يكون عنصرًا تابعًا لـ RestoredLeft). قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

يحدد ما إذا كان يجب أن تعوّض منطقة المحتوى الجانبية عن الحجم الجديد عند تغيير حجم النافذة التي تحتوي على العرض داخل التطبيق. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

يحدد ما إذا كان يجب أن تعوّض منطقة المحتوى الجانبية عن الحجم الجديد عند تغيير حجم النافذة التي تحتوي على العرض داخل التطبيق. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |