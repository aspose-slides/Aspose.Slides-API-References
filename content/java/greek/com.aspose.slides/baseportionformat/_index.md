---
title: BasePortionFormat
second_title: Aspose.Slides για την τεκμηρίωση του API Java
description: Κοινές ιδιότητες μορφοποίησης τμημάτων κειμένου.
type: docs
url: /el/com.aspose.slides/baseportionformat/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Κοινές ιδιότητες μορφοποίησης τμήματος κειμένου.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat του κειμένου. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει τις ιδιότητες EffectFormat του κειμένου. |
| [getHighlightColor()](#getHighlightColor--) | Επιστρέφει το χρώμα που χρησιμοποιείται για την επισήμανση κειμένου. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της κάτω γραμμής. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Επιστρέφει τις ιδιότητες FillFormat της κάτω γραμμής. |
| [getFontBold()](#getFontBold--) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [setFontBold(byte value)](#setFontBold-byte-) | Καθορίζει εάν η γραμματοσειρά είναι έντονη. |
| [getFontItalic()](#getFontItalic--) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Καθορίζει εάν η γραμματοσειρά είναι πλάγια. |
| [getKumimoji()](#getKumimoji--) | Καθορίζει εάν οι αριθμοί θα πρέπει να αγνοήσουν τη διάταξη κατακόρυφου κειμένου προσαρμοσμένη στις ανατολικές γλώσσες. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Καθορίζει εάν οι αριθμοί θα πρέπει να αγνοήσουν τη διάταξη κατακόρυφου κειμένου προσαρμοσμένη στις ανατολικές γλώσσες. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Καθορίζει εάν το ύψος ενός κειμένου πρέπει να ομαλοποιηθεί. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Καθορίζει εάν το ύψος ενός κειμένου πρέπει να ομαλοποιηθεί. |
| [getProofDisabled()](#getProofDisabled--) | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. |
| [getFontUnderline()](#getFontUnderline--) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. |
| [getTextCapType()](#getTextCapType--) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. |
| [getStrikethroughType()](#getStrikethroughType--) | Επιστρέφει ή ορίζει τον τύπο διακριτής γραμμής κειμένου. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Επιστρέφει ή ορίζει τον τύπο διακριτής γραμμής κειμένου. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. |
| [getFontHeight()](#getFontHeight--) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [setFontHeight(float value)](#setFontHeight-float-) | Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. |
| [getSymbolFont()](#getSymbolFont--) | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. |
| [getEscapement()](#getEscapement--) | Επιστρέφει ή ορίζει το υπέρ- ή υπο-κείμενο. |
| [setEscapement(float value)](#setEscapement-float-) | Επιστρέφει ή ορίζει το υπέρ- ή υπο-κείμενο. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο θα ενεργοποιηθεί το κέρνινγκ. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο θα ενεργοποιηθεί το κέρνινγκ. |
| [getLanguageId()](#getLanguageId--) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. |
| [getSpacing()](#getSpacing--) | Επιστρέφει ή ορίζει την αύξηση του διαστώματος μεταξύ χαρακτήρων. |
| [setSpacing(float value)](#setSpacing-float-) | Επιστρέφει ή ορίζει την αύξηση του διαστώματος μεταξύ χαρακτήρων. |
| [getSpellCheck()](#getSpellCheck--) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. |

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

Επιστρέφει τις ιδιότητες LineFormat για το περίγραμμα κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

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

Επιστρέφει τις ιδιότητες LineFormat που χρησιμοποιούνται για το περίγραμμα της κάτω γραμμής. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Επιστρέφει τις ιδιότητες FillFormat της κάτω γραμμής. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Καθορίζει εάν η γραμματοσειρά είναι έντονη. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Καθορίζει εάν η γραμματοσειρά είναι πλάγια. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Καθορίζει εάν οι αριθμοί θα πρέπει να αγνοήσουν τη διάταξη κατακόρυφου κειμένου προσαρμοσμένη στις ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Καθορίζει εάν οι αριθμοί θα πρέπει να αγνοήσουν τη διάταξη κατακόρυφου κειμένου προσαρμοσμένη στις ανατολικές γλώσσες. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Καθορίζει εάν το ύψος ενός κειμένου πρέπει να ομαλοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Καθορίζει εάν το ύψος ενός κειμένου πρέπει να ομαλοποιηθεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Καθορίζει εάν το κείμενο δεν πρέπει να ελεγχθεί ορθογραφικά. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Επιστρέφει:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Επιστρέφει ή ορίζει τον τύπο υπογράμμισης του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Επιστρέφει:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο κεφαλαίων του κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextCapType](../../com.aspose.slides/textcaptype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Επιστρέφει ή ορίζει τον τύπο διακριτής γραμμής κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Επιστρέφει:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο διακριτής γραμμής κειμένου. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/Εγγραφή [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες LineFormat ή κληρονομεί τις ιδιότητες LineFormat του κειμένου. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Καθορίζει εάν το στυλ υπογράμμισης έχει τις δικές του ιδιότητες FillFormat ή κληρονομεί τις ιδιότητες FillFormat του κειμένου. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος είναι αόριστο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Επιστρέφει:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος γραμματοσειράς ενός τμήματος. **Float.NaN** σημαίνει ότι το ύψος είναι αόριστο και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Latin. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς Ανατολικής Ασίας. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες γραμματοσειράς σύνθετου script. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Επιστρέφει ή ορίζει τις πληροφορίες συμβολικής γραμματοσειράς. Null σημαίνει ότι η γραμματοσειρά είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Επιστρέφει ή ορίζει το υπερ- ή υπο-κείμενο. Τιμή από -100% (υπό-δείκτη) έως 100% (υπέρ-δείκτη). **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Επιστρέφει:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Επιστρέφει ή ορίζει το υπερ- ή υπο-κείμενο. Τιμή από -100% (υπό-δείκτη) έως 100% (υπέρ-δείκτη). **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο θα ενεργοποιηθεί το κέρνινγκ. **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Επιστρέφει:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Επιστρέφει ή ορίζει το ελάχιστο μέγεθος γραμματοσειράς για το οποίο θα ενεργοποιηθεί το κέρνινγκ. **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας γλώσσας ελέγχου. Χρησιμοποιείται για έλεγχο ορθογραφίας και γραμματικής. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Επιστρέφει ή ορίζει το Id μιας εναλλακτικής γλώσσας. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Επιστρέφει ή ορίζει την αύξηση του διαστώματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Επιστρέφει:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Επιστρέφει ή ορίζει την αύξηση του διαστώματος μεταξύ χαρακτήρων. **Float.NaN** σημαίνει ότι η τιμή είναι αόριστη και πρέπει να κληρονομηθεί από το Master. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο έλεγχος είναι επιτρεπτός. Η προεπιλογή είναι  false .

---

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα στην πρώτη διαφάνεια
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Ενεργοποίηση ορθογραφικού ελέγχου για αυτό το τμήμα κειμένου
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
public final void setSpellCheck(boolean value)
```

Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν ο ορθογραφικός έλεγχος είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα είναι false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν είναι true, ο έλεγχος είναι επιτρεπτός. Η προεπιλογή είναι  false .

---

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα στην πρώτη διαφάνεια
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Ενεργοποίηση ορθογραφικού ελέγχου για αυτό το τμήμα κειμένου
>      portion.getPortionFormat().setSpellCheck(true);
>      // Αποθήκευση της τροποποιημένης παρουσίασης
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |