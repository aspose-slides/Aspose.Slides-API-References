---
title: Glow
second_title: Aspose.Slides για το Java API Reference
description: Αντιπροσωπεύει ένα εφέ Glow στο οποίο προστίθεται ένα θολό περίγραμμα χρώματος έξω από τις άκρες του αντικειμένου.
type: docs
url: /el/com.aspose.slides/glow/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Αναπαριστά ένα εφέ Glow, στο οποίο προστίθεται ένα θολό περίγραμμα χρώματος γύρω από τις άκρες του αντικειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Ακτίνα. |
| [setRadius(double value)](#setRadius-double-) | Ακτίνα. |
| [getColor()](#getColor--) | Μορφή χρώματος. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Glow με την κληρονόμηση εφαρμοσμένη. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο [Glow](../../com.aspose.slides/glow) είναι ίσο με το τρέχον [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Ακτίνα. Ανάγνωση/εγγραφή  double .

**Επιστρέφει:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Ακτίνα. Ανάγνωση/εγγραφή  double .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Μορφή χρώματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Λαμβάνει τα αποτελεσματικά δεδομένα εφέ Glow με την κληρονόμηση εφαρμοσμένη.

**Επιστρέφει:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - Ένα [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent\_Immediate. Μόνο ανάγνωση IDOMObject.

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


Καθορίζει εάν το καθορισμένο [Glow](../../com.aspose.slides/glow) είναι ίσο με το τρέχον [Glow](../../com.aspose.slides/glow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το [Glow](../../com.aspose.slides/glow) για σύγκριση. |

**Επιστρέφει:**
boolean - true εάν τα αντικείμενα είναι ίσα· αλλιώς, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο.

**Επιστρέφει:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο.