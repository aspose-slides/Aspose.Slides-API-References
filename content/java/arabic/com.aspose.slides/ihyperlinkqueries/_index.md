---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: توفر طريقة سهلة للوصول إلى الروابط الفائقة المضمنة.
type: docs
url: /ar/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

توفر طريقة سهلة للوصول إلى الروابط الفائقة المضمنة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkClick غير فارغ. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkMouseOver غير فارغ. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | يزيل جميع الروابط الفائقة HyperlinkClick وHyperlinkMouseOver المتضمنة (في جميع الكائنات الفرعية IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkClick غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط الفائق الخاص به (قراءة، تحديث أو حذف). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkMouseOver غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط الفائق الخاص به (قراءة، تحديث أو حذف). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

احصل على جميع الكائنات الفرعية IHyperlinkContainer التي تحتوي على HyperlinkMouseOver غير فارغ. مع كائن IHyperlinkContainer المعطى يمكنك إدارة الارتباط الفائق الخاص به (قراءة، تحديث أو حذف). راجع واجهة IHyperlinkContainer.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

يزيل جميع الروابط الفائقة HyperlinkClick وHyperlinkMouseOver المتضمنة (في جميع الكائنات الفرعية IHyperlinkContainer).