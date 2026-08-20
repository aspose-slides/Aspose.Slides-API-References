---
title: HyperlinkQueries
second_title: مرجع API لـ Aspose.Slides للغة Java
description: توفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.
type: docs
url: /ar/com.aspose.slides/hyperlinkqueries/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

توفر وصولًا سهلاً إلى الروابط التشعبية المحتواة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkClick غير فارغ. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | يزيل جميع الروابط التشعبية HyperlinkClick وHyperlinkMouseOver المحتواة (في جميع كائنات IHyperlinkContainer الفرعية). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkClick غير فارغ. باستخدام كائن IHyperlinkContainer المحدد يمكنك إدارة روابطه (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. باستخدام كائن IHyperlinkContainer المحدد يمكنك إدارة روابطه (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


احصل على جميع كائنات IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. باستخدام كائن IHyperlinkContainer المحدد يمكنك إدارة روابطه (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```


يزيل جميع الروابط التشعبية HyperlinkClick وHyperlinkMouseOver المحتواة (في جميع كائنات IHyperlinkContainer الفرعية).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


يرجع كائن Parent_Immediate. معرف IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject