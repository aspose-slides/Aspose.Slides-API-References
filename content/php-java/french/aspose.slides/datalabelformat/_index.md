---
title: DataLabelFormat
second_title: Référence de l'API Java Aspose.Sildes pour PHP
description: 
type: docs
url: /fr/aspose.slides/datalabelformat/
---
## DataLabelFormat classe

 Représente les options de mise en forme pour DataLabel.
 
### getChart {#getChart}

| Nom | Description |
| --- | --- |
| getChart () | Renvoie le graphique. Lecture seule IChart. |

 **Renvoie :**
[Chart](../chart)


---


### getFormat {#getFormat}

| Nom | Description |
| --- | --- |
| getFormat () | Représente le format de l'étiquette de données. Lecture seule IFormat. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété représente le format par défaut pour les nouvelles étiquettes de données dans la collection DataLabelCollection. |

 **Renvoie :**
[Format](../format)


---


### getNumberFormat {#getNumberFormat}

| Nom | Description |
| --- | --- |
| getNumberFormat () | Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" fait que tous les DataLabels.get_Item(i).getNumberFormat() sont égaux à val). |

 **Renvoie :**
String


---


### getPosition {#getPosition}

| Nom | Description |
| --- | --- |
| getPosition () | Représente la position de l'étiquette de données. Lecture/écriture LegendDataLabelPosition. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position des objets DataLabel. Définir cette propriété avec une valeur met également cette valeur dans la propriété Position pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause que tous les DataLabels.get_Item(i).getPosition() sont égaux à val). |

 **Renvoie :**
int


---


### getSeparator {#getSeparator}

| Nom | Description |
| --- | --- |
| getSeparator () | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause que tous les DataLabels.get_Item(i).getSeparator() sont égaux à val). |

 **Renvoie :**
String


---


### getShowBubbleSize {#getShowBubbleSize}

| Nom | Description |
| --- | --- |
| getShowBubbleSize () | Représente le comportement d'affichage de la valeur de taille de bulle d'une étiquette de données d'un graphique spécifié. True affiche la valeur de la taille de la bulle. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowBubbleSize pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause que tous les DataLabels.get_Item(i).getShowBubbleSize() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowCategoryName {#getShowCategoryName}

| Nom | Description |
| --- | --- |
| getShowCategoryName () | Représente le comportement d'affichage du nom de catégorie d'une étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowCategoryName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause que tous les DataLabels.get_Item(i).getShowCategoryName() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowLabelAsDataCallout {#getShowLabelAsDataCallout}

| Nom | Description |
| --- | --- |
| getShowLabelAsDataCallout () | Détermine si l'étiquette de données d'un graphique spécifié sera affichée comme appel de données ou comme étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause que tous les DataLabels.get_Item(i).getShowLabelAsDataCallout() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowLabelValueFromCell {#getShowLabelValueFromCell}

| Nom | Description |
| --- | --- |
| getShowLabelValueFromCell () | Représente le comportement d'affichage de la valeur de cellule d'une étiquette de données d'un graphique spécifié. True affiche la valeur de la cellule. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowLabelValueFromCell pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause que tous les DataLabels.get_Item(i).getShowLabelValueFromCell() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowLeaderLines {#getShowLeaderLines}

| Nom | Description |
| --- | --- |
| getShowLeaderLines () | Représente le comportement d'affichage des lignes directrices d'une étiquette de données d'un graphique spécifié. True affiche les lignes directrices. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowLeaderLines pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause que tous les DataLabels.get_Item(i).getShowLeaderLines() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowLegendKey {#getShowLegendKey}

| Nom | Description |
| --- | --- |
| getShowLegendKey () | Représente le comportement d'affichage de la clé de légende d'une étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowLegendKey pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause que tous les DataLabels.get_Item(i).getShowLegendKey() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowPercentage {#getShowPercentage}

| Nom | Description |
| --- | --- |
| getShowPercentage () | Représente le comportement d'affichage de la valeur de pourcentage d'une étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowPercentage pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause que tous les DataLabels.get_Item(i).getShowPercentage() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowSeriesName {#getShowSeriesName}

| Nom | Description |
| --- | --- |
| getShowSeriesName () | Renvoie ou définit un booléen indiquant le comportement d'affichage du nom de série pour les étiquettes de données sur un graphique. True pour afficher le nom de série. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowSeriesName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause que tous les DataLabels.get_Item(i).getShowSeriesName() sont égaux à val). |

 **Renvoie :**
boolean


---


### getShowValue {#getShowValue}

| Nom | Description |
| --- | --- |
| getShowValue () | Représente le comportement d'affichage de la valeur de pourcentage d'une étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété ShowValue pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause que tous les DataLabels.get_Item(i).getShowValue() sont égaux à val). |

 **Renvoie :**
boolean


---


### getTextFormat {#getTextFormat}

| Nom | Description |
| --- | --- |
| getTextFormat () | Renvoie le format de texte du graphique. Lecture seule IChartTextFormat. |

 **Renvoie :**
[ChartTextFormat](../charttextformat)


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie :**
long


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Nom | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur met également cette valeur dans la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause que tous les DataLabels.get_Item(i).isNumberFormatLinkedToSource() sont égaux à val). |

 **Renvoie :**
boolean


---


### setNumberFormat {#setNumberFormat}

| Nom | Description |
| --- | --- |
| setNumberFormat (String) | Représente la chaîne de format pour l'objet DataLabels. Lecture/écriture String. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" fait que tous les DataLabels.get_Item(i).getNumberFormat() sont égaux à val). |

 **Renvoie :**
void
### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Nom | Description |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété IsNumberFormatLinkedToSource pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété IsNumberFormatLinkedToSource pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).isNumberFormatLinkedToSource() sont égales à val). |

**Renvoie:**  
void


---


### setPosition {#setPosition}

| Nom | Description |
| --- | --- |
| setPosition (int) | Représente la position de l’étiquette de données. Lecture/écriture LegendDataLabelPosition. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Représente la position des objets DataLabel. Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setPosition(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getPosition() sont égales à val). |

**Renvoie:**  
void


---


### setSeparator {#setSeparator}

| Nom | Description |
| --- | --- |
| setSeparator (String) | Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données sur un graphique. Lecture/écriture String. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dire "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getSeparator() sont égales à val). |

**Renvoie:**  
void


---


### setShowBubbleSize {#setShowBubbleSize}

| Nom | Description |
| --- | --- |
| setShowBubbleSize (boolean) | Représente le comportement d’affichage de la valeur de taille de bulle des étiquettes de données d’un graphique spécifié. true affiche la valeur de taille de bulle. false la masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowBubbleSize() sont égales à val). |

**Renvoie:**  
void


---


### setShowCategoryName {#setShowCategoryName}

| Nom | Description |
| --- | --- |
| setShowCategoryName (boolean) | Représente le comportement d’affichage du nom de catégorie des étiquettes de données d’un graphique spécifié. true affiche le nom de catégorie. false le masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowCategoryName() sont égales à val). |

**Renvoie:**  
void


---


### setShowLabelAsDataCallout {#setShowLabelAsDataCallout}

| Nom | Description |
| --- | --- |
| setShowLabelAsDataCallout (boolean) | Détermine si l’étiquette de données d’un graphique spécifié sera affichée comme appel de données ou comme étiquette de données. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelAsDataCallout pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowLabelAsDataCallout() sont égales à val). |

**Renvoie:**  
void


---


### setShowLabelValueFromCell {#setShowLabelValueFromCell}

| Nom | Description |
| --- | --- |
| setShowLabelValueFromCell (boolean) | Représente le comportement d’affichage de la valeur de cellule des étiquettes de données d’un graphique spécifié. true affiche la valeur de cellule. false la masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowLabelValueFromCell() sont égales à val). |

**Renvoie:**  
void


---


### setShowLeaderLines {#setShowLeaderLines}

| Nom | Description |
| --- | --- |
| setShowLeaderLines (boolean) | Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. true affiche les lignes de repère. false les masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowLeaderLines() sont égales à val). |

**Renvoie:**  
void


---


### setShowLegendKey {#setShowLegendKey}

| Nom | Description |
| --- | --- |
| setShowLegendKey (boolean) | Représente le comportement d’affichage de la clé de légende des étiquettes de données d’un graphique spécifié. true si la clé de légende de l’étiquette de données est visible. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowLegendKey() sont égales à val). |

**Renvoie:**  
void


---


### setShowPercentage {#setShowPercentage}

| Nom | Description |
| --- | --- |
| setShowPercentage (boolean) | Représente le comportement d’affichage de la valeur de pourcentage des étiquettes de données d’un graphique spécifié. true affiche la valeur de pourcentage. false la masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowPercentage() sont égales à val). |

**Renvoie:**  
void


---


### setShowSeriesName {#setShowSeriesName}

| Nom | Description |
| --- | --- |
| setShowSeriesName (boolean) | Renvoie ou définit un booléen indiquant le comportement d’affichage du nom de série pour les étiquettes de données d’un graphique. true affiche le nom de série. false le masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowSeriesName() sont égales à val). |

**Renvoie:**  
void


---


### setShowValue {#setShowValue}

| Nom | Description |
| --- | --- |
| setShowValue (boolean) | Représente le comportement d’affichage de la valeur des étiquettes de données d’un graphique spécifié. true affiche la valeur. false la masque. Lecture/écriture boolean. Si le parent de cet objet DataLabelFormat est une collection DataLabelCollection d’étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection DataLabelCollection. Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données de la collection DataLabelCollection (c’est-à-dit "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" ce qui entraîne que toutes les DataLabels.get_Item(i).getShowValue() sont égales à val). |

**Renvoie:**  
void


---