---
title: FontsManager
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/fontsmanager/
---

## FontsManager class

 Manages fonts across the presentation.
 
### addEmbeddedFont {#addEmbeddedFont}

| Name | Description |
| --- | --- |
| addEmbeddedFont ([FontData](../fontdata), int) | Adds the embedded font |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


### addEmbeddedFont {#addEmbeddedFont}

| Name | Description |
| --- | --- |
| addEmbeddedFont (byte[], int) | Adds the embedded font |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


### getEmbeddedFonts {#getEmbeddedFonts}

| Name | Description |
| --- | --- |
| getEmbeddedFonts () | Returns the fonts embedded in the presentation |

 **Returns:**
[FontData](../fontdata)


---


### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| Name | Description |
| --- | --- |
| getFontFallBackRulesCollection () | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |

 **Returns:**
[FontFallBackRulesCollection](../fontfallbackrulescollection)


---


### getFontSubstRuleList {#getFontSubstRuleList}

| Name | Description |
| --- | --- |
| getFontSubstRuleList () | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |

 **Returns:**
[FontSubstRuleCollection](../fontsubstrulecollection)


---


### getFonts {#getFonts}

| Name | Description |
| --- | --- |
| getFonts () | Returns the fonts used in the presentation |

 **Returns:**
[FontData](../fontdata)


---


### getSubstitutions {#getSubstitutions}

| Name | Description |
| --- | --- |
| getSubstitutions () | Gets the information about fonts that will be replaced on the presentation's rendering. |

 **Returns:**
[VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ChartCategoryCollection](../chartcategorycollection), [CellCollection](../cellcollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), Stack, [FillFormatCollection](../fillformatcollection), [TrendlineCollection](../trendlinecollection), [SmartArtNodeCollection](../smartartnodecollection), [MathBlock](../mathblock), LinkedList, [ParagraphCollection](../paragraphcollection), [ColorOperationCollection](../coloroperationcollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [CommentCollection](../commentcollection), [Column](../column), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), [ChartSeriesCollection](../chartseriescollection), [CustomXmlPartCollection](../customxmlpartcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [CommentAuthorCollection](../commentauthorcollection), [VideoCollection](../videocollection), ReadOnlyCollection, [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [MathParagraph](../mathparagraph), [TextAnimationCollection](../textanimationcollection), [MasterSlideCollection](../masterslidecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ImageCollection](../imagecollection), Collection, [PortionCollection](../portioncollection), Dictionary, [RowCollection](../rowcollection), Queue, [Row](../row), [ChartCellCollection](../chartcellcollection), [DataLabelCollection](../datalabelcollection), [SmartArtShapeCollection](../smartartshapecollection), SortedList, [SectionSlideCollection](../sectionslidecollection), [SlideCollection](../slidecollection), [FontSubstRuleCollection](../fontsubstrulecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [GradientStopCollection](../gradientstopcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [LayoutSlideCollection](../layoutslidecollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [ControlCollection](../controlcollection), [SequenceCollection](../sequencecollection), [ControlPropertiesCollection](../controlpropertiescollection), [SectionCollection](../sectioncollection), [TagCollection](../tagcollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [AudioCollection](../audiocollection), [Sequence](../sequence), [VbaModuleCollection](../vbamodulecollection), [ShapeCollection](../shapecollection), [MotionPath](../motionpath), [ExtraColorSchemeCollection](../extracolorschemecollection), KeyedCollection, [BehaviorCollection](../behaviorcollection), SortedDictionary, List, [ChartDataPointCollection](../chartdatapointcollection)


---


### removeEmbeddedFont {#removeEmbeddedFont}

| Name | Description |
| --- | --- |
| removeEmbeddedFont ([FontData](../fontdata)) | Removes the embedded font |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont ([FontData](../fontdata), [FontData](../fontdata)) | Replace font in presentation |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Source font |
| destFont | [FontData](../fontdata) | Destination font |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont ([FontSubstRule](../fontsubstrule)) | Replace font in presentation using information provided in FontSubstRule |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| substRule | [FontSubstRule](../fontsubstrule) | Font substitution info |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont ([FontSubstRuleCollection](../fontsubstrulecollection)) | Replace font in presentation using information provided in collection of FontSubstRule |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection](../fontsubstrulecollection) | Font substitution rules collection |


---


### setFontFallBackRulesCollection {#setFontFallBackRulesCollection}

| Name | Description |
| --- | --- |
| setFontFallBackRulesCollection ([FontFallBackRulesCollection](../fontfallbackrulescollection)) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |


---


### setFontSubstRuleList {#setFontSubstRuleList}

| Name | Description |
| --- | --- |
| setFontSubstRuleList ([FontSubstRuleCollection](../fontsubstrulecollection)) | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |


---


