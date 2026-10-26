---
title: IPortionFormat
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/iportionformat/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

تحتوي هذه الفئة على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحددة للجزء المعين. يعني هذا أنه لا يُطبق وراثة عند جلب القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير مُعرّفة".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الوراثة، تحتاج إلى استخدام طريقة [getEffective](../../com.aspose.slides/iportionformat\#getEffective) التي تُعيد مثالًا من [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | يعيد أو يعيّن معرّف الإشارة المرجعية. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | يعيد أو يعيّن معرّف الإشارة المرجعية. |
| [getSmartTagClean()](#getSmartTagClean--) | يحدد ما إذا كان ينبغي تنظيف العلامة الذكية. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | يحدد ما إذا كان ينبغي تنظيف العلامة الذكية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الجزء الفعّال مع تطبيق الوراثة. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

يعيد أو يعيّن معرّف الإشارة المرجعية. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

يعيد أو يعيّن معرّف الإشارة المرجعية. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

يحدد ما إذا كان ينبغي تنظيف العلامة الذكية. لا تُطبق وراثة. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

يحدد ما إذا كان ينبغي تنظيف العلامة الذكية. لا تُطبق وراثة. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الجزء الفعّال مع تطبيق الوراثة.

**الإرجاع:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).