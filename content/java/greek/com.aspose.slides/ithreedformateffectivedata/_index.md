---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides για Java Αναφορά API
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει τις αποτελεσματικές ιδιότητες μορφοποίησης 3-D.
type: docs
url: /el/com.aspose.slides/ithreedformateffectivedata/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει τις αποτελεσματικές ιδιότητες μορφοποίησης 3-D.

--------------------

Αυτή η διασύνδεση χρησιμοποιείται μαζί με τη διασύνδεση [IThreeDFormat](../../com.aspose.slides/ithreedformat) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με εφαρμοσμένη κληρονομικότητα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Επιστρέφει το πλάτος ενός 3D περιγράμματος. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Επιστρέφει το ύψος ενός εφέ εξώθησης. |
| [getDepth()](#getDepth--) | Επιστρέφει το βάθος ενός 3D σχήματος. |
| [getBevelTop()](#getBevelTop--) | Επιστρέφει τον τύπο μιας άνω 3D λοξότμησης. |
| [getBevelBottom()](#getBevelBottom--) | Επιστρέφει τον τύπο μιας κάτω 3D λοξότμησης. |
| [getContourColor()](#getContourColor--) | Επιστρέφει το χρώμα ενός περιγράμματος. |
| [getExtrusionColor()](#getExtrusionColor--) | Επιστρέφει το χρώμα μιας εξώθησης. |
| [getCamera()](#getCamera--) | Επιστρέφει τις ρυθμίσεις μιας κάμερας. |
| [getLightRig()](#getLightRig--) | Επιστρέφει τον τύπο ενός φωτός. |
| [getMaterial()](#getMaterial--) | Επιστρέφει τον τύπο ενός υλικού. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Επιστρέφει το πλάτος ενός 3D περιγράμματος. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Επιστρέφει το ύψος ενός εφέ εξώθησης. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Επιστρέφει το βάθος ενός 3D σχήματος. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Επιστρέφει τον τύπο μιας άνω 3D λοξότμησης. Μόνο για ανάγνωση [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Επιστρέφει:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Επιστρέφει τον τύπο μιας κάτω 3D λοξότμησης. Μόνο για ανάγνωση [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Επιστρέφει:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

Επιστρέφει το χρώμα ενός περιγράμματος. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

Επιστρέφει το χρώμα μιας εξώθησης. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color

### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Επιστρέφει τις ρυθμίσεις μιας κάμερας. Μόνο για ανάγνωση [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Επιστρέφει:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)

### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Επιστρέφει τον τύπο ενός φωτός. Μόνο για ανάγνωση [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Επιστρέφει:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Επιστρέφει τον τύπο ενός υλικού. Μόνο για ανάγνωση [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Επιστρέφει:**
int