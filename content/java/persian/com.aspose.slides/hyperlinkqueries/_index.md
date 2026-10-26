---
title: HyperlinkQueries
second_title: مرجع API Aspose.Slides برای جاوا
description: دسترسی آسان به لینک‌های موجود را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/hyperlinkqueries/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

دسترسی آسان به لینک‌های داخلی را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkClick تهی نیستند. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkMouseOver تهی نیستند. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkMouseOver تهی نیستند. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | حذف تمام HyperlinkClick و HyperlinkMouseOverهای موجود (در تمام زیرشیءهای IHyperlinkContainer). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkClick تهی نیستند. با استفاده از شیء IHyperlinkContainer داده‌شده می‌توانید پیوند (hyperlink) آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). برای جزئیات به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkMouseOver تهی نیستند. با استفاده از شیء IHyperlinkContainer داده‌شده می‌توانید پیوند (hyperlink) آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). برای جزئیات به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

دریافت تمام زیرشیءهای IHyperlinkContainer که HyperlinkMouseOver تهی نیستند. با استفاده از شیء IHyperlinkContainer داده‌شده می‌توانید پیوند (hyperlink) آن را مدیریت کنید (خواندن، به‌روزرسانی یا حذف). برای جزئیات به رابط IHyperlinkContainer مراجعه کنید.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

حذف تمام HyperlinkClick و HyperlinkMouseOverهای موجود (در تمام زیرشیءهای IHyperlinkContainer).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بازمی‌گرداند. فقط خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject