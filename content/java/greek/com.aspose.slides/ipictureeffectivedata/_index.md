---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιλαμβάνει αποτελεσματικές ιδιότητες εικόνας.
type: docs
url: /el/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Αμετάβλητο αντικείμενο που περιλαμβάνει αποτελεσματικές ιδιότητες εικόνας.

Αυτή η διεπαφή χρησιμοποιείται ως μέρος των [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) και [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImage()](#getImage--) | Επιστρέφει την ενσωματωμένη εικόνα. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει τη διεύθυνση URL της συνδεδεμένης εικόνας. |
| [getImageTransform()](#getImageTransform--) | Επιστρέφει τη συλλογή των μετασχηματισμών εικόνας. |
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


Επιστρέφει τη διεύθυνση URL της συνδεδεμένης εικόνας. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Επιστρέφει τη συλλογή των μετασχηματισμών εικόνας. Μόνο για ανάγνωση [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Επιστρέφει:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)