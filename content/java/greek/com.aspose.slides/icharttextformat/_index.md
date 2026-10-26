---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
url: /el/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Το Chart λειτουργεί με περιορισμένο σύνολο ιδιοτήτων μορφοποίησης κειμένου. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describe this restricted set.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Επιστρέφει τη μορφή για τα στοιχεία κειμένου του διαγράμματος. |
| [getParagraphFormat()](#getParagraphFormat--) | Επιστρέφει τη μορφή παραγράφου. |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει τη μορφή τμήματος. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Αντιγράφει τη μορφή κειμένου σε καθορισμένο πλαίσιο κειμένου. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Αντιγράφει τη μορφή κειμένου από καθορισμένο πλαίσιο κειμένου. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Επιστρέφει τη μορφή για τα στοιχεία κειμένου του διαγράμματος. Μόνο για ανάγνωση [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

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


Αντιγράφει τη μορφή κειμένου σε καθορισμένο πλαίσιο κειμένου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Πλαίσιο κειμένου για αντιγραφή της μορφής κειμένου. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Αντιγράφει τη μορφή κειμένου από καθορισμένο πλαίσιο κειμένου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Πλαίσιο κειμένου για αντιγραφή της μορφής κειμένου. |