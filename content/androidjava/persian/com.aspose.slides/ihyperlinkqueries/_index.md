---
title: IHyperlinkQueries
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: دسترسی آسان به Hyperlinkهای موجود را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

دسترسی آسان به Hyperlinkهای موجود را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | تمام زیر شیء‌های IHyperlinkContainer که HyperlinkClick غیر null هستند را دریافت می‌کند. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null هستند را دریافت می‌کند. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null هستند را دریافت می‌کند. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | تمام HyperlinkClick و HyperlinkMouseOver موجود در (همه زیر شیء‌های IHyperlinkContainer) را حذف می‌کند. |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

تمام زیر شیء‌های IHyperlinkContainer که HyperlinkClick غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer ارائه شده می‌توانید پیوند Hyperlink آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیر شیء‌های IHyperlinkContainer که HyperlinkClick غیر null هستند
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer ارائه شده می‌توانید پیوند Hyperlink آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null هستند
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null دارند را دریافت می‌کند. با شیء IHyperlinkContainer ارائه شده می‌توانید پیوند Hyperlink آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - تمام زیر شیء‌های IHyperlinkContainer که HyperlinkMouseOver غیر null هستند
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

تمام HyperlinkClick و HyperlinkMouseOver موجود در (همه زیر شیء‌های IHyperlinkContainer) را حذف می‌کند.