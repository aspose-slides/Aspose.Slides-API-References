---
title: Connector
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/connector/
---
## Κλάση Connector

  Αντιπροσωπεύει έναν connector.
 
### getConnectorLock {#getConnectorLock}

| Όνομα | Περιγραφή |
| --- | --- |
| getConnectorLock () | Επιστρέφει τους κλειδάρους του connector. Μόνο-ανάγνωση IConnectorLock. |

 **Επιστρέφει:**
[ConnectorLock](../connectorlock)


---


### getEndShapeConnectedTo {#getEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| getEndShapeConnectedTo () | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### getEndShapeConnectionSiteIndex {#getEndShapeConnectionSiteIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| getEndShapeConnectionSiteIndex () | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το end shape. Ανάγνωση/Εγγραφή long. |

 **Επιστρέφει:**
long

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν η τιμή είναι μικρότερη από EndShapeConnectedTo.ConnectionSiteCount |


---


### getShapeLock {#getShapeLock}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeLock () | Επιστρέφει τους κλειδάρους του shape. Μόνο-ανάγνωση IConnectorLock. |

 **Επιστρέφει:**
[ConnectorLock](../connectorlock)


---


### getShapeType {#getShapeType}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeType () | Επιστρέφει ή ορίζει τον τύπο AutoShape. Ανάγνωση/Εγγραφή ShapeType. |

 **Επιστρέφει:**
int


---


### getStartShapeConnectedTo {#getStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| getStartShapeConnectedTo () | Επιστρέφει ή ορίζει το shape για να προσαρτήσει την αρχή του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### getStartShapeConnectionSiteIndex {#getStartShapeConnectionSiteIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| getStartShapeConnectionSiteIndex () | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το start shape. Ανάγνωση/Εγγραφή long. |

 **Επιστρέφει:**
long

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν η τιμή είναι μικρότερη από StartShapeConnectedTo.ConnectionSiteCount |


---


### reroute {#reroute}

| Όνομα | Περιγραφή |
| --- | --- |
| reroute () | Αναπροσανατολίζει το connector ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των shapes που συνδέει. |

 **Επιστρέφει:**
void


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([Connector](../connector)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([Shape](../shape)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([SmartArtShape](../smartartshape)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([Table](../table)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([Ink](../ink)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([GeometryShape](../geometryshape)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([ZoomFrame](../zoomframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([VideoFrame](../videoframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([SmartArt](../smartart)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([GroupShape](../groupshape)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([InkActions](../inkactions)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([AutoShape](../autoshape)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([PictureFrame](../pictureframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([Chart](../chart)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([AudioFrame](../audioframe)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectedTo ([ZoomObject](../zoomobject)) | Επιστρέφει ή ορίζει το shape για να προσαρτήσει το άκρο του connector. Ανάγνωση/Εγγραφή IShape. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Εναίρεση που προβάλλεται όταν το συνδεδεμένο shape δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |
| setEndShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στο άκρο του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setEndShapeConnectionSiteIndex {#setEndShapeConnectionSiteIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndShapeConnectionSiteIndex (long) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/εγγραφή long. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν η τιμή είναι μικρότερη από το EndShapeConnectedTo.ConnectionSiteCount |

---


### setShapeType {#setShapeType}

| Όνομα | Περιγραφή |
| --- | --- |
| setShapeType (int) | Επιστρέφει ή ορίζει τον τύπο AutoShape. Ανάγνωση/εγγραφή ShapeType. |

**Επιστρέφει:**  
void  

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([Connector](../connector)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([Shape](../shape)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([SmartArtShape](../smartartshape)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([Table](../table)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([Ink](../ink)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([GeometryShape](../geometryshape)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([ZoomFrame](../zoomframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([VideoFrame](../videoframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([SmartArt](../smartart)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([GroupShape](../groupshape)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([InkActions](../inkactions)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([AutoShape](../autoshape)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([PictureFrame](../pictureframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([Chart](../chart)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([AudioFrame](../audioframe)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([ZoomObject](../zoomobject)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Επιστρέφει ή ορίζει το σχήμα που θα προσαρτηθεί στην αρχή του συνδέσμου. Ανάγνωση/εγγραφή IShape. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν το συνδεδεμένο σχήμα δεν έχει κανένα σημείο σύνδεσης (IShape.ConnectionSiteCount equals zero) |

---


### setStartShapeConnectionSiteIndex {#setStartShapeConnectionSiteIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| setStartShapeConnectionSiteIndex (long) | Επιστρέφει ή ορίζει το δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/εγγραφή long. |

**Επιστρέφει:**  
void  

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εκβάλλεται όταν η τιμή είναι μικρότερη από το StartShapeConnectedTo.ConnectionSiteCount |