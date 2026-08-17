---
title: IShapeCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de formes.
type: docs
url: /fr/com.aspose.slides/ishapecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Représente une collection de formes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [getParentGroup()](#getParentGroup--) | Obtient l'objet de forme de groupe parent pour la collection de formes. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crée un nouveau cadre Zoom de section et l'ajoute à la fin de la collection de formes. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crée un nouveau cadre Zoom de section et l'insère dans la collection de formes à l'index spécifié. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crée un nouveau cadre Zoom de résumé et l'ajoute à la fin de la collection de formes. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crée un nouveau cadre Zoom de résumé et l'insère dans la collection de formes à l'index spécifié. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crée un nouveau cadre audio lié à une piste CD et l'ajoute à la fin de la collection de formes. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crée un nouveau cadre audio lié à un fichier audio externe et l'ajoute à la fin de la collection de formes. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les formes. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Déplace la forme spécifiée vers une nouvelle position au sein de la collection de formes. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Déplace les formes spécifiées au sein de la collection de formes, en les plaçant à partir de l'index donné. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crée une nouvelle forme auto avec un formatage par défaut et l'ajoute à la fin de la collection de formes. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage du modèle par défaut. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crée une nouvelle forme auto rectangle pour héberger du contenu mathématique et l'ajoute à la fin de la collection de formes. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage du modèle par défaut. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié, en l'initialisant éventuellement avec le style de modèle par défaut. |
| [addGroupShape()](#addGroupShape--) | Crée un nouveau groupe de formes vide et l'ajoute à la fin de la collection de formes. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crée un nouveau groupe de formes, convertit l'image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crée un nouveau groupe de formes vide et l'insère dans la collection de formes à l'index spécifié. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crée une nouvelle forme connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crée une nouvelle forme connecteur et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crée une nouvelle forme connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crée une nouvelle forme connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crée un nouveau cadre d'image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crée une nouvelle table et l'ajoute à la fin de la collection de formes. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crée une nouvelle table et l'insère dans la collection de formes à l'index spécifié. |
| [removeAt(int index)](#removeAt-int-) | Supprime la forme à l'index spécifié de la collection de formes. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [clear()](#clear--) | Supprime toutes les formes de la collection de formes. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Obtient l'objet de forme de groupe parent pour la collection de formes. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

**Renvoie :**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |

**Renvoie :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |
| initWithSample | boolean | Vrai pour initialiser le nouveau graphique avec des données d'exemple de séries et des paramètres ; faux pour créer le graphique sans série et avec uniquement des paramètres minimaux, ce qui accélère la création. |

**Renvoie :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du cadre du diagramme, en points. |
| y | float | La coordonnée y du cadre du diagramme, en points. |
| width | float | La largeur du cadre du diagramme, en points. |
| height | float | La hauteur du cadre du diagramme, en points. |
| layoutType | int | Le type de disposition SmartArt. |

**Renvoie :**
[ISmartArt](../../com.aspose.slides/ismartart) - Le [ISmartArt](../../com.aspose.slides/ismartart) nouvellement créé.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à créer. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du nouveau graphique, en points. |
| height | float | La hauteur du nouveau graphique, en points. |
| index | int | L'index basé sur zéro à laquelle insérer le nouveau graphique dans la collection de formes. |

**Renvoie :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à créer. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du nouveau graphique, en points. |
| height | float | La hauteur du nouveau graphique, en points. |
| index | int | L'index basé sur zéro à laquelle insérer le nouveau graphique dans la collection de formes. |
| initWithSample | boolean | Vrai pour initialiser le nouveau graphique avec des données d'exemple de séries et des paramètres ; faux pour créer le graphique sans série et avec uniquement des paramètres minimaux, ce qui accélère la création. |
| initWithSample | boolean | True pour initialiser le nouveau graphique avec des données et paramètres d'échantillon ; false pour créer le graphique sans séries et uniquement avec des paramètres minimaux, ce qui accélère la création. |

**Retour :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Les informations de données OLE intégrées ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| className | java.lang.String | Le nom de classe de l'objet OLE. |
| path | java.lang.String | Le chemin vers le fichier lié.

Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent. |

**Retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'indice indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre d'objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Les informations de données OLE intégrées ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'indice indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre d'objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| className | java.lang.String | Le nom de classe de l'objet OLE. |
| path | java.lang.String | Le chemin vers le fichier lié.

Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent. |

**Retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom ; doit appartenir à cette présentation. |

**Retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom ; doit appartenir à cette présentation. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'image pour la diapositive référencée [IPPImage](../../com.aspose.slides/ippimage). |

**Retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'indice indiqué.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom. |

**Retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'indice indiqué.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'image pour la diapositive référencée [IPPImage](../../com.aspose.slides/ippimage). |

**Retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crée un nouveau cadre Zoom de section et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |

**Retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'[IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre Zoom de section. |

**Retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crée un nouveau cadre Zoom de section et l'insère dans la collection de formes à l'indice indiqué.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre Zoom de section. |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |

**Retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'insère dans la collection de formes à l'indice indiqué.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Section Zoom à l'index spécifié d'une collection
>  (suppose qu'il y a au moins deux sections dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro auquel insérer le cadre Zoom de section. |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'image à afficher dans le cadre Zoom de section. |

**Retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crée un nouveau cadre Zoom de résumé et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre Zoom de résumé, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de résumé, en points. |
| width | float | La largeur du nouveau cadre Zoom de résumé, en points. |
| height | float | La hauteur du nouveau cadre Zoom de résumé, en points. |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |
**Retour :**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Le nouveau [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).  
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}  
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```  

Crée un nouveau cadre Summary Zoom et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Summary Zoom à l'index spécifié d'une collection
>  (suppose qu'il y a au moins deux sections dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre Summary Zoom. |
| x | float | La coordonnée x du nouveau cadre Summary Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Summary Zoom, en points. |
| width | float | La largeur du nouveau cadre Summary Zoom, en points. |
| height | float | La hauteur du nouveau cadre Summary Zoom, en points. |

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |
**Retour :**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Le nouveau [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).  
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}  
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```  

Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier vidéo à incorporer. |

**Retour :**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le nouveau [IVideoFrame](../../com.aspose.slides/ivideoframe).  
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}  
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```  

Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Le [IVideo](../../com.aspose.slides/ivideo) à incorporer dans le cadre vidéo. |

**Retour :**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le nouveau [IVideoFrame](../../com.aspose.slides/ivideoframe).  
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}  
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```  

Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre vidéo. |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier vidéo à incorporer. |

**Retour :**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le nouveau [IVideoFrame](../../com.aspose.slides/ivideoframe).  
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}  
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```  

Crée un nouveau cadre audio lié à une piste CD et l'ajoute à la fin de la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}  
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```  

Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}  
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```  

Crée un nouveau cadre audio lié à un fichier audio externe et l'ajoute à la fin de la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier audio externe à lier. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}  
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```  

Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier audio externe à lier. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}  
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```  

Crée un nouveau cadre audio avec un fichier WAV incorporé et l'ajoute à la fin de la collection de formes. L'audio incorporé est ajouté à la collection Presentation.Audios.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | java.io.InputStream | Un flux d'entrée contenant des données audio WAV à incorporer. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}  
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```  

Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Une instance [IAudio](../../com.aspose.slides/iaudio) de la collection Presentation.Audios. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}  
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```  

Crée un nouveau cadre audio avec un fichier WAV incorporé et l'insère dans la collection de formes à l'index spécifié. L'audio incorporé est ajouté à la collection Presentation.Audios.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | java.io.InputStream | Un flux d'entrée contenant des données audio WAV à incorporer. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}  
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```  

Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à laquelle insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Une instance [IAudio](../../com.aspose.slides/iaudio) de la collection Presentation.Audios à incorporer. |

**Retour :**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le nouveau [IAudioFrame](../../com.aspose.slides/iaudioframe).  
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}  
```
public abstract int indexOf(IShape shape)
```  

Retourne l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La forme à localiser dans la collection. |

**Retour :**  
int - L'index basé sur zéro de la première occurrence de la forme dans la collection de formes si trouvée ; sinon, -1.  
### toArray() {#toArray--}  
```
public abstract IShape[] toArray()
```  

Crée et retourne un tableau contenant toutes les formes.

**Retour :**  
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape).  
### toArray(int startIndex, int count) {#toArray-int-int-}  
```
public abstract IShape[] toArray(int startIndex, int count)
```  

Crée et retourne un tableau contenant toutes les formes dans la plage spécifiée.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | L'index de la première forme à retourner. |
| count | int | Le nombre de formes à retourner. |

**Retour :**  
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape).  
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}  
```
public abstract void reorder(int index, IShape shape)
```  

Déplace la forme spécifiée vers une nouvelle position dans la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à déplacer dans la collection. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}  
```
public abstract void reorder(int index, IShape[] shapes)
```  

Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l'index indiqué.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la première forme spécifiée sera placée ; les formes suivantes suivent dans l'ordre fourni. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Une ou plusieurs instances [IShape](../../com.aspose.slides/ishape) à déplacer dans la collection. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}  
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```  

Crée une nouvelle forme auto avec le formatage par défaut et l'ajoute à la fin de la collection de formes.

**Paramètres :**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de la forme auto à ajouter.
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Renvoie:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Le nouveau [IAutoShape](../../com.aspose.slides/iautoshape) créé.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de la forme auto à ajouter. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (style simple, texte centré et nom non vide) à la nouvelle forme ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

**Renvoie:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Le nouveau [IAutoShape](../../com.aspose.slides/iautoshape) créé.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Crée une nouvelle forme auto rectangulaire pour héberger du contenu mathématique et l'ajoute à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Renvoie:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Le nouveau [IAutoShape](../../com.aspose.slides/iautoshape) créé.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index indiqué, en appliquant le style de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la nouvelle forme auto. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de la forme auto à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Renvoie:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Le nouveau [IAutoShape](../../com.aspose.slides/iautoshape) créé.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index indiqué, en l'initialisant éventuellement avec le style de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme auto. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de la forme auto à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (incluant un nom non vide, style simple et texte centré) ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

**Renvoie:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Le nouveau [IAutoShape](../../com.aspose.slides/iautoshape) créé.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Crée une nouvelle forme de groupe vide et l'ajoute à la fin de la collection de formes. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

**Renvoie:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le nouveau [IGroupShape](../../com.aspose.slides/igroupshape) créé.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crée une nouvelle forme de groupe, convertit l'image SVG spécifiée en formes individuelles et ajoute le groupe résultant à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Le [ISvgImage](../../com.aspose.slides/isvgimage) contenant le contenu vectoriel à convertir en formes. |
| x | float | La coordonnée x du cadre du groupe, en points. |
| y | float | La coordonnée y du cadre du groupe, en points. |
| width | float | La largeur du cadre du groupe, en points. |
| height | float | La hauteur du cadre du groupe, en points. |

**Renvoie:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le nouveau [IGroupShape](../../com.aspose.slides/igroupshape) créé.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Crée une nouvelle forme de groupe vide et l'insère dans la collection de formes à l'index indiqué. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer la forme de groupe. |

**Renvoie:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le nouveau [IGroupShape](../../com.aspose.slides/igroupshape) créé.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à ajouter. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

**Renvoie:**
[IConnector](../../com.aspose.slides/iconnector) - Le nouveau [IConnector](../../com.aspose.slides/iconnector) créé.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à créer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs par défaut des propriétés. |

**Renvoie:**
[IConnector](../../com.aspose.slides/iconnector) - Le nouveau [IConnector](../../com.aspose.slides/iconnector) créé.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index indiqué, en appliquant le style de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer le connecteur. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

**Renvoie:**
[IConnector](../../com.aspose.slides/iconnector) - Le nouveau [IConnector](../../com.aspose.slides/iconnector) créé.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index indiqué, en appliquant éventuellement le style de modèle par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer le connecteur. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs par défaut des propriétés. |

**Renvoie:**
[IConnector](../../com.aspose.slides/iconnector) - Le nouveau [IConnector](../../com.aspose.slides/iconnector) créé.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crée un nouveau cadre d'image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Spécifie le type de forme contenu dans [ShapeType](../../com.aspose.slides/shapetype), à l'exception de tous les types de lignes :<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | La coordonnée x du cadre d'image, en points. |
| y | float | La coordonnée y du cadre d'image, en points. |
| width | float | La largeur du cadre d'image, en points. |
| height | float | La hauteur du cadre d'image, en points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Le [IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre d'image. |

**Renvoie:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Le nouveau [IPictureFrame](../../com.aspose.slides/ipictureframe) créé.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index indiqué.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro auquel insérer le cadre d'image. |
| shapeType | int | Spécifie le type de forme contenu dans [ShapeType](../../com.aspose.slides/shapetype), à l'exception de tous les types de lignes :<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | La coordonnée x du cadre d'image, en points. |
| y | float | La coordonnée y du cadre d'image, en points. |
| width | float | La largeur du cadre d'image, en points. |
| height | float | La hauteur du cadre d'image, en points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Le [IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre d'image. |

**Renvoie:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Le nouveau [IPictureFrame](../../com.aspose.slides/ipictureframe) créé.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crée une nouvelle table et l'ajoute à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x de la table, en points. |
| y | float | La coordonnée y de la table, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes de la table, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes de la table, en points. |

**Renvoie:**
[ITable](../../com.aspose.slides/itable) - Le nouveau [ITable](../../com.aspose.slides/itable) créé.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Crée un nouveau tableau et l’insère dans la collection de formes à l’indice spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro où insérer le tableau. |
| x | float | La coordonnée x du tableau, en points. |
| y | float | La coordonnée y du tableau, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

**Valeur de retour:**
[ITable](../../com.aspose.slides/itable) - Le [ITable](../../com.aspose.slides/itable) nouvellement créé.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime la forme à l’indice spécifié de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de la forme à supprimer. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Supprime la première occurrence de la forme spécifiée de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à supprimer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les formes de la collection de formes.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur du  sourceShape .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Crée une copie de la forme spécifiée et l’ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille d’origine.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. La nouvelle forme conserve la largeur et la hauteur du  sourceShape .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’indice spécifié. La forme clonée conserve la position et la taille d’origine.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |

**Valeur de retour:**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.