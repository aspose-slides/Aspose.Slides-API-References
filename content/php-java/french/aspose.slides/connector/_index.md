---
title: Connector
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/connector/
---
## Connector classe

  Représente un connecteur.
 
### getConnectorLock {#getConnectorLock}

| Nom | Description |
| --- | --- |
| getConnectorLock () | Renvoie les verrous du connecteur. Lecture seule IConnectorLock. |

**Renvoie:**  
[ConnectorLock](../connectorlock)

---

### getEndShapeConnectedTo {#getEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| getEndShapeConnectedTo () | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### getEndShapeConnectionSiteIndex {#getEndShapeConnectionSiteIndex}

| Nom | Description |
| --- | --- |
| getEndShapeConnectionSiteIndex () | Renvoie ou définit l'index du site de connexion pour la forme d'extrémité. Lecture/écriture long. |

**Renvoie:**  
long

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la valeur est inférieure à EndShapeConnectedTo.ConnectionSiteCount |

---

### getShapeLock {#getShapeLock}

| Nom | Description |
| --- | --- |
| getShapeLock () | Renvoie les verrous de la forme. Lecture seule IConnectorLock. |

**Renvoie:**  
[ConnectorLock](../connectorlock)

---

### getShapeType {#getShapeType}

| Nom | Description |
| --- | --- |
| getShapeType () | Renvoie ou définit le type AutoShape. Lecture/écriture ShapeType. |

**Renvoie:**  
int

---

### getStartShapeConnectedTo {#getStartShapeConnectedTo}

| Nom | Description |
| --- | --- |
| getStartShapeConnectedTo () | Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### getStartShapeConnectionSiteIndex {#getStartShapeConnectionSiteIndex}

| Nom | Description |
| --- | --- |
| getStartShapeConnectionSiteIndex () | Renvoie ou définit l'index du site de connexion pour la forme de départ. Lecture/écriture long. |

**Renvoie:**  
long

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la valeur est inférieure à StartShapeConnectedTo.ConnectionSiteCount |

---

### reroute {#reroute}

| Nom | Description |
| --- | --- |
| reroute () | Redirige le connecteur afin qu'il prenne le chemin le plus court possible entre les formes qu'il relie. |

**Renvoie:**  
void

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([Connector](../connector)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([Shape](../shape)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([SmartArtShape](../smartartshape)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([Table](../table)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([Ink](../ink)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([GeometryShape](../geometryshape)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([ZoomFrame](../zoomframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([VideoFrame](../videoframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([SmartArt](../smartart)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([GroupShape](../groupshape)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([InkActions](../inkactions)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([AutoShape](../autoshape)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([PictureFrame](../pictureframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([Chart](../chart)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lançé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([AudioFrame](../audioframe)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lançé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

---

### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Nom | Description |
| --- | --- |
| setEndShapeConnectedTo ([ZoomObject](../zoomobject)) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**  
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lançé lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zéro) |

| setEndShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Renvoie ou définit la forme à attacher à l'extrémité du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setEndShapeConnectionSiteIndex {#setEndShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setEndShapeConnectionSiteIndex (long) | Renvoie ou définit l'index du site de connexion pour la forme de fin. Lecture/écriture long. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la valeur est inférieure à EndShapeConnectedTo.ConnectionSiteCount |

---

### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType (int) | Renvoie ou définit le type d'AutoShape. Lecture/écriture ShapeType. |

**Renvoie:**
void

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Connector](../connector)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Shape](../shape)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SmartArtShape](../smartartshape)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Table](../table)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Ink](../ink)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GeometryShape](../geometryshape)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([ZoomFrame](../zoomframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([VideoFrame](../videoframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SmartArt](../smartart)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GroupShape](../groupshape)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([InkActions](../inkactions)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([AutoShape](../autoshape)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([PictureFrame](../pictureframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Chart](../chart)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([AudioFrame](../audioframe)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([ZoomObject](../zoomobject)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Renvoie ou définit la forme à attacher au début du connecteur. Lecture/écriture IShape. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la forme connectée ne possède aucun site de connexion (IShape.ConnectionSiteCount equals zero) |

---

### setStartShapeConnectionSiteIndex {#setStartShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setStartShapeConnectionSiteIndex (long) | Renvoie ou définit l'index du site de connexion pour la forme de départ. Lecture/écriture long. |

**Renvoie:**
void

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Lancée lorsque la valeur est inférieure à StartShapeConnectedTo.ConnectionSiteCount |

---