---
title: SoftEdge
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει ένα εφέ ήπιας άκρης.
type: docs
url: /el/com.aspose.slides/softedge/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Αντιπροσωπεύει ένα εφέ ήπιας άκρης. Οι άκρες του σχήματος είναι θολές, ενώ το γέμισμα δεν επηρεάζεται.
## Μεθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Καθορίζει την ακτίνα θολώματος που θα εφαρμοστεί στις άκρες. |
| [setRadius(double value)](#setRadius-double-) | Καθορίζει την ακτίνα θολώματος που θα εφαρμοστεί στις άκρες. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Soft Edge με την κληρονομικότητα που εφαρμόστηκε. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο [SoftEdge](../../com.aspose.slides/softedge) είναι ίσο με το τρέχον [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για ένα συγκεκριμένο τύπο. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Καθορίζει την ακτίνα θολώματος που θα εφαρμοστεί στις άκρες. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Καθορίζει την ακτίνα θολώματος που θα εφαρμοστεί στις άκρες. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Soft Edge με την κληρονομικότητα που εφαρμόστηκε.

**Επιστρέφει:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Ένα [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το καθορισμένο [SoftEdge](../../com.aspose.slides/softedge) είναι ίσο με το τρέχον [SoftEdge](../../com.aspose.slides/softedge).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [SoftEdge](../../com.aspose.slides/softedge) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για ένα συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.