---
title: ITabEffectiveData
second_title: Aspose.Slides لمرجع API لجافا
description: كائن غير قابل للتغيير يحتوي على خصائص نقاط توقف جدولة النصوص الفعّالة.
type: docs
url: /ar/com.aspose.slides/itabeffectivedata/
---
**جميع الواجهات المنفذة:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

كائن غير قابل للتغيير يحتوي على خصائص نقاط التوقف للجدولة للنص الفعّال.

--------------------

هذه الواجهة تُستخدم كجزء من [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPosition()](#getPosition--) | يعيد موضع علامة تبويب. |
| [getAlignment()](#getAlignment--) | يعيد نمط محاذاة علامة تبويب. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

يعيد موضع علامة تبويب. تعيين هذه الخاصية يمكن أن يغيّر فهرس علامة التبويب في المجموعة ويُلغي صحة Enumerator. قراءة فقط double.

**الإرجاع:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

يعيد نمط محاذاة علامة تبويب. قراءة فقط [TabAlignment](../../com.aspose.slides/tabalignment).

**الإرجاع:**
int