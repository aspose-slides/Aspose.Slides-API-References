---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java Αναφορά API
description: Διεπαφή βάσης για αμετάβλητα αντικείμενα που περιέχουν τις αποτελεσματικές ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
url: /el/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Διεπαφή βάσης για αμετάβλητα αντικείμενα που περιέχουν τις αποτελεσματικές ιδιότητες μορφοποίησης τμημάτων κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για την περιγράµαση κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για την περιγράµαση της γραμμής υπογράμμισης. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. |
| [getFontBold()](#getFontBold--) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για τις ανατολικές γλώσσες. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει εάν το κείμενο δεν πρέπει να υποβληθεί σε ορθογραφικό έλεγχο. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει τον τύπο υπογράμμισης κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει τον τύπο κεφαλαιοποίησης κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει τον τύπο διαγράμμισης κειμένου. |
| [getSmartTagClean()](#getSmartTagClean--) | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε μονάδες σημείου. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει τις πληροφορίες της λατινικής γραμματοσειράς. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει τις πληροφορίες της ασιατικής ανατολικής γραμματοσειράς. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [getEscapement()](#getEscapement--) | Επιστρέφει το ανώτερον ή κατώτερο εκθέτη κειμένου. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η εσοχή χαρακτήρων. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει το Id μιας γλώσσας. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει το Id εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει το βήμα διαστήματος μεταξύ χαρακτήρων, σε μονάδες σημείου. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat για την περιγράµαση κειμένου. Μόνο για ανάγνωση [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Επιστρέφει:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Μόνο για ανάγνωση [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Επιστρέφει:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για την περιγράµαση της γραμμής υπογράμμισης. Μόνο για ανάγνωση [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Επιστρέφει:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Μόνο για ανάγνωση [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Επιστρέφει:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Καθορίζει εάν η γραμματοσειρά είναι έντονη. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για τις ανατολικές γλώσσες. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Καθορίζει εάν το κείμενο δεν πρέπει να υποβληθεί σε ορθογραφικό έλεγχο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Επιστρέφει τον τύπο υπογράμμισης κειμένου. Μόνο για ανάγνωση [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Επιστρέφει:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Επιστρέφει τον τύπο κεφαλαιοποίησης κειμένου. Μόνο για ανάγνωση [TextCapType](../../com.aspose.slides/textcaptype).

**Επιστρέφει:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Επιστρέφει τον τύπο διαγράμμισης κειμένου. Μόνο για ανάγνωση [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Επιστρέφει:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε μονάδες σημείου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Επιστρέφει τις πληροφορίες της λατινικής γραμματοσειράς. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Επιστρέφει τις πληροφορίες της ασιατικής ανατολικής γραμματοσειράς. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Επιστρέφει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Επιστρέφει τις πληροφορίες της συμβολικής γραμματοσειράς. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Επιστρέφει το ανώτερον ή κατώτερο εκθέτη κειμένου. Τιμή από -100% (κατώτερο) έως 100% (ανώτερον). Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς, για το οποίο πρέπει να ενεργοποιηθεί η εσοχή χαρακτήρων. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Επιστρέφει το Id μιας γλώσσας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Επιστρέφει το Id εναλλακτικής γλώσσας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Επιστρέφει το βήμα διαστήματος μεταξύ χαρακτήρων, σε μονάδες σημείου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float