---
title: IConnector
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει έναν σύνδεσμο.
type: docs
url: /el/com.aspose.slides/iconnector/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Αντιπροσωπεύει έναν σύνδεσμο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [getConnectorLock()](#getConnectorLock--) | Επιστρέφει τις κλειδώσεις του Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [reroute()](#reroute--) | Αναπροσανατολίζει το connector ώστε να ακολουθεί τη συντομότερη δυνατότερη διαδρομή μεταξύ των σχημάτων που συνδέει. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Επιστρέφει τις κλειδώσεις του Connector. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του connector. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του connector. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του connector. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του connector. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```


Αναπροσανατολίζει το connector ώστε να ακολουθεί τη συντομότερη δυνατότερη διαδρομή μεταξύ των σχημάτων που συνδέει.