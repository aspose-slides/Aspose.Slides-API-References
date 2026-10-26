---
title: IPictureFrame
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα πλαίσιο με εικόνα μέσα.
type: docs
url: /el/com.aspose.slides/ipictureframe/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Αντιπροσωπεύει ένα πλαίσιο με εικόνα μέσα.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Returns PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Returns the PictureFillFormat object for a picture frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Επιστρέφει τις κλειδώσεις του PictureFrame. Μόνο για ανάγνωση [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

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

Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικό με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικό με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικό με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικό με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |