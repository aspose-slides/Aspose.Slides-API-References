---
title: IColorFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/icolorformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorType()](#getColorType--) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [setColorType(int value)](#setColorType-int-) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [getColor()](#getColor--) | Επιστρέφει το τελικό χρώμα (με όλες τις μετασχηματισμούς χρώματος εφαρμόσες). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Επιστρέφει το τελικό χρώμα (με όλες τις μετασχηματισμούς χρώματος εφαρμόσες). |
| [getPresetColor()](#getPresetColor--) | Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. |
| [setPresetColor(int value)](#setPresetColor-int-) | Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. |
| [getSystemColor()](#getSystemColor--) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. |
| [setSystemColor(int value)](#setSystemColor-int-) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. |
| [getSchemeColor()](#getSchemeColor--) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. |
| [getR()](#getR--) | Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. |
| [setR(byte value)](#setR-byte-) | Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. |
| [getG()](#getG--) | Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. |
| [setG(byte value)](#setG-byte-) | Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. |
| [getB()](#getB--) | Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. |
| [setB(byte value)](#setB-byte-) | Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. |
| [getFloatR()](#getFloatR--) | Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. |
| [setFloatR(float value)](#setFloatR-float-) | Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. |
| [getFloatG()](#getFloatG--) | Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. |
| [setFloatG(float value)](#setFloatG-float-) | Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. |
| [getFloatB()](#getFloatB--) | Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. |
| [setFloatB(float value)](#setFloatB-float-) | Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. |
| [getHue()](#getHue--) | Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. |
| [setHue(float value)](#setHue-float-) | Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. |
| [getSaturation()](#getSaturation--) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. |
| [getLuminance()](#getLuminance--) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. |
| [getColorTransform()](#getColorTransform--) | Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. |
| [toString(int format)](#toString-int-) | Επιστρέφει μια String που αντιπροσωπεύει την τρέχουσα μορφή χρώματος. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Αντιγράψτε τη μορφή χρώματος από "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Επιστρέφει:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Επιστρέφει το τελικό χρώμα (με όλες τις μετασχηματισμούς χρώματος εφαρμόσες). Ορίζει χρώματα RGB και διαγράφει όλες τις μετασχηματισμούς χρώματος. Ανάγνωση/εγγραφή java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Επιστρέφει το τελικό χρώμα (με όλες τις μετασχηματισμούς χρώματος εφαρμόσες). Ορίζει χρώματα RGB και διαγράφει όλες τις μετασχηματισμούς χρώματος. Ανάγνωση/εγγραφή java.lang.Integer.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. Ανάγνωση/εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Επιστρέφει:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. Ανάγνωση/εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. Ανάγνωση/εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Επιστρέφει:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. Ανάγνωση/εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Επιστρέφει:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο ανάγνωση [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Επιστρέφει:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Επιστρέφει μια String που αντιπροσωπεύει την τρέχουσα μορφή χρώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | int | Ένας τύπος μορφής συμβολοσειράς χρώματος. |

**Επιστρέφει:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει την τρέχουσα μορφή χρώματος.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Αντιγράψτε τη μορφή χρώματος από "color".

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Χρώμα [IColorFormat](../../com.aspose.slides/icolorformat) |