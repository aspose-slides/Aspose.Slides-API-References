---
title: ColorFormat
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/colorformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Αντιπροσωπεύει ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorType()](#getColorType--) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [setColorType(int value)](#setColorType-int-) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [getColor()](#getColor--) | Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). |
| [getPresetColor()](#getPresetColor--) | Επιστρέφει ή ορίζει την προρυθμισμένη τιμή χρώματος. |
| [setPresetColor(int value)](#setPresetColor-int-) | Επιστρέφει ή ορίζει την προρυθμισμένη τιμή χρώματος. |
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
| [getHue()](#getHue--) | Επιστρέφει ή ορίζει το συστατικό τόνου ενός χρώματος σε αναπαράσταση HSL. |
| [setHue(float value)](#setHue-float-) | Επιστρέφει ή ορίζει το συστατικό τόνου ενός χρώματος σε αναπαράσταση HSL. |
| [getSaturation()](#getSaturation--) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. |
| [getLuminance()](#getLuminance--) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. |
| [getColorTransform()](#getColorTransform--) | Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. |
| [toString(int format)](#toString-int-) | Επιστρέφει ένα String που αντιπροσωπεύει την τρέχουσα μορφή χρώματος. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Αντιγράφει τη μορφή χρώματος από το "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει την ισότητα με το συγκεκριμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει κωδικό hash. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getColorType() {#getColorType--}
```
public final int getColorType()
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/Εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Επιστροφή:**
int
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/Εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). Ορίζει χρώματα RGB και εκκαθαρίζει όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/Εγγραφή java.awt.Color.

**Επιστροφή:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις εφαρμοσμένες μετασχηματισμούς χρώματος). Ορίζει χρώματα RGB και εκκαθαρίζει όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/Εγγραφή java.awt.Color.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Επιστρέφει ή ορίζει την προρυθμισμένη τιμή χρώματος. Ανάγνωση/Εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Επιστροφή:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Επιστρέφει ή ορίζει την προρυθμισμένη τιμή χρώματος. Ανάγνωση/Εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. Ανάγνωση/Εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Επιστροφή:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα συστήματος χρωμάτων. Ανάγνωση/Εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/Εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Επιστροφή:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/Εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  byte .

**Επιστροφή:**
byte
### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  byte .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται.

**Επιστροφή:**
byte
### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  byte .

**Επιστροφή:**
byte
### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  byte .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Επιστρέφει ή ορίζει το συστατικό τόνου ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Επιστρέφει ή ορίζει το συστατικό τόνου ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Επιστροφή:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Ανάγνωση/Εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο για ανάγνωση [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Επιστροφή:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public final IColorOperationCollection getColorTransform()
```

Επιστρέφει ένα String που αντιπροσωπεύει την τρέχουσα μορφή χρώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | int | Ένας τύπος μορφής χρωματικής συμβολοσειράς. |

**Επιστροφή:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει την τρέχουσα μορφή χρώματος.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Αντιγράφει τη μορφή χρώματος από το "color".

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ελέγχει την ισότητα με το συγκεκριμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Αντικείμενο. |

**Επιστροφή:**
boolean - True if objects are equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Επιστρέφει κωδικό hash.

**Επιστροφή:**
int - Hash code.
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστροφή:**
long
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```




**Επιστροφή:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο για ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστροφή:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)