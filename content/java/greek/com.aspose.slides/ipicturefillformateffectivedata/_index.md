---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides για Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες του γεμίσματος εικόνας.
type: docs
url: /el/com.aspose.slides/ipicturefillformateffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες του γεμίσματος εικόνας.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDpi()](#getDpi--) | Επιστρέφει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. |
| [getPictureFillMode()](#getPictureFillMode--) | Επιστρέφει τη λειτουργία γεμίσματος εικόνας. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα. |
| [getCropLeft()](#getCropLeft--) | Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται αριστερά της εικόνας. |
| [getCropTop()](#getCropTop--) | Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται πάνω από την εικόνα. |
| [getCropRight()](#getCropRight--) | Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται δεξιά της εικόνας. |
| [getCropBottom()](#getCropBottom--) | Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται κάτω από την εικόνα. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Επιστρέφει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Επιστρέφει τη λειτουργία γεμίσματος εικόνας. Μόνο για ανάγνωση [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Επιστρέφει:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Επιστρέφει την εικόνα. Μόνο για ανάγνωση [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Επιστρέφει:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται αριστερά της εικόνας. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται πάνω από την εικόνα. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Επιστρέφει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται δεξιά της εικόνας. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Επιστρέφει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται κάτω από την εικόνα. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float