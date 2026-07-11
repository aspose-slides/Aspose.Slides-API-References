---
title: Picture
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια εικόνα σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/picture/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Αντιπροσωπεύει μια εικόνα σε παρουσίαση.
## Μεθόδοι

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. |
| [getImageTransform()](#getImageTransform--) | Επιστρέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την παρουσίαση. |
| [equals(Object obj)](#equals-java.lang.Object-) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει το hash. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια μιας εικόνας. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο για ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Επιστρέφει ή ορίζει την ενσωματωμένη εικόνα. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει τη διεύθυνση URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Επιστρέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. Μόνο για ανάγνωση [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Επιστρέφει:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Συγκρίνει με το καθορισμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Αντικείμενο προς σύγκριση. |

**Επιστρέφει:**
boolean - True αν τα αντικείμενα είναι ίσα, διαφορετικά false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Επιστρέφει το hash.

**Επιστρέφει:**
int - Hash.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια μιας εικόνας. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)