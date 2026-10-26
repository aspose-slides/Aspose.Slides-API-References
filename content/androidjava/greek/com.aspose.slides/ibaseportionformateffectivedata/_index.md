---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /el/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Βασική διασύνδεση για αμετάβλητα αντικείμενα που περιέχουν αποτελεσματικές ιδιότητες μορφοποίησης τμήματος κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα του κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση ενός κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της υπογραμμισμένης γραμμής. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της υπογραμμισμένης γραμμής. |
| [getFontBold()](#getFontBold--) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για τα ανατολικά γλωσσικά κείμενα. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει εάν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει τον τύπο υπογράμμισης του κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει τον τύπο κεφαλαιοποίησης του κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει τον τύπο διαγράμμισης ενός κειμένου. |
| [getSmartTagClean()](#getSmartTagClean--) | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει εάν το στυλ υπογράμμισης διαθέτει δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει εάν το στυλ υπογράμμισης διαθέτει δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε σημεία. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει τις πληροφορίες γραμματοσειράς Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει τις πληροφορίες γραμματοσειράς East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει τις πληροφορίες γραμματοσειράς complex script. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει τις πληροφορίες γραμματοσειράς symbolic. |
| [getEscapement()](#getEscapement--) | Επιστρέφει κείμενο υπερ- ή υπο-συνδρομής. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί η σύγκλιση. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει το Id μιας γλώσσας. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει το Id μιας εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει το βήμα μεταξύ χαρακτήρων, σε σημεία. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα του κειμένου. Μόνο για ανάγνωση [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

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
public abstract Integer getHighlightColor()
```


Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση ενός κειμένου. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της υπογραμμισμένης γραμμής. Μόνο για ανάγνωση [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Επιστρέφει:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Επιστρέφει τις ιδιότητες FillFormat της υπογραμμισμένης γραμμής. Μόνο για ανάγνωση [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

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


Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για τα ανατολικά γλωσσικά κείμενα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Καθορίζει εάν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Επιστρέφει τον τύπο υπογράμμισης του κειμένου. Μόνο για ανάγνωση [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Επιστρέφει:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Επιστρέφει τον τύπο κεφαλαιοποίησης του κειμένου. Μόνο για ανάγνωση [TextCapType](../../com.aspose.slides/textcaptype).

**Επιστρέφει:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Επιστρέφει τον τύπο διαγράμμισης ενός κειμένου. Μόνο για ανάγνωση [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

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


Καθορίζει εάν το στυλ υπογράμμισης διαθέτει δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Καθορίζει εάν το στυλ υπογράμμισης διαθέτει δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Επιστρέφει το ύψος γραμματοσειράς του τμήματος κειμένου, σε σημεία. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Επιστρέφει τις πληροφορίες γραμματοσειράς Latin. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Επιστρέφει τις πληροφορίες γραμματοσειράς East Asian. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Επιστρέφει τις πληροφορίες γραμματοσειράς complex script. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Επιστρέφει τις πληροφορίες γραμματοσειράς symbolic. Μόνο για ανάγνωση [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Επιστρέφει κείμενο υπερ- ή υπο-συνδρομής. Τιμή από -100% (υποσέλιδο) έως 100% (υπερσέλιδο). Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Επιστρέφει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί η σύγκλιση. Μόνο για ανάγνωση float.

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


Επιστρέφει το Id μιας εναλλακτικής γλώσσας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Επιστρέφει το βήμα μεταξύ χαρακτήρων, σε σημεία. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float