---
title: IPictureFrame
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ένα πλαίσιο με εικόνα μέσα.
type: docs
url: /el/com.aspose.slides/ipictureframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Αντιπροσωπεύει ένα πλαίσιο με εικόνα μέσα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Επιστρέφει τα κλειδώματα του PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Επιστρέφει τα κλειδώματα του PictureFrame. Μόνο για ανάγνωση [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Επιστρέφει:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |