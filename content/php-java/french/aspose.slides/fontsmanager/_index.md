---
title: FontsManager
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/fontsmanager/
---
## FontsManager classe

 Gère les polices à travers la présentation.
 
### addEmbeddedFont {#addEmbeddedFont}

| Nom | Description |
| --- | --- |
| addEmbeddedFont ([FontData](../fontdata), int) | Ajoute la police incorporée |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Une ArgumentException peut être levée si les données de police sont nulles ou si cette police est déjà incorporée Gardez à l'esprit lors de la copie de toute police que la plupart des polices sont protégées par le droit d'auteur. Localisez d'abord la licence d'une police à l'avance et vérifiez qu'elle peut être transférée librement vers une autre machine. |


---

### addEmbeddedFont {#addEmbeddedFont}

| Nom | Description |
| --- | --- |
| addEmbeddedFont (byte[], int) | Ajoute la police incorporée |

 **Retour :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentException | Une ArgumentException peut être levée si les données de police sont nulles ou si cette police est déjà incorporée Gardez à l'esprit lors de la copie de toute police que la plupart des polices sont protégées par le droit d'auteur. Localisez d'abord la licence d'une police à l'avance et vérifiez qu'elle peut être transférée librement vers une autre machine. |


---

### getEmbeddedFonts {#getEmbeddedFonts}

| Nom | Description |
| --- | --- |
| getEmbeddedFonts () | Retourne les polices incorporées dans la présentation |

 **Retour :**
[FontData](../fontdata)


---

### getFontBytes {#getFontBytes}

| Nom | Description |
| --- | --- |
| getFontBytes ([FontData](../fontdata), int) | Récupère le tableau d'octets représentant les données de police pour un style de police spécifié et les données de police. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../fontdata) | L'objet de données de police contenant les informations sur la police IFontData. |
| fontStyle | int | Le style de la police pour lequel les données doivent être récupérées FontStyleType. |

 **Retour :**
byte


---

### getFontEmbeddingLevel {#getFontEmbeddingLevel}

| Nom | Description |
| --- | --- |
| getFontEmbeddingLevel (byte[], String) | Détermine le niveau d'incorporation d'une police à partir du tableau d'octets donné et du nom de la police. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | Le tableau d'octets contenant les données de police. |
| fontName | String | Le nom de la police. |

 **Retour :**
int

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Levée lorsque {@code fontBytes} est null. |


---

### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| Nom | Description |
| --- | --- |
| getFontFallBackRulesCollection () | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices pour des substitutions appropriées via la fonctionnalité de repli Lecture/écriture IFontFallBackRulesCollection. |

 **Retour :**
[FontFallBackRulesCollection](../fontfallbackrulescollection)


---

### getFontSubstRuleList {#getFontSubstRuleList}

| Nom | Description |
| --- | --- |
| getFontSubstRuleList () | Substitutions de police à utiliser lors du rendu. Lecture/écriture IFontSubstRuleCollection. |

 **Retour :**
[FontSubstRuleCollection](../fontsubstrulecollection)


---

### getFonts {#getFonts}

| Nom | Description |
| --- | --- |
| getFonts () | Retourne les polices utilisées dans la présentation |

 **Retour :**
[FontData](../fontdata)


---

### getSubstitutions {#getSubstitutions}

| Nom | Description |
| --- | --- |
| getSubstitutions () | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |

 **Retour :**
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)


---

### getSubstitutions {#getSubstitutions}

| Nom | Description |
| --- | --- |
| getSubstitutions (int[]) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| slides | int[] | Un tableau d'index de diapositives pour lesquelles récupérer les informations de substitution de police, en commençant à 1. |

 **Retour :**
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)


---

### removeEmbeddedFont {#removeEmbeddedFont}

| Nom | Description |
| --- | --- |
| removeEmbeddedFont ([FontData](../fontdata)) | Supprime la police incorporée |

 **Retour :**
void


---

### replaceFont {#replaceFont}

| Nom | Description |
| --- | --- |
| replaceFont ([FontData](../fontdata), [FontData](../fontdata)) | Remplace la police dans la présentation |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Police source |
| destFont | [FontData](../fontdata) | Police de destination |

 **Retour :**
void


---

### replaceFont {#replaceFont}

| Nom | Description |
| --- | --- |
| replaceFont ([FontSubstRule](../fontsubstrule)) | Remplace la police dans la présentation en utilisant les informations fournies dans FontSubstRule |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| substRule | [FontSubstRule](../fontsubstrule) | Informations de substitution de police |

 **Retour :**
void


---

### replaceFont {#replaceFont}

| Nom | Description |
| --- | --- |
| replaceFont ([FontSubstRuleCollection](../fontsubstrulecollection)) | Remplace la police dans la présentation en utilisant les informations fournies dans une collection de FontSubstRule |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection](../fontsubstrulecollection) | Collection de règles de substitution de police |

 **Retour :**
void


---

### setFontFallBackRulesCollection {#setFontFallBackRulesCollection}

| Nom | Description |
| --- | --- |
| setFontFallBackRulesCollection ([FontFallBackRulesCollection](../fontfallbackrulescollection)) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices pour des substitutions appropriées via la fonctionnalité de repli Lecture/écriture IFontFallBackRulesCollection. |

 **Retour :**
void


---

### setFontSubstRuleList {#setFontSubstRuleList}

| Nom | Description |
| --- | --- |
| setFontSubstRuleList ([FontSubstRuleCollection](../fontsubstrulecollection)) | Substitutions de police à utiliser lors du rendu. Lecture/écriture IFontSubstRuleCollection. |

 **Retour :**
void


---