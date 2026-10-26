---
title: IHyperlinkQueries
second_title: Aspose.Slides برای Java مرجع API
description: دسترسی آسان به پیوندهای موجود را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

دسترس آسان به پیوندهای موجود را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | تمام زیرشیء‌های IHyperlinkContainer که HyperlinkClick غیر null دارند را دریافت می‌کند. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | تمام پیوندهای HyperlinkClick و HyperlinkMouseOver موجود را در همه زیرشیء‌های IHyperlinkContainer حذف می‌کند. |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

تمام زیرشیء‌های IHyperlinkContainer که HyperlinkClick غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer داده‌شده می‌توانید پیوند آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیرشیء‌های IHyperlinkContainer که HyperlinkClick غیر null دارند
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer داده‌شده می‌توانید پیوند آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer داده‌شده می‌توانید پیوند آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیرشیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

تمام پیوندهای HyperlinkClick و HyperlinkMouseOver موجود را در همه زیرشیء‌های IHyperlinkContainer حذف می‌کند.