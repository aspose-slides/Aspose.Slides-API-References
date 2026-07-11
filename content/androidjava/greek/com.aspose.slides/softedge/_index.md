---
title: SoftEdge
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα εφέ Soft Edge.
type: docs
url: /el/com.aspose.slides/softedge/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Αναπαριστά ένα εφέ Soft Edge. Οι άκρες του σχήματος είναι θολές, ενώ η γέμιση δεν επηρεάζεται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Καθορίζει την ακτίνα θολώματος που εφαρμόζεται στις άκρες. |
| [setRadius(double value)](#setRadius-double-) | Καθορίζει την ακτίνα θολώματος που εφαρμόζεται στις άκρες. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Soft Edge με την κληρονομική εφαρμογή. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο [SoftEdge](../../com.aspose.slides/softedge) είναι ίσο με το τρέχον [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Καθορίζει την ακτίνα θολώματος που εφαρμόζεται στις άκρες. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Καθορίζει την ακτίνα θολώματος που εφαρμόζεται στις άκρες. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα του εφέ Soft Edge με την κληρονομική εφαρμογή.

**Επιστρέφει:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Καθορίζει εάν το συγκεκριμένο [SoftEdge](../../com.aspose.slides/softedge) είναι ίσο με το τρέχον [SoftEdge](../../com.aspose.slides/softedge).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [SoftEdge](../../com.aspose.slides/softedge) προς σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· διαφορετικά, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.