---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /el/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες της εικόνας.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) και [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImage()](#getImage--) | Επιστρέφει την ενσωματωμένη εικόνα. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει το URL της συνδεδεμένης εικόνας. |
| [getImageTransform()](#getImageTransform--) | Επιστέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Επιστρέφει την ενσωματωμένη εικόνα. Μόνο για ανάγνωση [IPPImage](../../com.aspose.slides/ippimage).

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Επιστρέφει το URL της συνδεδεμένης εικόνας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Επιστέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. Μόνο για ανάγνωση [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Επιστρέφει:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)