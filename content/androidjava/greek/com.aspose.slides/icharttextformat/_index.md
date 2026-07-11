---
title: IChartTextFormat
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Το Chart λειτουργεί με περιορισμένο σύνολο ιδιοτήτων μορφοποίησης κειμένου.
type: docs
url: /el/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Το Chart λειτουργεί με περιορισμένο σύνολο ιδιοτήτων μορφοποίησης κειμένου. Οι διεπαφές IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat περιγράφουν αυτό το περιορισμένο σύνολο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Επιστρέφει τη μορφή για τα στοιχεία κειμένου του chart. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει τη μορφή παραγράφου. |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει τη μορφή τμήματος. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Αντιγράφει τη μορφή κειμένου στο καθορισμένο πλαίσιο κειμένου. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Αντιγράφει τη μορφή κειμένου από το καθορισμένο πλαίσιο κειμένου. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Επιστρέφει τη μορφή για τα στοιχεία κειμένου του chart. Μόνο για ανάγνωση [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Επιστρέφει:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Επιστρέφει τη μορφή παραγράφου. Μόνο για ανάγνωση [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Επιστρέφει:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Επιστρέφει τη μορφή τμήματος. Μόνο για ανάγνωση [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Επιστρέφει:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Αντιγράφει τη μορφή κειμένου στο καθορισμένο πλαίσιο κειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Πλαίσιο κειμένου στο οποίο θα αντιγραφεί η μορφή κειμένου. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Αντιγράφει τη μορφή κειμένου από το καθορισμένο πλαίσιο κειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Πλαίσιο κειμένου από το οποίο θα αντιγραφεί η μορφή κειμένου. |