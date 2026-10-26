---
title: IThreeDFormat
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ιδιότητες 3-D.
type: docs
url: /el/com.aspose.slides/ithreedformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Αντιπροσωπεύει τις ιδιότητες 3-D.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. |
| [setContourWidth(double value)](#setContourWidth-double-) | Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Επιστρέφει ή ορίζει το ύψος μιας εφέ εξώθησης. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Επιστρέφει ή ορίζει το ύψος μιας εφέ εξώθησης. |
| [getDepth()](#getDepth--) | Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. |
| [setDepth(double value)](#setDepth-double-) | Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. |
| [getBevelTop()](#getBevelTop--) | Επιστρέφει ή ορίζει τον τύπο μιας επάνω 3D λοξοτμής. |
| [getBevelBottom()](#getBevelBottom--) | Επιστρέφει ή ορίζει τον τύπο μιας κάτω 3D λοξοτμής. |
| [getContourColor()](#getContourColor--) | Επιστρέφει ή ορίζει το χρώμα ενός περιγράμματος. |
| [getExtrusionColor()](#getExtrusionColor--) | Επιστρέφει ή ορίζει το χρώμα μιας εξώθησης. |
| [getCamera()](#getCamera--) | Επιστρέφει ή ορίζει τις ρυθμίσεις μιας κάμερας. |
| [getLightRig()](#getLightRig--) | Επιστρέφει ή ορίζει τον τύπο ενός φωτός. |
| [getMaterial()](#getMaterial--) | Επιστρέφει ή ορίζει τον τύπο ενός υλικού. |
| [setMaterial(int value)](#setMaterial-int-) | Επιστρέφει ή ορίζει τον τύπο ενός υλικού. |
| [getEffective()](#getEffective--) | Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης 3-D με την κληρονομικότητα που εφαρμόζεται. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Επιστρέφει ή ορίζει το ύψος μιας εφέ εξώθησης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Επιστρέφει ή ορίζει το ύψος μιας εφέ εξώθησης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Επιστρέφει ή ορίζει τον τύπο μιας επάνω 3D λοξοτμής. Μόνο για ανάγνωση [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Επιστρέφει:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Επιστρέφει ή ορίζει τον τύπο μιας κάτω 3D λοξοτμής. Μόνο για ανάγνωση [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Επιστρέφει:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Επιστρέφει ή ορίζει το χρώμα ενός περιγράμματος. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Επιστρέφει ή ορίζει το χρώμα μιας εξώθησης. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Επιστρέφει ή ορίζει τις ρυθμίσεις μιας κάμερας. Μόνο για ανάγνωση [ICamera](../../com.aspose.slides/icamera).

**Επιστρέφει:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Επιστέ

φει ή ορίζει τον τύπο ενός φωτός. Μόνο για ανάγνωση [ILightRig](../../com.aspose.slides/ilightrig).

**Επιστρέφει:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Επιστρέφει ή ορίζει τον τύπο ενός υλικού. Ανάγνωση/εγγραφή [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Επιστρέφει:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Επιστρέφει ή ορίζει τον τύπο ενός υλικού. Ανάγνωση/εγγραφή [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης 3-D με την κληρονομικότητα που εφαρμόζεται.

**Επιστρέφει:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Ένα [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).