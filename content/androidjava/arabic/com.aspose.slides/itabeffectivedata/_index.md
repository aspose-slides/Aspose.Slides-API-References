---
title: ITabEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: كائن غير قابل للتغيير يحتوي على خصائص توقف الجدولة للنصوص الفعالة.
type: docs
url: /ar/com.aspose.slides/itabeffectivedata/
---
**جميع الواجهات المنفذة:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

كائن غير قابل للتغيير يحتوي على خصائص توقف الجدولة للنص الفعلي.

--------------------

تُستخدم هذه الواجهة كجزء من [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getPosition()](#getPosition--) | يعيد موقع علامة تبويب. |
| [getAlignment()](#getAlignment--) | يعيد نمط محاذاة علامة تبويب. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


يعيد موقع علامة تبويب. يمكن أن يؤدي تعيين هذه الخاصية إلى تغيير فهرس علامة التبويب في المجموعة وإبطال المُعدِّد. عدد مزدوج للقراءة فقط.

**القيمة المرجعة:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


يعيد نمط محاذاة علامة تبويب. للقراءة فقط [TabAlignment](../../com.aspose.slides/tabalignment).

**القيمة المرجعة:**
int