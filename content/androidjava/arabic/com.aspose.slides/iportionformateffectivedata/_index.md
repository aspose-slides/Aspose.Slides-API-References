---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق جزء النص الفعال.
type: docs
url: /ar/com.aspose.slides/iportionformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق جزء النص الفعال.

--------------------

تُستخدم هذه الواجهة مع واجهة [IPortionFormat](../../com.aspose.slides/iportionformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | إرجاع معرف العلامة المرجعية. |
| [getHyperlinkClick()](#getHyperlinkClick--) | إرجاع الارتباط التشعبي المحدد للنقر بالماوس. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | إرجاع الارتباط التشعبي المحدد للتحويم بالفأرة. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


إرجاع معرف العلامة المرجعية. للقراءة فقط String.

**الإرجاع:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


إرجاع الارتباط التشعبي المحدد للنقر بالماوس. للقراءة فقط [IHyperlink](../../com.aspose.slides/ihyperlink).

**الإرجاع:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


إرجاع الارتباط التشعبي المحدد للتحويم بالفأرة. للقراءة فقط [IHyperlink](../../com.aspose.slides/ihyperlink).

**الإرجاع:**
[IHyperlink](../../com.aspose.slides/ihyperlink)