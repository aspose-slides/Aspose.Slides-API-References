---
title: ColorFormat
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
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

Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColorType()](#getColorType--) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [setColorType(int value)](#setColorType-int-) | Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. |
| [getColor()](#getColor--) | Επιστρέφει το τελικό χρώμα (με όλους τους μετασχηματισμούς χρώματος εφαρμόζονται). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Επιστρέφει το τελικό χρώμα (με όλους τους μετασχηματισμούς χρώματος εφαρμόζονται). |
| [getPresetColor()](#getPresetColor--) | Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. |
| [setPresetColor(int value)](#setPresetColor-int-) | Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. |
| [getSystemColor()](#getSystemColor--) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. |
| [setSystemColor(int value)](#setSystemColor-int-) | Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. |
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
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει την ισότητα με το καθορισμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getColorType() {#getColorType--}
```
public final int getColorType()
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Επιστρέφει:**
int
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Επιστρέφει ή ορίζει τη μέθοδο ορισμού χρώματος. Ανάγνωση/εγγραφή [ColorType](../../com.aspose.slides/colortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public final Integer getColor()
```

Επιστρέφει το τελικό χρώμα (με όλους τους μετασχηματισμούς χρώματος εφαρμόζονται). Ορίζει χρώματα RGB και αφαιρεί όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/εγγραφή java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Επιστρέφει το τελικό χρώμα (με όλους τους μετασχηματισμούς χρώματος εφαρμόζονται). Ορίζει χρώματα RGB και αφαιρεί όλους τους μετασχηματισμούς χρώματος. Ανάγνωση/εγγραφή java.lang.Integer.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. Ανάγνωση/εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Επιστρέφει:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Επιστρέφει ή ορίζει το προεπιλεγμένο χρώμα. Ανάγνωση/εγγραφή [PresetColor](../../com.aspose.slides/presetcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. Ανάγνωση/εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Επιστρέφει:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων συστήματος. Ανάγνωση/εγγραφή [SystemColor](../../com.aspose.slides/systemcolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Επιστρέφει:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Επιστρέφει ή ορίζει το χρώμα που προσδιορίζεται από ένα σχήμα χρώματος. Ανάγνωση/εγγραφή [SchemeColor](../../com.aspose.slides/schemecolor).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public final byte getR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public final byte getG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται.

**Επιστρέφει:**
byte
### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public final byte getB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Επιστρέφει ή ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Επιστρέφει ή ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Επιστρέφει ή ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public final float getHue()
```

Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Επιστρέφει ή ορίζει το συστατικό απόχρωσης ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Επιστρέφει ή ορίζει το συστατικό κορεσμού ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλήονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Επιστρέφει ή ορίζει το συστατικό φωτεινότητας ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος παραβλέπονται. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο για ανάγνωση [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Επιστρέφει:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public final String toString(int format)
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
public final void copyFrom(IColorFormat color)
```

Αντιγράψτε τη μορφή χρώματος από "color".

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ελέγχει την ισότητα με το καθορισμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Object. |

**Επιστρέφει:**
boolean - True if objects are equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Επιστρέφει τον κωδικό κατακερματισμού.

**Επιστρέφει:**
int - Hash code.
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```




**Επιστρέφει:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονέα IPresentationComponent. Μόνο για ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)