---
title: BasePortionFormat
second_title: Aspose.Slides για Android μέσω Java αναφορά API
description: Κοινές ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
url: /el/com.aspose.slides/baseportionformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Κοινές ιδιότητες μορφοποίησης τμήματος κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για την περιγράμμιση του κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για την περιγράμμιση της υπογράμμισης. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. |
| [getFontBold()](#getFontBold--) | Καθορίζει αν η γραμματοσειρά είναι έντονη. |
| [setFontBold(byte value)](#setFontBold-byte-) | Καθορίζει αν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει αν η γραμματοσειρά είναι πλάγια. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Καθορίζει αν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη διάταξη κάθετου κειμένου ειδική για ανατολικές γλώσσες. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη διάταξη κάθετου κειμένου ειδική για ανατολικές γλώσσες. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [setFontHeight(float value)](#setFontHeight-float-) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της Λατινικής γραμματοσειράς. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της Λατινικής γραμματοσειράς. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της Ανατολικής Ασιατικής γραμματοσειράς. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της Ανατολικής Ασιατικής γραμματοσειράς. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. |
| [getEscapement()](#getEscapement--) | Επιστρέφει ή ορίζει το κείμενο σε υπέργραμμο ή υπογραμμο. |
| [setEscapement(float value)](#setEscapement-float-) | Επιστρέφει ή ορίζει το κείμενο σε υπέργραμμο ή υπογραμμο. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [setSpacing(float value)](#setSpacing-float-) | Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. |
| [getSpellCheck()](#getSpellCheck--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat για την περιγράμμιση του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για την περιγράμμιση της υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat της γραμμής υπογράμμισης. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Καθορίζει αν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Καθορίζει αν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη διάταξη κάθετου κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Καθορίζει αν οι αριθμοί πρέπει να αγνοούν τη διάταξη κάθετου κειμένου ειδική για ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Καθορίζει αν το ύψος του κειμένου πρέπει να κανονικοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Καθορίζει αν το κείμενο δεν πρέπει να ελεγχθεί για ορθογραφία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Επιστρέφει:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Επιστρέφει:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Επιστρέφει:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο διαγράμμισης κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες LineFormat ή κληρονομεί από τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Καθορίζει αν το στυλ υπογράμμισης έχει δικές του ιδιότητες FillFormat ή κληρονομεί από τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της Λατινικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της Λατινικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της Ανατολικής Ασιατικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της Ανατολικής Ασιατικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της γραμματοσειράς πολύπλοκου script. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες της συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Επιστρέφει ή ορίζει το κείμενο σε υπέργραμμο ή υπογραμμο. Τιμή από -100% (υπογραμμο) έως 100% (υπέργραμμο). **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Επιστρέφει ή ορίζει το κείμενο σε υπέργραμμο ή υπογραμμο. Τιμή από -100% (υπογραμμο) έως 100% (υπέργραμμο). **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο πρέπει να ενεργοποιηθεί το kerning. **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για ορθογραφικό και γραμματικό έλεγχο. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για ορθογραφικό και γραμματικό έλεγχο. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Επιστρέφει ή ορίζει την αύξηση του διαστήματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή δεν ορίζεται και πρέπει να κληρονομαστεί από το Master. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο ορθογραφικός έλεγχος επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

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
public final void setSpellCheck(boolean value...
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο ορθογραφικός έλεγχος επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.

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