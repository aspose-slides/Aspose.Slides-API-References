---
title: FontSubstRule
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά πληροφορίες αντικατάστασης γραμματοσειράς
type: docs
url: /el/com.aspose.slides/fontsubstrule/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Αναπαριστά πληροφορίες αντικατάστασης γραμματοσειράς
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Δημιουργεί νέα παρουσία. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Δημιουργεί νέα παρουσία. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Γραμματοσειρά προς αντικατάσταση. |
| [getDestFont()](#getDestFont--) | Γραμματοσειρά που θα χρησιμοποιηθεί για την αντικατάσταση. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Κανόνας που θα εφαρμοστεί για την αντικατάσταση. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Δημιουργεί νέα παρουσία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Πηγή γραμματοσειράς. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Προορισμός γραμματοσειράς. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Δημιουργεί νέα παρουσία.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Πηγή γραμματοσειράς. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Προορισμός γραμματοσειράς. |
| fontSubstRule | int | Κανόνας αντικατάστασης γραμματοσειράς. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Γραμματοσειρά προς αντικατάσταση. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Γραμματοσειρά που θα χρησιμοποιηθεί για την αντικατάσταση. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Κανόνας που θα εφαρμοστεί για την αντικατάσταση. Μόνο για ανάγνωση [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Επιστρέφει:**
int