---
title: ShapeCollection
second_title: Aspose.Sildes pour PHP via l'API Java
description: 
type: docs

url: /fr/aspose.slides/shapecollection/
---
## ShapeCollection classe

 Représente une collection de formes.
 
### addAudioFrameCD {#addAudioFrameCD}

| Nom | Description |
| --- | --- |
| addAudioFrameCD (float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

 **Retour :**
[AudioFrame](../audioframe)


---

### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Nom | Description |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, InputStream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l’ajoute à la fin de la collection de formes. L’audio intégré est ajouté à la collection Presentation.Audios. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | InputStream | Un flux d’entrée contenant les données audio WAV à intégrer. |

 **Retour :**
[AudioFrame](../audioframe)


---

### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Nom | Description |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, [Audio](../audio)) | Crée un nouveau cadre audio et l’ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [Audio](../audio) | Une instance IAudio de la collection Presentation.Audios. |

 **Retour :**
[AudioFrame](../audioframe)


---

### addAudioFrameLinked {#addAudioFrameLinked}

| Nom | Description |
| --- | --- |
| addAudioFrameLinked (float, float, float, float, String) | Crée un nouveau cadre audio lié à un fichier audio externe et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | String | Le chemin ou le nom du fichier audio externe à lier. |

 **Retour :**
[AudioFrame](../audioframe)


---

### addAutoShape {#addAutoShape}

| Nom | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float) | Crée une nouvelle forme automatique avec un formatage par défaut et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapeType | int | Le ShapeType de la forme automatique à ajouter. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

 **Retour :**
[AutoShape](../autoshape)


---

### addAutoShape {#addAutoShape}

| Nom | Description |
| --- | --- |
| addAutoShape (int, float, float, float, float, boolean) | Crée une nouvelle forme automatique et l’ajoute à la fin de la collection de formes, en l’initialisant éventuellement avec le formatage du modèle par défaut. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapeType | int | Le ShapeType de la forme automatique à ajouter. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (style simple, texte centré et nom non vide) à la nouvelle forme ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

 **Retour :**
[AutoShape](../autoshape)


---

### addChart {#addChart}

| Nom | Description |
| --- | --- |
| addChart (int, float, float, float, float) | Crée un nouveau graphique, l’initialise avec des données de séries d’exemple et des paramètres, puis l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |

 **Retour :**
[Chart](../chart)


---

### addChart {#addChart}

| Nom | Description |
| --- | --- |
| addChart (int, float, float, float, float, boolean) | Crée un nouveau graphique, l’initialise avec des données de séries d’exemple et des paramètres, puis l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |
| initWithSample | boolean | True pour initialiser le nouveau graphique avec des données de séries d’exemple et des paramètres ; false pour créer le graphique sans séries et avec seulement les paramètres minimaux, ce qui accélère la création. |

 **Retour :**
[Chart](../chart)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Table](../table), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | La forme à cloner. |
| x | float | La coordonnée x du nouveau cadre de forme, en points. |
| y | float | La coordonnée y du nouveau cadre de forme, en points. |
| width | float | La largeur du nouveau cadre de forme, en points. |
| height | float | La hauteur du nouveau cadre de forme, en points. |

 **Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | La forme à cloner. |

| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float, float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Connector](../connector), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Shape](../shape), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Table](../table), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Ink](../ink), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Chart](../chart), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Connector](../connector)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Shape](../shape)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Table](../table)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Table](../table) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Ink](../ink)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GeometryShape](../geometryshape)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille de l'original. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | L'IShape à cloner. |
**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([VideoFrame](../videoframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SmartArt](../smartart)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([GroupShape](../groupshape)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([InkActions](../inkactions)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AutoShape](../autoshape)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([PictureFrame](../pictureframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | L'IShape à cloner. |

**Valeur retournée:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([Chart](../chart)) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres:**
| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([AudioFrame](../audioframe)) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([ZoomObject](../zoomobject)) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Nom | Description |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram)) | Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | L'IShape à cloner. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addConnector {#addConnector}

| Nom | Description |
| --- | --- |
| addConnector (int, float, float, float, float) | Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapeType | int | Le ShapeType de la forme connecteur à ajouter. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

**Retour :**
[Connector](../connector)

---

### addConnector {#addConnector}

| Nom | Description |
| --- | --- |
| addConnector (int, float, float, float, float, boolean) | Crée une nouvelle forme de connecteur et l’ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapeType | int | Le ShapeType de la forme connecteur à créer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriétés par défaut. |

**Retour :**
[Connector](../connector)

---

### addGroupShape {#addGroupShape}

| Nom | Description |
| --- | --- |
| addGroupShape () | Crée une nouvelle forme de groupe vide et l’ajoute à la fin de la collection de formes. Le cadre du groupe s’ajustera automatiquement pour contenir toutes les formes ajoutées. |

**Retour :**
[GroupShape](../groupshape)

---

### addGroupShape {#addGroupShape}

| Nom | Description |
| --- | --- |
| addGroupShape ([SvgImage](../svgimage), float, float, float, float) | Crée une nouvelle forme de groupe, convertit l’image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | L'ISvgImage contenant le contenu vectoriel à convertir en formes. |
| x | float | La coordonnée x du cadre du groupe, en points. |
| y | float | La coordonnée y du cadre du groupe, en points. |
| width | float | La largeur du cadre du groupe, en points. |
| height | float | La hauteur du cadre du groupe, en points. |

**Retour :**
[GroupShape](../groupshape)

---

### addMathShape {#addMathShape}

| Nom | Description |
| --- | --- |
| addMathShape (float, float, float, float) | Crée une nouvelle forme rectangle auto pour accueillir du contenu mathématique et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Retour :**
[AutoShape](../autoshape)

---

### addOleObjectFrame {#addOleObjectFrame}

| Nom | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Crée un nouveau cadre d’objet OLE et l’ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur de la nouvelle trame OLE, en points. |
| height | float | La hauteur de la nouvelle trame OLE, en points. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Les informations sur les données OLE incorporées ( IOleEmbeddedDataInfo). |

**Retour :**
[OleObjectFrame](../oleobjectframe)

---

### addOleObjectFrame {#addOleObjectFrame}

| Nom | Description |
| --- | --- |
| addOleObjectFrame (float, float, float, float, String, String) | Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame OLE, en points. |
| y | float | La coordonnée y de la nouvelle trame OLE, en points. |
| width | float | La largeur de la nouvelle trame OLE, en points. |
| height | float | La hauteur de la nouvelle trame OLE, en points. |
| className | String | Le nom de classe de l'objet OLE. |
| path | String | Le chemin vers le fichier lié. Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un autre répertoire. |

**Retour :**
[OleObjectFrame](../oleobjectframe)

---

### addPictureFrame {#addPictureFrame}

| Nom | Description |
| --- | --- |
| addPictureFrame (int, float, float, float, float, [PPImage](../ppimage)) | Crée une nouvelle trame d’image contenant l’image spécifiée et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shapeType | int | Spécifie le type de forme contenu dans ShapeType, à l’exception de tous les types de lignes : ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | La coordonnée x de la trame d’image, en points. |
| y | float | La coordonnée y de la trame d’image, en points. |
| width | float | La largeur de la trame d’image, en points. |
| height | float | La hauteur de la trame d’image, en points. |
| image | [PPImage](../ppimage) | L’IPPImage à afficher dans la trame d’image. |

**Retour :**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)

---

### addSectionZoomFrame {#addSectionZoomFrame}

| Nom | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section)) | Crée une nouvelle trame Section Zoom et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame Section Zoom, en points. |
| y | float | La coordonnée y de la nouvelle trame Section Zoom, en points. |
| width | float | La largeur de la nouvelle trame Section Zoom, en points. |
| height | float | La hauteur de la nouvelle trame Section Zoom, en points. |
| section | [Section](../section) | Le ISection référencé par la trame Section Zoom ; il doit appartenir à cette présentation et contenir au moins une diapositive. |

**Retour :**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Levée si la section référencée n’appartient pas à la présentation actuelle ou ne contient aucune diapositive. |

---

### addSectionZoomFrame {#addSectionZoomFrame}

| Nom | Description |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Crée une nouvelle trame Section Zoom avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame Section Zoom, en points. |
| y | float | La coordonnée y de la nouvelle trame Section Zoom, en points. |
| width | float | La largeur de la nouvelle trame Section Zoom, en points. |
| height | float | La hauteur de la nouvelle trame Section Zoom, en points. |
| section | [Section](../section) | Le ISection référencé par la trame Section Zoom ; il doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [PPImage](../ppimage) | L’IPPImage à afficher dans la trame Section Zoom. |

**Retour :**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Levée si la section référencée n’appartient pas à la présentation actuelle ou ne contient aucune diapositive. |

---

### addSmartArt {#addSmartArt}

| Nom | Description |
| --- | --- |
| addSmartArt (float, float, float, float, int) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du cadre du diagramme, en points. |
| y | float | La coordonnée y du cadre du diagramme, en points. |
| width | float | La largeur du cadre du diagramme, en points. |
| height | float | La hauteur du cadre du diagramme, en points. |
| layoutType | int | Le type de mise en page SmartArt. |

**Retour :**
[SmartArt](../smartart)

---

### addSummaryZoomFrame {#addSummaryZoomFrame}

| Nom | Description |
| --- | --- |
| addSummaryZoomFrame (float, float, float, float) | Crée une nouvelle trame Summary Zoom et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame Summary Zoom, en points. |
| y | float | La coordonnée y de la nouvelle trame Summary Zoom, en points. |
| width | float | La largeur de la nouvelle trame Summary Zoom, en points. |
| height | float | La hauteur de la nouvelle trame Summary Zoom, en points. Cette méthode crée un nouveau Summary Zoom et y insère une collection d’objets pour toutes les sections de cette présentation. |

**Retour :**
[SummaryZoomFrame](../summaryzoomframe)

**Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Levée s’il n’y a aucune section dans la présentation, ou si la diapositive cible n’appartient à aucune section. |

---

### addTable {#addTable}

| Nom | Description |
| --- | --- |
| addTable (float, float, double[], double[]) | Crée un nouveau tableau et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du tableau, en points. |
| y | float | La coordonnée y du tableau, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

**Retour :**
[Table](../table)

---

### addVideoFrame {#addVideoFrame}

| Nom | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, String) | Crée une nouvelle trame vidéo et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame vidéo, en points. |
| y | float | La coordonnée y de la nouvelle trame vidéo, en points. |
| width | float | La largeur de la nouvelle trame vidéo, en points. |
| height | float | La hauteur de la nouvelle trame vidéo, en points. |
| fname | String | Le chemin ou le nom du fichier vidéo à incorporer. |

**Retour :**
[VideoFrame](../videoframe)

---

### addVideoFrame {#addVideoFrame}

| Nom | Description |
| --- | --- |
| addVideoFrame (float, float, float, float, [Video](../video)) | Crée une nouvelle trame vidéo et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame vidéo, en points. |
| y | float | La coordonnée y de la nouvelle trame vidéo, en points. |
| width | float | La largeur de la nouvelle trame vidéo, en points. |
| height | float | La hauteur de la nouvelle trame vidéo, en points. |
| video | [Video](../video) | Le IVideo à incorporer dans la trame vidéo. |

**Retour :**
[VideoFrame](../videoframe)

---

### addZoomFrame {#addZoomFrame}

| Nom | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide)) | Crée une nouvelle trame Zoom et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame Zoom, en points. |
| y | float | La coordonnée y de la nouvelle trame Zoom, en points. |
| width | float | La largeur de la nouvelle trame Zoom, en points. |
| height | float | La hauteur de la nouvelle trame Zoom, en points. |
| slide | [Slide](../slide) | Le ISlide référencé par la trame Zoom ; il doit appartenir à cette présentation. |

**Retour :**
[ZoomFrame](../zoomframe)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Levée si la diapositive référencée n’appartient pas à la présentation actuelle. |

---

### addZoomFrame {#addZoomFrame}

| Nom | Description |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Crée une nouvelle trame Zoom et l'ajoute à la fin de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la nouvelle trame Zoom, en points. |
| y | float | La coordonnée y de la nouvelle trame Zoom, en points. |
| width | float | La largeur de la nouvelle trame Zoom, en points. |
| height | float | La hauteur de la nouvelle trame Zoom, en points. |
| slide | [Slide](../slide) | Le ISlide référencé par la trame Zoom ; il doit appartenir à cette présentation. |
| image | [PPImage](../ppimage) | L’image pour la diapositive référencée IPPImage. |

**Retour :**
[ZoomFrame](../zoomframe)

**Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | Levée si la diapositive référencée n’appartient pas à la présentation actuelle. |

---

### clear {#clear}

| Nom | Description |
| --- | --- |
| clear () | Supprime toutes les formes de la collection de formes. |

**Retour :**
void

---

### getParentGroup {#getParentGroup}

| Nom | Description |
| --- | --- |
| getParentGroup () | Obtient l’objet de forme de groupe parent pour la collection de formes. Lecture seule IGroupShape. |

**Retour :**
[GroupShape](../groupshape)

---

### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Retourne une racine de synchronisation. Lecture seule Object. |

**Retour :**
Object

---

### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l’élément à l’index spécifié. Lecture seule IShape. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([GraphicalObject](../graphicalobject)) | Retourne l’index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | La forme à rechercher dans la collection. |

**Retour :**
int

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Connector](../connector)) | Retourne l’index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | La forme à rechercher dans la collection. |

**Retour :**
int

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Shape](../shape)) | Retourne l’index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | La forme à rechercher dans la collection. |

**Retour :**
int

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([SmartArtShape](../smartartshape)) | Retourne l’index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | La forme à rechercher dans la collection. |

**Retour :**
int

---

### indexOf {#indexOf}

| Nom | Description |
| --- | --- |
| indexOf ([Table](../table)) | Retourne l’index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

| shape | [Table](../table) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Ink](../ink)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomFrame](../summaryzoomframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GeometryShape](../geometryshape)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomFrame](../zoomframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([OleObjectFrame](../oleobjectframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([VideoFrame](../videoframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArt](../smartart)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GroupShape](../groupshape)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([InkActions](../inkactions)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AutoShape](../autoshape)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([PictureFrame](../pictureframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SectionZoomFrame](../sectionzoomframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Chart](../chart)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AudioFrame](../audioframe)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomObject](../zoomobject)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([LegacyDiagram](../legacydiagram)) | Renvoie l’indice basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | La forme à rechercher dans la collection. |

**Renvoie :**
int


---


### insertAudioFrameCD {#insertAudioFrameCD}

| Name | Description |
| --- | --- |
| insertAudioFrameCD (int, float, float, float, float) | Crée un nouveau cadre audio lié à une piste CD et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

**Renvoie :**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, InputStream) | Crée un nouveau cadre audio avec un fichier WAV intégré et l’insère dans la collection de formes à l’indice spécifié. L’audio intégré est ajouté à la collection Presentation.Audios. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | InputStream | Un flux d’entrée contenant des données audio WAV à intégrer. |

**Renvoie :**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, [Audio](../audio)) | Crée un nouveau cadre audio et l’insère dans la collection de formes à l’indice spécifié en utilisant un objet audio existant de la liste Presentation.Audios. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [Audio](../audio) | Une instance IAudio de la collection Presentation.Audios à intégrer. |

**Renvoie :**
[AudioFrame](../audioframe)


---


### insertAudioFrameLinked {#insertAudioFrameLinked}

| Name | Description |
| --- | --- |
| insertAudioFrameLinked (int, float, float, float, float, String) | Crée un nouveau cadre audio lié à un fichier audio externe et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | String | Le chemin ou le nom du fichier audio externe à lier. |

**Renvoie :**
[AudioFrame](../audioframe)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float) | Crée une nouvelle auto shape et l’insère dans la collection de formes à l’indice spécifié, en appliquant le formatage de modèle par défaut. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer la nouvelle auto shape. |
| shapeType | int | Le ShapeType de l’auto shape à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Renvoie :**
[AutoShape](../autoshape)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float, boolean) | Crée une nouvelle auto shape et l’insère dans la collection de formes à l’indice spécifié, en l’initialisant éventuellement avec le style de modèle par défaut. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro à lequel insérer l’auto shape. |
| shapeType | int | Le ShapeType de l’auto shape à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | Vrai pour appliquer le style de modèle par défaut (y compris un nom non vide, un style simple et du texte centré) ; faux pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

**Renvoie :**
[AutoShape](../autoshape)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int) | Crée un nouveau chart, l’initialise avec des données et paramètres d’exemple, et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Le type de chart à créer. |
| x | float | La coordonnée x du nouveau chart, en points. |
| y | float | La coordonnée y du nouveau chart, en points. |
| width | float | La largeur du nouveau chart, en points. |
| height | float | La hauteur du nouveau chart, en points. |
| index | int | L’indice basé sur zéro à lequel insérer le nouveau chart dans la collection de formes. |

**Renvoie :**
[Chart](../chart)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int, boolean) | Crée un nouveau chart, l’initialise avec des données et paramètres d’exemple, et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres :**
| Nom | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à créer. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du nouveau graphique, en points. |
| height | float | La hauteur du nouveau graphique, en points. |
| index | int | L'indice basé sur zéro à lequel insérer le nouveau graphique dans la collection de formes. |
| initWithSample | boolean | True pour initialiser le nouveau graphique avec des données et paramètres d'exemple ; false pour créer le graphique sans séries et uniquement avec les paramètres minimaux, ce qui rend la création plus rapide. |

**Retour:**  
[Chart](../chart)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [GraphicalObject](../graphicalobject) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [Connector](../connector) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [Shape](../shape) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SmartArtShape](../smartartshape) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [Table](../table) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [Ink](../ink) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [GeometryShape](../geometryshape) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [ZoomFrame](../zoomframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float, float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [VideoFrame](../videoframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [SmartArt](../smartart) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [GroupShape](../groupshape) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [InkActions](../inkactions) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [AutoShape](../autoshape) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [PictureFrame](../pictureframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [Chart](../chart) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [AudioFrame](../audioframe) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [ZoomObject](../zoomobject) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float, float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [LegacyDiagram](../legacydiagram) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [GraphicalObject](../graphicalobject) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

**Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---  

### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme clonée. |
| sourceShape | [Connector](../connector) | L'IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [Shape](../shape) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [SmartArtShape](../smartartshape) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Table](../table), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [Table](../table) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [Ink](../ink) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [GeometryShape](../geometryshape) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [ZoomFrame](../zoomframe) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer la forme clonée. |
| sourceShape | [VideoFrame](../videoframe) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [SmartArt](../smartart) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [GroupShape](../groupshape) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à lequel insérer la forme clonée. |
| sourceShape | [InkActions](../inkactions) | L’IShape à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

 **Retour:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [AutoShape](../autoshape) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [PictureFrame](../pictureframe) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [Chart](../chart) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [AudioFrame](../audioframe) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [ZoomObject](../zoomobject) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de sourceShape. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [LegacyDiagram](../legacydiagram) | L'IShape à dupliquer. |
| x | float | La coordonnée x du cadre de la forme dupliquée, en points. |
| y | float | La coordonnée y du cadre de la forme dupliquée, en points. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [GraphicalObject](../graphicalobject) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Connector](../connector)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [Connector](../connector) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Shape](../shape)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [Shape](../shape) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [SmartArtShape](../smartartshape) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Table](../table)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [Table](../table) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [Ink](../ink)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [Ink](../ink) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel insérer la forme dupliquée. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | L'IShape à dupliquer. |

**Valeur de retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Nom | Description |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape)) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme dupliquée conserve la position et la taille d'origine. |

**Paramètres :**
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [GeometryShape](../geometryshape) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [ZoomFrame](../zoomframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [VideoFrame](../videoframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SmartArt](../smartart)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SmartArt](../smartart) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [GroupShape](../groupshape) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [InkActions](../inkactions)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [InkActions](../inkactions) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [AutoShape](../autoshape) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [PictureFrame](../pictureframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Chart](../chart)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [Chart](../chart) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [AudioFrame](../audioframe) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [ZoomObject](../zoomobject) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram)) | Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué. La forme clonée conserve la position et la taille d’origine. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme clonée. |
| sourceShape | [LegacyDiagram](../legacydiagram) | L’IShape à cloner. |

 **Renvoie:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float) | Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’index indiqué, en appliquant le style de modèle par défaut. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme de connecteur. |
| shapeType | int | Le ShapeType de la forme de connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

 **Renvoie:**  
[Connector](../connector)

---


### insertConnector {#insertConnector}

| Name | Description |
| --- | --- |
| insertConnector (int, int, float, float, float, float, boolean) | Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’index indiqué, en appliquant éventuellement le style de modèle par défaut. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro à lequel insérer la forme de connecteur. |
| shapeType | int | Le ShapeType de la forme de connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| boolean |  |  |

| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriété par défaut. |

**Renvoie :**
[Connector](../connector)

---

### insertGroupShape {#insertGroupShape}

| Name | Description |
| --- | --- |
| insertGroupShape (int) | Crée une nouvelle forme de groupe vide et l’insère dans la collection de formes à l’index spécifié. Le cadre du groupe s’ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer la forme de groupe. |

**Renvoie :**
[GroupShape](../groupshape)

---

### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Crée un nouveau cadre d’objet OLE et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre d’objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Les informations de données OLE incorporées (IOleEmbeddedDataInfo). |

**Renvoie :**
[OleObjectFrame](../oleobjectframe)

---

### insertOleObjectFrame {#insertOleObjectFrame}

| Name | Description |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, String, String) | Crée un nouveau cadre d’objet OLE et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre d’objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| className | String | Le nom de classe de l’objet OLE. |
| path | String | Le chemin vers le fichier lié. Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l’ouverture de la présentation depuis un répertoire différent. |

**Renvoie :**
[OleObjectFrame](../oleobjectframe)

---

### insertPictureFrame {#insertPictureFrame}

| Name | Description |
| --- | --- |
| insertPictureFrame (int, int, float, float, float, float, [PPImage](../ppimage)) | Crée un nouveau cadre d’image contenant l’image spécifiée et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre d’image. |
| shapeType | int | Spécifie le type de forme contenu dans ShapeType, à l’exception de tous les types de lignes : ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | La coordonnée x du cadre d’image, en points. |
| y | float | La coordonnée y du cadre d’image, en points. |
| width | float | La largeur du cadre d’image, en points. |
| height | float | La hauteur du cadre d’image, en points. |
| image | [PPImage](../ppimage) | L’IPPImage à afficher dans le cadre d’image. |

**Renvoie :**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)

---

### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section)) | Crée un nouveau cadre Section Zoom et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre Section Zoom. |
| x | float | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | float | La largeur du nouveau cadre Section Zoom, en points. |
| height | float | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [Section](../section) | L’ISection référencée par le cadre Section Zoom ; elle doit appartenir à cette présentation et contenir au moins une diapositive. |

**Renvoie :**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Exception**

| Error | Condition |
| --- | --- |
| ArgumentException | Lancée si la section référencée n’appartient pas à la présentation courante ou ne contient aucune diapositive. |

---

### insertSectionZoomFrame {#insertSectionZoomFrame}

| Name | Description |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Crée un nouveau cadre Section Zoom avec une image prédéfinie et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre Section Zoom. |
| x | float | La coordonnée x du nouveau cadre Section Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Section Zoom, en points. |
| width | float | La largeur du nouveau cadre Section Zoom, en points. |
| height | float | La hauteur du nouveau cadre Section Zoom, en points. |
| section | [Section](../section) | L’ISection référencée par le cadre Section Zoom ; elle doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [PPImage](../ppimage) | L’image à afficher dans le cadre Section Zoom. |

**Renvoie :**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Exception**

| Error | Condition |
| --- | --- |
| ArgumentException | Lancée si la section référencée n’appartient pas à la présentation courante ou ne contient aucune diapositive. |

---

### insertSummaryZoomFrame {#insertSummaryZoomFrame}

| Name | Description |
| --- | --- |
| insertSummaryZoomFrame (int, float, float, float, float) | Crée un nouveau cadre Summary Zoom et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre Summary Zoom. |
| x | float | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | float | La largeur du nouveau cadre Summary Zoom, en points. |
| height | float | La hauteur du nouveau cadre Summary Zoom, en points. Ce mode crée un cadre Summary Zoom qui agrège les liens de résumé pour toutes les sections de la présentation. |

**Renvoie :**
[SummaryZoomFrame](../summaryzoomframe)

**Exception**

| Error | Condition |
| --- | --- |
| PptxEditException | Lancée si la présentation ne contient aucune section, ou si la diapositive cible n’appartient à aucune section. |

---

### insertTable {#insertTable}

| Name | Description |
| --- | --- |
| insertTable (int, float, float, double[], double[]) | Crée une nouvelle table et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer la table. |
| x | float | La coordonnée x de la table, en points. |
| y | float | La coordonnée y de la table, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes de la table, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes de la table, en points. |

**Renvoie :**
[Table](../table)

---

### insertVideoFrame {#insertVideoFrame}

| Name | Description |
| --- | --- |
| insertVideoFrame (int, float, float, float, float, String) | Crée un nouveau cadre vidéo et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre vidéo. |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| fname | String | Le chemin ou le nom du fichier vidéo à incorporer. |

**Renvoie :**
[VideoFrame](../videoframe)

---

### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide)) | Crée un nouveau cadre Zoom et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [Slide](../slide) | L’ISlide référencée par le cadre Zoom. |

**Renvoie :**
[ZoomFrame](../zoomframe)

**Exception**

| Error | Condition |
| --- | --- |
| ArgumentException | Lancée si la diapositive référencée n’appartient pas à la présentation courante. |

---

### insertZoomFrame {#insertZoomFrame}

| Name | Description |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Crée un nouveau cadre Zoom avec une image prédéfinie et l’insère dans la collection de formes à l’index spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | L’index de base zéro à laquelle insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [Slide](../slide) | L’ISlide référencée par le cadre Zoom. |
| image | [PPImage](../ppimage) | L’image pour la diapositive référencée IPPImage. |

**Renvoie :**
[ZoomFrame](../zoomframe)

**Exception**

| Error | Condition |
| --- | --- |
| ArgumentException | Lancée si la diapositive référencée n’appartient pas à la présentation courante. |

---

### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Booléen en lecture seule. |

**Renvoie :**
boolean

---

### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Renvoie un itérateur qui parcourt la collection. |

**Renvoie :**



---

### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l’ensemble de la collection. |

**Renvoie :**



---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([GraphicalObject](../graphicalobject)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | L’IShape à supprimer. |

**Renvoie :**
void

---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Connector](../connector)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Connector](../connector) | L’IShape à supprimer. |

**Renvoie :**
void

---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Shape](../shape)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Shape](../shape) | L’IShape à supprimer. |

**Renvoie :**
void

---
| --- | --- |
| remove ([SmartArtShape](../smartartshape)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Table](../table)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [Table](../table) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Ink](../ink)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([SummaryZoomFrame](../summaryzoomframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([GeometryShape](../geometryshape)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([SummaryZoomSection](../summaryzoomsection)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([ZoomFrame](../zoomframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([OleObjectFrame](../oleobjectframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([VideoFrame](../videoframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([SmartArt](../smartart)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([GroupShape](../groupshape)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([InkActions](../inkactions)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([AutoShape](../autoshape)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([PictureFrame](../pictureframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([SectionZoomFrame](../sectionzoomframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([Chart](../chart)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([AudioFrame](../audioframe)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([ZoomObject](../zoomobject)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | L'IShape à supprimer. |

**Retour :**
void


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove ([LegacyDiagram](../legacydiagram)) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | L'IShape à supprimer. |

**Retour :**
void


---


### removeAt {#removeAt}

| Nom | Description |
| --- | --- |
| removeAt (int) | Supprime la forme à l'index spécifié de la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de la forme à supprimer. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [GraphicalObject](../graphicalobject)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [GraphicalObject](../graphicalobject) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Connector](../connector)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [Connector](../connector) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Shape](../shape)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [Shape](../shape) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [SmartArtShape](../smartartshape)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [SmartArtShape](../smartartshape) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Table](../table)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [Table](../table) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Ink](../ink)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [Ink](../ink) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [SummaryZoomFrame](../summaryzoomframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [GeometryShape](../geometryshape)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [GeometryShape](../geometryshape) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [SummaryZoomSection](../summaryzoomsection)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [SummaryZoomSection](../summaryzoomsection) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [ZoomFrame](../zoomframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [ZoomFrame](../zoomframe) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [OleObjectFrame](../oleobjectframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [OleObjectFrame](../oleobjectframe) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [VideoFrame](../videoframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [VideoFrame](../videoframe) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [SmartArt](../smartart)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [SmartArt](../smartart) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [GroupShape](../groupshape)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [GroupShape](../groupshape) | L'IShape à déplacer dans la collection. |

**Retour :**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [InkActions](../inkactions)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres :**
| indice | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [InkActions](../inkactions) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [AutoShape](../autoshape)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [AutoShape](../autoshape) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [PictureFrame](../pictureframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [PictureFrame](../pictureframe) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [SectionZoomFrame](../sectionzoomframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [SectionZoomFrame](../sectionzoomframe) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [Chart](../chart)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [Chart](../chart) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [AudioFrame](../audioframe)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [AudioFrame](../audioframe) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [ZoomObject](../zoomobject)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [ZoomObject](../zoomobject) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, [LegacyDiagram](../legacydiagram)) | Déplace la forme spécifiée vers une nouvelle position dans la collection de formes. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [LegacyDiagram](../legacydiagram) | L'IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### reorder {#reorder}

| Nom | Description |
| --- | --- |
| reorder (int, com.aspose.slides.IShape[]) | Déplace les formes spécifiées dans la collection de formes, les plaçant à partir de l'index donné. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la première forme spécifiée sera placée ; les formes suivantes suivent dans l'ordre fourni. |
| shapes | com.aspose.slides.IShape[] | Une ou plusieurs instances IShape à déplacer dans la collection. |

**Renvoie:**
void


---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |

**Renvoie:**
int


---


### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray () | Crée et renvoie un tableau contenant toutes les formes. |

**Renvoie:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### toArray {#toArray}

| Nom | Description |
| --- | --- |
| toArray (int, int) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| startIndex | int | L'index de la première forme à renvoyer. |
| count | int | Le nombre de formes à renvoyer. |

**Renvoie:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)