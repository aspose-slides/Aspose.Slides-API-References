---
title: ISlidesPicture
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά μια εικόνα σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/islidespicture/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Αναπαριστά μια εικόνα σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImage()](#getImage--) | Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. |
| [getImageTransform()](#getImageTransform--) | Επιστρέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Επιστρέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. Μόνο για ανάγνωση [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Επιστρέφει:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)