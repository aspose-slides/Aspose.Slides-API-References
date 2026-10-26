---
title: PVIObject
second_title: Aspose.Slides για Java – Αναφορά API
description: Καταρτίζει τη βασική υποδομή υπηρεσιών για αντικείμενα που μπορούν να αποτελούν αντικείμενο κληρονομίας τιμής ιδιότητας.
type: docs
url: /el/com.aspose.slides/pviobject/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Καταρτίζει τη βασική υποδομή υπηρεσιών για αντικείμενα που μπορούν να αποτελούν αντικείμενο κληρονομίας τιμής ιδιότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει κωδικό hash. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Επιστρέφει αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


Επιστρέφει γονικό IPresentationComponent. Μόνο για ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```




**Επιστρέφει:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```


Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[Presentation](../../com.aspose.slides/presentation)
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


Επιστρέφει κωδικό hash.

**Επιστρέφει:**
int - Hash code.