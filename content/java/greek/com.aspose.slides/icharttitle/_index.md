---
title: IChartTitle
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά τις ιδιότητες του τίτλου διαγράμματος.
type: docs
url: /el/com.aspose.slides/icharttitle/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Αναπαριστά τις ιδιότητες του τίτλου διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOverlay()](#getOverlay--) | Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλυφούν τον τίτλο. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλυφούν τον τίτλο. |
| [getFormat()](#getFormat--) | Επιστρέφει τα στυλ γεμίσματος, γραμμής και εφέ ενός τίτλου. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλυφούν τον τίτλο. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλυφούν τον τίτλο. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τα στυλ γεμίσματος, γραμμής και εφέ ενός τίτλου. Μόνο ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)