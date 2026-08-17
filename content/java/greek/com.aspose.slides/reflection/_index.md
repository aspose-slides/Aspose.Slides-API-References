---
title: Reflection
second_title: Aspose.Slides για το Java API Reference
description: Αναπαριστά ένα εφέ Αντανάκλασης.
type: docs
url: /el/com.aspose.slides/reflection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Αναπαριστά ένα εφέ Αντανάκλασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα έναρξης (ποσοστά). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα έναρξης (ποσοστά). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα λήξης (ποσοστά). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα λήξης (ποσοστά). |
| [getFadeDirection()](#getFadeDirection--) | Καθορίζει την κατεύθυνση μετατόπισης της αντανάκλασης. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Καθορίζει την κατεύθυνση μετατόπισης της αντανάκλασης. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Αρχική αδιαφάνεια αντανάκλασης. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Αρχική αδιαφάνεια αντανάκλασης. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Τελική αδιαφάνεια αντανάκλησης. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Τελική αδιαφάνεια αντανάκλησης. |
| [getBlurRadius()](#getBlurRadius--) | Ακτίνα θολώματος. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Ακτίνα θολώματος. |
| [getDirection()](#getDirection--) | Κατεύθυνση της αντανάκλησης. |
| [setDirection(float value)](#setDirection-float-) | Κατεύθυνση της αντανάκλησης. |
| [getDistance()](#getDistance--) | Απόσταση της αντανάκλησης. |
| [setDistance(double value)](#setDistance-double-) | Απόσταση της αντανάκλησης. |
| [getRectangleAlign()](#getRectangleAlign--) | Στοίχιση του ορθογωνίου. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Στοίχιση του ορθογωνίου. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Καθορίζει τη γωνία οριζόντιας παραμόρφωσης. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Καθορίζει τη γωνία οριζόντιας παραμόρφωσης. |
| [getSkewVertical()](#getSkewVertical--) | Καθορίζει τη γωνία κάθετης παραμόρφωσης. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Καθορίζει τη γωνία κάθετης παραμόρφωσης. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Καθορίζει αν η αντανάκληση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Καθορίζει αν η αντανάκληση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Καθορίζει τον οριζόντιο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Καθορίζει τον οριζόντιο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). |
| [getScaleVertical()](#getScaleVertical--) | Καθορίζει τον κάθετο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Καθορίζει τον κάθετο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Αντανάκληση με την εφαρμοσμένη κληρονομιά. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν το συγκεκριμένο [Reflection](../../com.aspose.slides/reflection) είναι ίσο με το τρέχον [Reflection](../../com.aspose.slides/reflection). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα έναρξης (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

Καθορίζει τη θέση έναρξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα έναρξης (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα λήξης (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

Καθορίζει τη θέση λήξης (κατά μήκος της κλίμακας διαβάθμισης άλφα) της τιμής άλφα λήξης (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

Καθορίζει την κατεύθυνση μετατόπισης της αντανάκλησης. (γωνία). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

Καθορίζει την κατεύθυνση μετατόπισης της αντανάκλησης. (γωνία). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

Αρχική αδιαφάνεια αντανάκλησης. (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

Αρχική αδιαφάνεια αντανάκλησης. (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

Τελική αδιαφάνεια αντανάκλησης. (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

Τελική αδιαφάνεια αντανάκλησης. (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Ακτίνα θολώματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Κατεύθυνση της αντανάκλησης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Κατεύθυνση της αντανάκλησης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Απόσταση της αντανάκλησης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Απόσταση της αντανάκλησης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Στοίχιση του ορθογωνίου. Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Επιστρέφει:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Στοίχιση του ορθογωνίου. Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Καθορίζει τη γωνία οριζόντιας παραμόρφωσης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Καθορίζει τη γωνία οριζόντιας παραμόρφωσης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Καθορίζει τη γωνία κάθετης παραμόρφωσης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Καθορίζει τη γωνία κάθετης παραμόρφωσης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Καθορίζει αν η αντανάκληση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Καθορίζει αν η αντανάκληση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Καθορίζει τον οριζόντιο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Καθορίζει τον οριζόντιο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Καθορίζει τον κάθετο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Καθορίζει τον κάθετο παράγοντα κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί ανίστροφη (ποσοστά). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Αντανάκληση με την εφαρμοσμένη κληρονομιά.

**Επιστρέφει:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - ένα [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Έκδοση. Μόνο-ανάγνωση long.

**Επιστρέφει:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο-ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει αν το συγκεκριμένο [Reflection](../../com.aspose.slides/reflection) είναι ίσο με το τρέχον [Reflection](../../com.aspose.slides/reflection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [Reflection](../../com.aspose.slides/reflection) για σύγκριση. |

**Επιστρέφει:**
boolean - true αν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.