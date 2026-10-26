---
title: IConnector
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά έναν σύνδεσμο.
type: docs
url: /el/com.aspose.slides/iconnector/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Represents a connector.  
## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τα κλειδώματα του σχήματος. |
| [getConnectorLock()](#getConnectorLock--) | Επιστρέφει τα κλειδώματα του Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του συνδέσμου. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του συνδέσμου. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [reroute()](#reroute--) | Επαναδρομολογεί τον σύνδεσμο ώστε να ακολουθεί τη δυνατότατα μικρότερη διαδρομή μεταξύ των σχημάτων που συνδέει. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Επιστρέφει τα κλειδώματα του σχήματος. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Επιστρέφει τα κλειδώματα του Connector. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**  
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του συνδέσμου. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**  
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του συνδέσμου. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/Εγγραφή long.

**Επιστρέφει:**  
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/Εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/Εγγραφή long.

**Επιστρέφει:**  
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/Εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Επαναδρομολογεί τον σύνδεσμο ώστε να ακολουθεί τη δυνατότατα μικρότερη διαδρομή μεταξύ των σχημάτων που συνδέει.