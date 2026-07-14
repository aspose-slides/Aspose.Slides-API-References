---
title: IHyperlinkQueries
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: توفر وصولًا سهلًا إلى الارتباطات التشعبية المتضمنة.
type: docs
url: /ar/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

توفر وصولًا سهلًا إلى الارتباطات التشعبية المتضمنة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkClick غير فارغ. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | يزيل جميع HyperlinkClick و HyperlinkMouseOver الموجودة (في جميع IHyperlinkContainer الفرعية). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkClick غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkClick غير فارغ
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

احصل على جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط التشعبي الخاص به (قراءة، تحديث أو إزالة). راجع واجهة IHyperlinkContainer.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - جميع IHyperlinkContainer الفرعية التي تحتوي على HyperlinkMouseOver غير فارغ
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

يقوم بإزالة جميع HyperlinkClick و HyperlinkMouseOver الموجودة (في جميع IHyperlinkContainer الفرعية).