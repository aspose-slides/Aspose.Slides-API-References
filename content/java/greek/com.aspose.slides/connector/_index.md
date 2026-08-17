---
title: Connector
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά έναν σύνδεσμο.
type: docs
url: /el/com.aspose.slides/connector/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Αναπαριστά έναν σύνδεσμο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [getConnectorLock()](#getConnectorLock--) | Επιστρέφει τις κλειδώσεις του σύνδεσμου. |
| [getShapeType()](#getShapeType--) | Επιστρέφει ή ορίζει τον τύπο AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Επιστρέφει ή ορίζει τον τύπο AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του σύνδεσμου. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του σύνδεσμου. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του σύνδεσμου. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του σύνδεσμου. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα. |
| [reroute()](#reroute--) | Ανακατευθύνει τον σύνδεσμο ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των σχημάτων που συνδέει. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Επιστρέφει τις κλειδώσεις του σύνδεσμου. Μόνο για ανάγνωση [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Επιστρέφει:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Επιστρέφει ή ορίζει τον τύπο AutoShape. Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Επιστρέφει:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Επιστρέφει ή ορίζει τον τύπο AutoShape. Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του σύνδεσμου. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του σύνδεσμου. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του σύνδεσμου. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το τέλος του σύνδεσμου. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Ανακατευθύνει τον σύνδεσμο ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των σχημάτων που συνδέει.