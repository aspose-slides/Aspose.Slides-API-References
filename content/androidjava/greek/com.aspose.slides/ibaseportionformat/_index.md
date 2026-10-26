---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
url: /el/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμημάτων κειμένου. Σε αντίθεση με [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι επεξεργάσιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμημάτων κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, οπότε στις περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν «απροσδιόριστο».

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) που επιστρέφει ένα παράδειγμα [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. |
| [getFontBold()](#getFontBold--) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [setFontBold(byte value)](#setFontBold-byte-) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την ανατολική διάταξη κατακόρυφου κειμένου. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την ανατολική διάταξη κατακόρυφου κειμένου. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης του κειμένου. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης του κειμένου. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [setFontHeight(float value)](#setFontHeight-float-) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της λατινικής γραμματοσειράς. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της ασιατικής γραμματοσειράς. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της ασιατικής γραμματοσειράς. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της πολυσύνθετης γραμματοσειράς. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της πολυσύνθετης γραμματοσειράς. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [getEscapement()](#getEscapement--) | Επιστρέφει ή ορίζει το ανώτερο ή κατώτερο κείμενο. |
| [setEscapement(float value)](#setEscapement-float-) | Επιστρέφει ή ορίζει το ανώτερο ή κατώτερο κείμενο. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει ή ορίζει το Id γλώσσας ελέγχου. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id γλώσσας ελέγχου. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει ή ορίζει το Id εναλλακτικής γλώσσας. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [setSpacing(float value)](#setSpacing-float-) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [getSpellCheck()](#getSpellCheck--) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Επιστρέφει το χρώμα που χρησιμοποιείται για επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για περίγραμμα της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την ανατολική διάταξη κατακόρυφου κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Καθορίζει εάν οι αριθμοί πρέπει να αγνοούν την ανατολική διάταξη κατακόρυφου κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Καθορίζει εάν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

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

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Επιστρέφει:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Καθορίζει εάν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

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

Επιστρέφει ή ορίζει τις πληροφορίες της ασιατικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της ασιατικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της πολυσύνθετης γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της πολυσύνθετης γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετορι:**
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

Επιστρέφει ή ορίζει το ανώτερο ή κατώτερο κείμενο. Τιμή από -100% (κατώτερο) έως 100% (ανώτερο). **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Επιστρέφει ή ορίζει το ανώτερο ή κατώτερο κείμενο. Τιμή από -100% (κατώτερο) έως 100% (ανώτερο). **Float.NaN** σημαίνει ότι η τιμή είναι απροσδιόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/εγγραφή float.

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

Επιστρέφει ή ορίζει το Id γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Επιστρέφει ή ορίζει το Id εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

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

Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, ο ορθογραφικός έλεγχος επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
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

Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν είναι ενεργοποιημένος ο ορθογραφικός έλεγχος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για τα στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, ο ορθογραφικός έλεγχος επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |