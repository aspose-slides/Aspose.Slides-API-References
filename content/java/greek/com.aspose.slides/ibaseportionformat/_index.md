---
title: IBasePortionFormat
second_title: Aspose.Slides for Java API Reference
description: Αυτή η κλάση περιλαμβάνει τις ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
url: /el/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Αυτή η κλάση περιλαμβάνει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την ανάκτηση και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λαμβάνετε τιμές που σημαίνουν «απροσδιόριστη».

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) που επιστρέφει ένα παράδειγμα [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της υπογράμμισης. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. |
| [getFontBold()](#getFontBold--) | Καθορίζει αν η γραμματοσειρά είναι έντονη. |
| [setFontBold(byte value)](#setFontBold-byte-) | Καθορίζει αν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει αν η γραμματοσειρά είναι πλάγια. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Καθορίζει αν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [setFontHeight(float value)](#setFontHeight-float-) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς Ανατολικής Ασίας. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς Ανατολικής Ασίας. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς σύνθετου script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς σύνθετου script. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [getEscapement()](#getEscapement--) | Επιστρέφει ή ορίζει το υπερ- ή υπο-γράψιμο κείμενο. |
| [setEscapement(float value)](#setEscapement-float-) | Επιστρέφει ή ορίζει το υπερ- ή υπο-γράψιμο κείμενο. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [setSpacing(float value)](#setSpacing-float-) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [getSpellCheck()](#getSpellCheck--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Καθορίζει αν οι αριθμοί πρέπει να αγνοούν την κατακόρυφη διάταξη κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Καθορίζει αν το ύψος ενός κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Επιστρέφει:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Επιστρέφει:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Επιστρέφει:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Καθορίζει αν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος είναι απροσδιόριστο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος είναι απροσδιόριστο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsian 
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Επιστρέφει ή ορίζει το υπερ- ή υπο-γράψιμο κείμενο. Τιμή από -100 % (υπόγραμμο) έως 100 % (υπέργραμμο). **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Επιστρέφει ή ορίζει το υπερ- ή υπο-γράψιμο κείμενο. Τιμή από -100 % (υπόγραμμο) έως 100 % (υπέργραμμο). **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου παραλείπονται. Όταν ορίζεται σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα στη πρώτη διαφάνεια
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Ενεργοποίηση ελέγχου ορθογραφίας για αυτό το τμήμα κειμένου
>      portion.getPortionFormat().setSpellCheck(true);
>      // Αποθήκευση της τροποποιημένης παρουσίασης
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου παραλείπονται. Όταν ορίζεται σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα στη πρώτη διαφάνεια
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Ενεργοποίηση ελέγχου ορθογραφίας για αυτό το τμήμα κειμένου
>      portion.getPortionFormat().setSpellCheck(true);
>      // Αποθήκευση της τροποποιημένης παρουσίασης
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |