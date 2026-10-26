---
title: ShapeCollection
second_title: Référence d'API Aspose.Slides pour Android via Java
description: Représente une collection de formes.
type: docs
url: /fr/com.aspose.slides/shapecollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Représente une collection de formes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'insère dans la collection de formes à l'index spécifié. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crée un nouveau cadre Zoom et le ajoute à la fin de la collection de formes. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom et le ajoute à la fin de la collection de formes. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crée un nouveau cadre Zoom de section et le ajoute à la fin de la collection de formes. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom de section avec une image prédéfinie et le ajoute à la fin de la collection de formes. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crée un nouveau cadre Zoom de section et l'insère dans la collection de formes à l'index spécifié. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crée un nouveau cadre Zoom de résumé et le ajoute à la fin de la collection de formes. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crée un nouveau cadre Zoom de résumé et l'insère dans la collection de formes à l'index spécifié. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crée un nouveau cadre d'objet OLE et le ajoute à la fin de la collection de formes. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crée un nouveau cadre d'objet OLE et le ajoute à la fin de la collection de formes. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crée un nouveau cadre vidéo et le ajoute à la fin de la collection de formes. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crée un nouveau cadre vidéo et le ajoute à la fin de la collection de formes. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crée un nouveau cadre audio lié à une piste CD et le ajoute à la fin de la collection de formes. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crée un nouveau cadre audio lié à un fichier audio externe et le ajoute à la fin de la collection de formes. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crée un nouveau cadre audio avec un fichier WAV intégré et le ajoute à la fin de la collection de formes. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crée un nouveau cadre audio et le ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crée un nouveau cadre audio et l'insère à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les formes. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Déplace la forme spécifiée vers une nouvelle position au sein de la collection de formes. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Déplace les formes spécifiées au sein de la collection de formes, en les plaçant à partir de l'index donné. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crée une nouvelle auto-forme avec un formatage par défaut et l'ajoute à la fin de la collection de formes. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crée une nouvelle auto-forme et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage de modèle par défaut. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crée une nouvelle auto-forme rectangulaire pour accueillir du contenu mathématique et l'ajoute à la fin de la collection de formes. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crée une nouvelle auto-forme et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crée une nouvelle auto-forme et l'insère dans la collection de formes à l'index spécifié, en l'initialisant éventuellement avec le style de modèle par défaut. |
| [addGroupShape()](#addGroupShape--) | Crée un nouveau groupe de formes vide et l'ajoute à la fin de la collection de formes. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crée un nouveau groupe de formes, convertit l'image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crée un nouveau groupe de formes vide et l'insère dans la collection de formes à l'index spécifié. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crée un nouveau cadre image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crée un nouveau cadre image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crée un nouveau tableau et l'ajoute à la fin de la collection de formes. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crée un nouveau tableau et l'insère dans la collection de formes à l'index spécifié. |
| [removeAt(int index)](#removeAt-int-) | Supprime la forme à l'index spécifié de la collection de formes. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [clear()](#clear--) | Supprime toutes les formes de la collection de formes. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [getParentGroup()](#getParentGroup--) | Obtient l'objet groupe parent pour la collection de formes. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule  int .

**Valeur de retour :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instancie la classe Presentation qui représente un fichier PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Accède à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Ajoute un graphique avec ses données par défaut
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Définit le titre du graphique
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Configure la première série pour afficher les valeurs
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Définit l'index pour la feuille de données du graphique
>      int defaultWorksheetIndex = 0;
>      // Obtient la feuille de calcul des données du graphique
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Supprime les séries et catégories générées par défaut
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Ajoute de nouvelles séries
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Ajoute de nouvelles catégories
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Récupère la première série du graphique
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Remplit les données de la série
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Définit la couleur de remplissage pour la série
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Récupère la deuxième série du graphique
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Remplit les données de la série
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Définit la couleur de remplissage pour la série
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Configure la première étiquette pour afficher le nom de la catégorie
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Configure la série pour afficher la valeur pour la troisième étiquette
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Enregistre le fichier PPTX sur le disque
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |

**Valeur de retour :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à ajouter. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du graphique, en points. |
| height | float | La hauteur du graphique, en points. |
| initWithSample | boolean | True pour initialiser le nouveau graphique avec des données de série d'exemple et des paramètres ; false pour créer le graphique sans série et uniquement avec les paramètres minimaux, ce qui accélère la création. |

**Valeur de retour :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> L'exemple suivant montre comment ajouter une forme intelligente dans une présentation PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
| layoutType | int | Le type de mise en page SmartArt. |

**Valeur de retour :**
[ISmartArt](../../com.aspose.slides/ismartart) - Le [ISmartArt](../../com.aspose.slides/ismartart) nouvellement créé.
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à créer. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du nouveau graphique, en points. |
| height | float | La hauteur du nouveau graphique, en points. |
| index | int | L'index basé sur zéro où insérer le nouveau graphique dans la collection de formes. |

**Valeur de retour :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crée un nouveau graphique, l'initialise avec des données de série d'exemple et des paramètres, et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de graphique à créer. |
| x | float | La coordonnée x du nouveau graphique, en points. |
| y | float | La coordonnée y du nouveau graphique, en points. |
| width | float | La largeur du nouveau graphique, en points. |
| height | float | La hauteur du nouveau graphique, en points. |
| index | int | L'index basé sur zéro où insérer le nouveau graphique dans la collection de formes. |
| initWithSample | boolean | True pour initialiser le nouveau graphique avec des données de série d'exemple et des paramètres ; false pour créer le graphique sans série et uniquement avec les paramètres minimaux, ce qui accélère la création. |

**Valeur de retour :**
[IChart](../../com.aspose.slides/ichart) - Le [IChart](../../com.aspose.slides/ichart) nouvellement créé.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> Cet exemple montre comment ajouter un objet Zoom à la fin d'une collection
>  (supposons qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") :
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

**Valeur de retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> Cet exemple montre comment ajouter un objet Zoom à la fin d'une collection
>  (supposons qu'il y ait au moins deux diapositives dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
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

**Valeur de retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection
>  (supposons qu'il y ait au moins deux diapositives dans la présentation "Presentation.pptx"):
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
| index | int | L'index basé sur zéro où insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom. |

**Valeur de retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection
>  (supposons qu'il y ait au moins deux diapositives dans la présentation "Presentation.pptx") :
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre Zoom. |
| x | float | La coordonnée x du nouveau cadre Zoom, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom, en points. |
| width | float | La largeur du nouveau cadre Zoom, en points. |
| height | float | La hauteur du nouveau cadre Zoom, en points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Le [ISlide](../../com.aspose.slides/islide) référencé par le cadre Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'image pour la diapositive référencée [IPPImage](../../com.aspose.slides/ippimage). |

**Valeur de retour :**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Le [IZoomFrame](../../com.aspose.slides/izoomframe) nouvellement créé.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crée un nouveau cadre Zoom de section et le ajoute à la fin de la collection de formes.

--------------------

> ```
> Cet exemple montre comment ajouter un objet Section Zoom à la fin d'une collection
>  (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):
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

**Valeur de retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crée un nouveau cadre Zoom de section avec une image prédéfinie et le ajoute à la fin de la collection de formes.

--------------------

> ```
> Cet exemple montre comment ajouter un objet Section Zoom à la fin d'une collection
>  (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
| image | [IPPImage](../../com.aspose.slides/ippimage) | Le [IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre Zoom de section. |

**Valeur de retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crée un nouveau cadre Zoom de section et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Section Zoom à l'index spécifié d'une collection
>  (supposons qu'il y a au moins deux sections dans la présentation "Presentation.pptx"):
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
| index | int | L'index basé sur zéro où insérer le cadre Zoom de section. |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |

**Valeur de retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crée un nouveau cadre Zoom de section avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Section Zoom à l'index spécifié d'une collection
>  (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre Zoom de section. |
| x | float | La coordonnée x du nouveau cadre Zoom de section, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de section, en points. |
| width | float | La largeur du nouveau cadre Zoom de section, en points. |
| height | float | La hauteur du nouveau cadre Zoom de section, en points. |
| section | [ISection](../../com.aspose.slides/isection) | Le [ISection](../../com.aspose.slides/isection) référencé par le cadre Zoom de section ; doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'image à afficher dans le cadre Zoom de section. |

**Valeur de retour :**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Le [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) nouvellement créé.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crée un nouveau cadre Zoom de résumé et le ajoute à la fin de la collection de formes.

--------------------

> ```
> Cet exemple montre comment ajouter un objet Summary Zoom à la fin d'une collection
>  (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):
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

Cette méthode crée un nouveau résumé Zoom et place une collection d'objets à l'intérieur pour toutes les sections de cette présentation.

**Valeur de retour :**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Le [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) nouvellement créé.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Crée un nouveau cadre Zoom de résumé et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre la création et l'insertion d'un objet Summary Zoom à l'index spécifié d'une collection
>  (supposons qu'il y ait au moins deux sections dans la présentation "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre Zoom de résumé. |
| x | float | La coordonnée x du nouveau cadre Zoom de résumé, en points. |
| y | float | La coordonnée y du nouveau cadre Zoom de résumé, en points. |
| width | float | La largeur du nouveau cadre Zoom de résumé, en points. |
| height | float | La hauteur du nouveau cadre Zoom de résumé, en points. |

Cette méthode crée un cadre Zoom de résumé qui agrège les liens de résumé pour toutes les sections de la présentation.

**Valeur de retour :**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Le [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) nouvellement créé.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crée un nouveau cadre d'objet OLE et le ajoute à la fin de la collection de formes.

--------------------

> ```
> L'exemple suivant montre comment ajouter des cadres d'objet OLE aux diapositives d'une présentation PowerPoint.
>  
>  // Instancie la classe Presentation qui représente le PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Accède à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Charge un fichier Excel en flux
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Crée un objet de données pour l'intégration
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Ajoute une forme de cadre d'objet OLE
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Écrit le PPTX sur le disque
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Les informations sur les données OLE intégrées ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Valeur de retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crée un nouveau cadre d'objet OLE et le ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| className | java.lang.String | Le nom de classe de l'objet OLE. |
| path | java.lang.String | Le chemin du fichier lié. Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent. |

**Valeur de retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

--------------------

> ```
> Cet exemple montre comment insérer un objet OLE à l'index 2 :
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre d'objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Les informations sur les données OLE intégrées ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Valeur de retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) nouvellement créé.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre d'objet OLE. |
| x | float | La coordonnée x du nouveau cadre OLE, en points. |
| y | float | La coordonnée y du nouveau cadre OLE, en points. |
| width | float | La largeur du nouveau cadre OLE, en points. |
| height | float | La hauteur du nouveau cadre OLE, en points. |
| className | java.lang.String | Le nom de classe de l'objet OLE. |
| path | java.lang.String | Le chemin du fichier lié. Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent. |

**Valeur de retour :**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Le cadre d'objet OLE nouvellement créé.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Crée un nouveau cadre vidéo et le ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier vidéo à intégrer. |

**Valeur de retour :**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le [IVideoFrame](../../com.aspose.slides/ivideoframe) nouvellement créé.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Crée un nouveau cadre vidéo et le ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Le [IVideo](../../com.aspose.slides/ivideo) à intégrer dans le cadre vidéo. |

**Valeur de retour :**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le [IVideoFrame](../../com.aspose.slides/ivideoframe) nouvellement créé.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre vidéo. |
| x | float | La coordonnée x du nouveau cadre vidéo, en points. |
| y | float | La coordonnée y du nouveau cadre vidéo, en points. |
| width | float | La largeur du nouveau cadre vidéo, en points. |
| height | float | La hauteur du nouveau cadre vidéo, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier vidéo à intégrer. |

**Valeur de retour :**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Le [IVideoFrame](../../com.aspose.slides/ivideoframe) nouvellement créé.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Crée un nouveau cadre audio lié à une piste CD et le ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Crée un nouveau cadre audio lié à un fichier audio externe et le ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier audio externe à lier. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| fname | java.lang.String | Le chemin ou le nom du fichier audio externe à lier. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Crée un nouveau cadre audio avec un fichier WAV intégré et le ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instancie une classe de présentation qui représente un fichier de présentation
>  Presentation pres = new Presentation();
>  try {
>      // Obtient la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Charge le fichier audio wav dans un flux
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Ajoute le cadre audio
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Définit le mode de lecture et le volume de l'audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Écrit le fichier PowerPoint sur le disque
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | java.io.InputStream | Un flux d'entrée contenant des données audio WAV à intégrer. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio_stream | java.io.InputStream | Un flux d'entrée contenant des données audio WAV à intégrer. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Crée un nouveau cadre audio et le ajoute à la fin de la collection de formes en utilisant un objet audio existant de la liste Presentation.Audios.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Une instance [IAudio](../../com.aspose.slides/iaudio) de la collection Presentation.Audios. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié en utilisant un objet audio existant de la liste Presentation.Audios.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre audio. |
| x | float | La coordonnée x du nouveau cadre audio, en points. |
| y | float | La coordonnée y du nouveau cadre audio, en points. |
| width | float | La largeur du nouveau cadre audio, en points. |
| height | float | La hauteur du nouveau cadre audio, en points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Une instance [IAudio](../../com.aspose.slides/iaudio) de la collection Presentation.Audios à intégrer. |

**Valeur de retour :**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Le [IAudioFrame](../../com.aspose.slides/iaudioframe) nouvellement créé.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La forme à localiser dans la collection. |

**Valeur de retour :**
int - L'index basé sur zéro de la première occurrence de la forme dans la collection si trouvée ; sinon, \u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Crée et renvoie un tableau contenant toutes les formes.

**Valeur de retour :**
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | L'index de la première forme à renvoyer. |
| count | int | Le nombre de formes à renvoyer. |

**Valeur de retour :**
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Déplace la forme spécifiée vers une nouvelle position au sein de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la forme sera placée. |
| shape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à déplacer dans la collection. |
### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Déplace les formes spécifiées au sein de la collection de formes, en les plaçant à partir de l'index donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index cible basé sur zéro où la première forme spécifiée sera placée ; les formes suivantes suivent dans l'ordre fourni. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Une ou plusieurs instances [IShape](../../com.aspose.slides/ishape) à déplacer dans la collection. |
### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle auto-forme avec un formatage par défaut et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de l'auto-forme à ajouter. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Valeur de retour :**
[IAutoShape](../../com.aspose.slides/iautoshape) - La [IAutoShape](../../com.aspose.slides/iautoshape) nouvellement créée.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle auto-forme et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de l'auto-forme à ajouter. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (style simple, texte centré et nom non vide) à la nouvelle forme ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

**Valeur de retour :**
[IAutoShape](../../com.aspose.slides/iautoshape) - La [IAutoShape](../../com.aspose.slides/iautoshape) nouvellement créée.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Crée une nouvelle auto-forme rectangulaire pour accueillir du contenu mathématique et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> L'exemple suivant montre comment ajouter une équation mathématique dans une présentation PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Valeur de retour :**
[IAutoShape](../../com.aspose.slides/iautoshape) - La [IAutoShape](../../com.aspose.slides/iautoshape) nouvellement créée.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle auto-forme et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer la nouvelle auto-forme. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de l'auto-forme à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |

**Valeur de retour :**
[IAutoShape](../../com.aspose.slides/iautoshape) - La [IAutoShape](../../com.aspose.slides/iautoshape) nouvellement créée.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle auto-forme et l'insère dans la collection de formes à l'index spécifié, en l'initialisant éventuellement avec le style de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer l'auto-forme. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) de l'auto-forme à insérer. |
| x | float | La coordonnée x du cadre de la forme, en points. |
| y | float | La coordonnée y du cadre de la forme, en points. |
| width | float | La largeur du cadre de la forme, en points. |
| height | float | La hauteur du cadre de la forme, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (incluant un nom non vide, un style simple et un texte centré) ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |

**Valeur de retour :**
[IAutoShape](../../com.aspose.slides/iautoshape) - La [IAutoShape](../../com.aspose.slides/iautoshape) nouvellement créée.
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Crée un nouveau groupe de formes vide et l'ajoute à la fin de la collection de formes. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

--------------------

> ```
> L'exemple suivant montre comment ajouter une forme groupée à une diapositive d'une présentation PowerPoint.
>  
>  // Instancie la classe Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Obtient la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accède à la collection de formes des diapositives
>      IShapeCollection slideShapes = sld.getShapes();
>      // Ajoute une forme groupée à la diapositive
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Ajoute des formes à l'intérieur de la forme groupée ajoutée
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Ajoute le cadre de la forme groupée
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Écrit le fichier PPTX sur le disque
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Valeur de retour :**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le [IGroupShape](../../com.aspose.slides/igroupshape) nouvellement créé.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crée un nouveau groupe de formes, convertit l'image SVG contenant du contenu vectoriel en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Le [ISvgImage](../../com.aspose.slides/isvgimage) contenant du contenu vectoriel à convertir en formes. |
| x | float | La coordonnée x du cadre du groupe, en points. |
| y | float | La coordonnée y du cadre du groupe, en points. |
| width | float | La largeur du cadre du groupe, en points. |
| height | float | La hauteur du cadre du groupe, en points. |

**Valeur de retour :**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le [IGroupShape](../../com.aspose.slides/igroupshape) nouvellement créé.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Crée un nouveau groupe de formes vide et l'insère dans la collection de formes à l'index spécifié. Le cadre du groupe s'ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le groupe de formes. |

**Valeur de retour :**
[IGroupShape](../../com.aspose.slides/igroupshape) - Le [IGroupShape](../../com.aspose.slides/igroupshape) nouvellement créé.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> L'exemple suivant montre comment ajouter un connecteur (un connecteur coudé) entre deux formes (une ellipse et un rectangle) dans une présentation PowerPoint.
>  
>  // Instancie une classe de présentation qui représente un fichier PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Accède à la collection de formes d'une diapositive spécifique
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Ajoute une forme auto ellipse
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Ajoute une forme auto rectangle
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Ajoute une forme de connecteur à la collection de formes de la diapositive
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connecte les formes à l'aide du connecteur
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Appelle reroute qui définit le chemin le plus court automatique entre les formes
>      connector.reroute();
>      // Enregistre la présentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à ajouter. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

**Valeur de retour :**
[IConnector](../../com.aspose.slides/iconnector) - Le [IConnector](../../com.aspose.slides/iconnector) nouvellement créé.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à créer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriété par défaut. |

**Valeur de retour :**
[IConnector](../../com.aspose.slides/iconnector) - Le [IConnector](../../com.aspose.slides/iconnector) nouvellement créé.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant le style de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le connecteur. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |

**Valeur de retour :**
[IConnector](../../com.aspose.slides/iconnector) - Le [IConnector](../../com.aspose.slides/iconnector) nouvellement créé.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié, en appliquant éventuellement le style de modèle par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le connecteur. |
| shapeType | int | Le [ShapeType](../../com.aspose.slides/shapetype) du connecteur à insérer. |
| x | float | La coordonnée x du cadre du connecteur, en points. |
| y | float | La coordonnée y du cadre du connecteur, en points. |
| width | float | La largeur du cadre du connecteur, en points. |
| height | float | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | boolean | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriété par défaut. |

**Valeur de retour :**
[IConnector](../../com.aspose.slides/iconnector) - Le [IConnector](../../com.aspose.slides/iconnector) nouvellement créé.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crée un nouveau cadre image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | int | Spécifie le type de forme contenu dans [ShapeType](../../com.aspose.slides/shapetype), à l'exception de tous les types de lignes : ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | La coordonnée x du cadre image, en points. |
| y | float | La coordonnée y du cadre image, en points. |
| width | float | La largeur du cadre image, en points. |
| height | float | La hauteur du cadre image, en points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Le [IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre image. |

**Valeur de retour :**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Le [IPictureFrame](../../com.aspose.slides/ipictureframe) nouvellement créé.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crée un nouveau cadre image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le cadre image. |
| shapeType | int | Spécifie le type de forme contenu dans [ShapeType](../../com.aspose.slides/shapetype), à l'exception de tous les types de lignes : ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | La coordonnée x du cadre image, en points. |
| y | float | La coordonnée y du cadre image, en points. |
| width | float | La largeur du cadre image, en points. |
| height | float | La hauteur du cadre image, en points. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Le [IPPImage](../../com.aspose.slides/ippimage) à afficher dans le cadre image. |

**Valeur de retour :**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Le [IPictureFrame](../../com.aspose.slides/ipictureframe) nouvellement créé.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crée un nouveau tableau et l'ajoute à la fin de la collection de formes.

--------------------

> ```
> L'exemple suivant montre comment ajouter un tableau dans une présentation PowerPoint.
>  
>  // Instancie la classe Presentation qui représente le fichier PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Accède à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Définit les colonnes avec leurs largeurs et les lignes avec leurs hauteurs
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Ajoute la forme tableau à la diapositive
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Définit le format de bordure pour chaque cellule
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Fusionne les cellules 1 et 2 de la ligne 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Ajoute du texte à la cellule fusionnée
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Enregistre le PPTX sur le disque
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | La coordonnée x du tableau, en points. |
| y | float | La coordonnée y du tableau, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

**Valeur de retour :**
[ITable](../../com.aspose.slides/itable) - Le [ITable](../../com.aspose.slides/itable) nouvellement créé.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Crée un nouveau tableau et l'insère dans la collection de formes à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer le tableau. |
| x | float | La coordonnée x du tableau, en points. |
| y | float | La coordonnée y du tableau, en points. |
| columnWidths | double[] | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | double[] | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

**Valeur de retour :**
[ITable](../../com.aspose.slides/itable) - Le [ITable](../../com.aspose.slides/itable) nouvellement créé.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime la forme à l'index spécifié de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de la forme à supprimer. |
### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Supprime la première occurrence de la forme spécifiée de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) à supprimer. |
### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les formes de la collection de formes.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Valeur de retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Valeur de retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un java.util.Iterator pour l'ensemble de la collection.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Obtient l'objet groupe parent de la collection de formes. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

**Valeur de retour :**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | float | La largeur du cadre de la nouvelle forme, en points. |
| height | float | La hauteur du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La nouvelle forme conserve la largeur et la hauteur de la sourceShape.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forme à cloner. |
| x | float | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | float | La coordonnée y du cadre de la nouvelle forme, en points. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. La forme clonée conserve la position et la taille originales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |
| width | float | La largeur du cadre de la forme clonée, en points. |
| height | float | La hauteur du cadre de la forme clonée, en points. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La nouvelle forme conserve la largeur et la hauteur de la sourceShape.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) à cloner. |
| x | float | La coordonnée x du cadre de la forme clonée, en points. |
| y | float | La coordonnée y du cadre de la forme clonée, en points. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index indiqué. La forme clonée conserve la position et la taille originales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où insérer la forme clonée. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Le [IShape](../../com.aspose.slides/ishape) à cloner. |

**Valeur de retour :**
[IShape](../../com.aspose.slides/ishape) - Le [IShape](../../com.aspose.slides/ishape) nouvellement créé.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de début dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule  boolean .

**Valeur de retour :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Lecture seule  Object .

**Valeur de retour :**
java.lang.Object