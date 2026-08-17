---
title: Picture
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια εικόνα σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/picture/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Αντιπροσωπεύει μια εικόνα σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Returns or sets the embedded image. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returns or sets the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns of sets linked image's URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns of sets linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
| [getPresentation()](#getPresentation--) | Returns the presentation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares with specified object. |
| [hashCode()](#hashCode--) | Returns hash. |
| [getSlide()](#getSlide--) | Returns the parent slide of a picture. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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

Επιστρέφει ή ορίζει το URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το URL της συνδεδεμένης εικόνας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Επιστρέφει τη συλλογή των εφέ μετασχηματισμού εικόνας. Μόνο ανάγνωση [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Επιστρέφει:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την παρουσίαση. Μόνο ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

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
boolean - True εάν τα αντικείμενα είναι ίσα, διαφορετικά false.
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

Επιστρέφει το γονικό slide μιας εικόνας. Μόνο ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)