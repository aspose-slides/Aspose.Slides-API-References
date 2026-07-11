---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες του γεμίσματος εικόνας.
type: docs
url: /el/com.aspose.slides/ipicturefillformateffectivedata/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες του γεμίσματος εικόνας.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDpi()](#getDpi--) | Επιστρέφει το dpi που χρησιμοποιείται για τη γέμιση μιας εικόνας. |
| [getPictureFillMode()](#getPictureFillMode--) | Επιστρέφει τη λειτουργία γεμίσματος εικόνας. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα. |
| [getCropLeft()](#getCropLeft--) | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. |
| [getCropTop()](#getCropTop--) | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους της εικόνας που περικόπτεται από την άνω πλευρά της εικόνας. |
| [getCropRight()](#getCropRight--) | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. |
| [getCropBottom()](#getCropBottom--) | Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Επιστρέφει το dpi που χρησιμοποιείται για τη γέμιση μιας εικόνας. Μόνο για ανάγνωση int.

**Returns:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Επιστρέφει τη λειτουργία γεμίσματος εικόνας. Μόνο για ανάγνωση [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Returns:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Επιστρέφει την εικόνα. Μόνο για ανάγνωση [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. Μόνο για ανάγνωση float.

**Returns:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους της εικόνας που περικόπτεται από την άνω πλευρά της εικόνας. Μόνο για ανάγνωση float.

**Returns:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Επιστρέφει τον αριθμό των ποσοστών του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. Μόνο για ανάγνωση float.

**Returns:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Επιστρέφει τον αριθμό των ποσοστών του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. Μόνο για ανάγνωση float.

**Returns:**
float