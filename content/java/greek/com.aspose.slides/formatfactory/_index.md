---
title: FormatFactory
second_title: Αναφορά API του Aspose.Slides για Java
description: Επιτρέπει τη δημιουργία μορφών μέσω διεπαφής COM.
type: docs
url: /el/com.aspose.slides/formatfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Επιτρέπει τη δημιουργία μορφών μέσω COM διεπαφής.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInstance()](#getInstance--) | Στατική παρουσία του εργοστασίου μορφής. |
| [createPortionFormat()](#createPortionFormat--) | Δημιουργεί νέο [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Δημιουργεί νέο [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Δημιουργεί νέο [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Στατική παρουσία του εργοστασίου μορφής. Μόνο για ανάγνωση [FormatFactory](../../com.aspose.slides/formatfactory).

**Επιστρέφει:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Δημιουργεί νέο [IPortionFormat](../../com.aspose.slides/iportionformat).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Νέα μορφή τμήματος.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

Δημιουργεί νέο [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Επιστρέφει:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Νέα μορφή παραγράφου.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

Δημιουργεί νέο [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Επιστρέφει:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Νέα μορφή πλαισίου κειμένου.