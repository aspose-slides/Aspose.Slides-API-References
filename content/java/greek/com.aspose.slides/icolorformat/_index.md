---
title: IColorFormat
second_title: Aspose.Slides για Java - Αναφορά API
description: Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/icolorformat/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorType()](#getColorType--) | Επιστρέφει ή ορίζει τη μέθοδο καθορισμού χρώματος. |
| [setColorType(int value)](#setColorType-int-) | Επιστρέφει ή ορίζει τη μέθοδο καθορισμού χρώματος. |
| [getColor()](#getColor--) | Επιστρέφει το τελικό χρώμα (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Επιστρέφει το τελικό χρώμα (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). |
| [getPresetColor()](#getPresetColor--) | Επιστρέφει ή ορίζει την προεπιλογή χρώματος. |
| [setPresetColor(int value)](#setPresetColor-int-) | Επιστρέφει ή ορίζει την προεπιλογή χρώματος. |
| [getSystemColor()](#getSystemColor--) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. |
| [setSystemColor(int value)](#setSystemColor-int-) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. |
| [getSchemeColor()](#getSchemeColor--) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σύστημα χρωμάτων. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σύστημα χρωμάτων. |
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
| [getHue()](#getHue--) | Επιστρέφει ή ορίζει το συστατικό απόχρωση ενός χρώματος στην αναπαράσταση HSL. |
| [setHue(float value)](#setHue-float-) | Επιστρέφει ή ορίζει το συστατικό απόχρωση ενός χρώματος στην αναπαράσταση HSL. |
| [getSaturation()](#getSaturation--) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. |
| [getLuminance()](#getLuminance--) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. |
| [getColorTransform()](#getColorTransform--) | Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. |
| [toString(int format)](#toString-int-) | Επιστρέφει μια String που αντιπροσωπεύει την τρέχουσα μορφή χρώματος. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Αντιγράφει τη μορφή χρώματος από το "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Επιστρέφει ή ορίζει τη μέθοδο καθορισμού χρώματος. Ανάγνωση/Εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Επιστρέφει:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο καθορισμού χρώματος. Ανάγνωση/Εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Επιστρέφει το τελικό χρώμα (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). Ορίζει χρώματα RGB και εκκαθαρίζει όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/Εγγραφή java.awt.Color.

**Επιστρέφει:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Επιστρέφει το τελικό χρώμα (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). Ορίζει χρώματα RGB και εκκαθαρίζει όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/Εγγραφή java.awt.Color.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Επιστρέφει ή ορίζει την προεπιλογή χρώματος. Ανάγνωση/Εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Επιστρέφει:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Επιστρέφει ή ορίζει την προεπιλογή χρώματος. Ανάγνωση/Εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. Ανάγνωση/Εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Επιστρέφει:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. Ανάγνωση/Εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σύστημα χρωμάτων. Ανάγνωση/Εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Επιστρέφει:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σύστημα χρωμάτων. Ανάγνωση/Εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Επιστρέφει:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Επιστρέφει:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Επιστρέφει:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Επιστέ

ψιει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Επιστρέφει ή ορίζει το συστατικό απόχρωση ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Επιστρέφει ή ορίζει το συστατικό απόχρωση ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Επιστρέφει:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο για ανάγνωση [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

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
| format | int | Ένας τύπος μορφής χρωματικού string. |

**Επιστρέφει:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει την τρέχουσα μορφή χρώματος.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Αντιγράφει τη μορφή χρώματος από το "color".

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |