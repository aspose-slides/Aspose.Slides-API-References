---
title: IReflection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα εφέ ανάκλασης.
type: docs
url: /el/com.aspose.slides/ireflection/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

Represents a reflection effect.
## Methods

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Καθορίζει τη θέση εκκίνησης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της αρχικής τιμής άλφα (ποσοστά). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Καθορίζει τη θέση εκκίνησης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της αρχικής τιμής άλφα (ποσοστά). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Καθορίζει τη θέση λήξης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της τελικής τιμής άλφα (ποσοστά). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Καθορίζει τη θέση λήξης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της τελικής τιμής άλφα (ποσοστά). |
| [getFadeDirection()](#getFadeDirection--) | Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Αρχική διαφάνεια ανάκλασης (ποσοστά). |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Αρχική διαφάνεια ανάκλασης (ποσοστά). |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Τελική διαφάνεια ανάκλασης (ποσοστά). |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Τελική διαφάνεια ανάκλασης (ποσοστά). |
| [getBlurRadius()](#getBlurRadius--) | Ακτίνα θόλωσης. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Ακτίνα θόλωσης. |
| [getDirection()](#getDirection--) | Κατεύθυνση ανάκλασης. |
| [setDirection(float value)](#setDirection-float-) | Κατεύθυνση ανάκλασης. |
| [getDistance()](#getDistance--) | Απόσταση ανάκλασης. |
| [setDistance(double value)](#setDistance-double-) | Απόσταση ανάκλασης. |
| [getRectangleAlign()](#getRectangleAlign--) | Στοίχιση ορθογωνίου. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Στοίχιση ορθογωνίου. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Καθορίζει τη γωνία οριζόντιας διαστρέβλωσης. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Καθορίζει τη γωνία οριζόντιας διαστρέβλωσης. |
| [getSkewVertical()](#getSkewVertical--) | Καθορίζει τη γωνία κάθετης διαστρέβλωσης. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Καθορίζει τη γωνία κάθετης διαστρέβλωσης. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή. |
| [getScaleVertical()](#getScaleVertical--) | Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Καθορίζει τη θέση εκκίνησης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της αρχικής τιμής άλφα (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

Καθορίζει τη θέση εκκίνησης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της αρχικής τιμής άλφα (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Καθορίζει τη θέση λήξης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της τελικής τιμής άλφα (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

Καθορίζει τη θέση λήξης (κατά μήκος της καταβάσεως διαβάθμισης άλφα) της τελικής τιμής άλφα (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. (γωνία). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

Καθορίζει την κατεύθυνση μετατόπισης της ανάκλασης. (γωνία). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Αρχική διαφάνεια ανάκλασης (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

Αρχική διαφάνεια ανάκλασης (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Τελική διαφάνεια ανάκλασης (ποσοστά). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

Τελική διαφάνεια ανάκλασης (ποσοστά). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Ακτίνα θόλωσης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Ακτίνα θόλωσης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Κατεύθυνση ανάκλασης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Κατεύθυνση ανάκλασης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Απόσταση ανάκλασης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Απόσταση ανάκλασης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Στοίχιση ορθογωνίου. Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Επιστρέφει:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Στοίχιση ορθογωνίου. Ανάγνωση/εγγραφή [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Καθορίζει τη γωνία οριζόντιας διαστρέβλωσης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Καθορίζει τη γωνία οριζόντιας διαστρέβλωσης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Καθορίζει τη γωνία κάθετης διαστρέβλωσης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Καθορίζει τη γωνία κάθετης διαστρέβλωσης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Καθορίζει αν η ανάκλαση πρέπει να περιστρέφεται μαζί με το σχήμα όταν το σχήμα περιστρέφεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή (ποσοστά). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Καθορίζει τον οριζόντιο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή (ποσοστά). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαλεί αναστροφή (ποσοστά). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Καθορίζει τον κάθετο συντελεστή κλιμάκωσης, η αρνητική κλιμάκωση προκαίζει αναστροφή (ποσοστά). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |