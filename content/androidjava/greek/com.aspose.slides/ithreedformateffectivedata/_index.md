---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει τις αποτελεσματικές ιδιότητες μορφοποίησης 3Δ.
type: docs
url: /el/com.aspose.slides/ithreedformateffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει τις αποτελεσματικές ιδιότητες μορφοποίησης 3Δ.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [IThreeDFormat](../../com.aspose.slides/ithreedformat) για την επιστροφή αποτελεσματικών τιμών μορφοποίησης με κληρονομικότητα εφαρμοσμένη.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Επιστρέφει το πλάτος ενός 3Δ περιγράμματος. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Επιστρέφει το ύψος ενός εφέ εξώθησης. |
| [getDepth()](#getDepth--) | Επιστρέφει το βάθος ενός 3Δ σχήματος. |
| [getBevelTop()](#getBevelTop--) | Επιστρέφει τον τύπο της επάνω 3Δ λοξότονης ακμής. |
| [getBevelBottom()](#getBevelBottom--) | Επιστρέφει τον τύπο της κάτω 3Δ λοξότονης ακμής. |
| [getContourColor()](#getContourColor--) | Επιστρέφει το χρώμα ενός περιγράμματος. |
| [getExtrusionColor()](#getExtrusionColor--) | Επιστρέφει το χρώμα μιας εξώθησης. |
| [getCamera()](#getCamera--) | Επιστρέφει τις ρυθμίσεις μιας κάμερας. |
| [getLightRig()](#getLightRig--) | Επιστρέφει τον τύπο ενός φωτός. |
| [getMaterial()](#getMaterial--) | Επιστρέφει τον τύπο ενός υλικού. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Επιστρέφει το πλάτος ενός 3Δ περιγράμματος. Μόνο για ανάγνωση double.

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

Επιστρέφει το βάθος ενός 3Δ σχήματος. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Επιστρέφει τον τύπο της επάνω 3Δ λοξότονης ακμής. Μόνο για ανάγνωση [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Επιστρέφει:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Επιστρέφει τον τύπο της κάτω 3Δ λοξότονης ακμής. Μόνο για ανάγνωση [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Επιστρέφει:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Επιστρέφει το χρώμα ενός περιγράμματος. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Επιστρέφει το χρώμα μιας εξώθησης. Μόνο για ανάγνωση java.lang.Integer.

**Επιστρέφει:**
java.lang.Integer
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