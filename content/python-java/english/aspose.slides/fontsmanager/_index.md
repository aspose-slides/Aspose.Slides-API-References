---
title: FontsManager
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/fontsmanager/
---

## FontsManager class

 Manages fonts across the presentation.
 
### addEmbeddedFont {#addEmbeddedFont}

| Name | Description |
| --- | --- |
| addEmbeddedFont([FontData](../fontdata), int) | Adds the embedded font |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


### addEmbeddedFont {#addEmbeddedFont}

| Name | Description |
| --- | --- |
| addEmbeddedFont(byte[], int) | Adds the embedded font |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


### getEmbeddedFonts {#getEmbeddedFonts}

| Name | Description |
| --- | --- |
| getEmbeddedFonts() | Returns the fonts embedded in the presentation |

 **Returns:**
[FontData](../fontdata)


---


### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| Name | Description |
| --- | --- |
| getFontFallBackRulesCollection() | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |

 **Returns:**
[FontFallBackRulesCollection](../fontfallbackrulescollection)


---


### getFontSubstRuleList {#getFontSubstRuleList}

| Name | Description |
| --- | --- |
| getFontSubstRuleList() | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |

 **Returns:**
[FontSubstRuleCollection](../fontsubstrulecollection)


---


### getFonts {#getFonts}

| Name | Description |
| --- | --- |
| getFonts() | Returns the fonts used in the presentation |

 **Returns:**
[FontData](../fontdata)


---


### getSubstitutions {#getSubstitutions}

| Name | Description |
| --- | --- |
| getSubstitutions() | Gets the information about fonts that will be replaced on the presentation's rendering. |

 **Returns:**
Collection, [ShapeCollection](../shapecollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [Column](../column), [Row](../row), [PortionCollection](../portioncollection), [FontSubstRuleCollection](../fontsubstrulecollection), SortedList, [ChartCategoryCollection](../chartcategorycollection), [CustomXmlPartCollection](../customxmlpartcollection), [SlideCollection](../slidecollection), [Sequence](../sequence), [ParagraphCollection](../paragraphcollection), [LineFormatCollection](../lineformatcollection), [TabCollection](../tabcollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [MotionPath](../motionpath), [CommentAuthorCollection](../commentauthorcollection), [SectionCollection](../sectioncollection), [ImageCollection](../imagecollection), [VbaModuleCollection](../vbamodulecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), Queue, [VbaReferenceCollection](../vbareferencecollection), [ChartCellCollection](../chartcellcollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [AudioCollection](../audiocollection), [GradientStopCollection](../gradientstopcollection), [TagCollection](../tagcollection), [EffectStyleCollection](../effectstylecollection), [TextAnimationCollection](../textanimationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, KeyedCollection, [ControlPropertiesCollection](../controlpropertiescollection), List, [TrendlineCollection](../trendlinecollection), [BehaviorCollection](../behaviorcollection), [VideoCollection](../videocollection), [CellCollection](../cellcollection), [SmartArtShapeCollection](../smartartshapecollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), LinkedList, [LayoutSlideCollection](../layoutslidecollection), [ControlCollection](../controlcollection), [MathBlock](../mathblock), [BehaviorPropertyCollection](../behaviorpropertycollection), [MathParagraph](../mathparagraph), [ImageTransformOperationCollection](../imagetransformoperationcollection), [ColumnCollection](../columncollection), [ColorOperationCollection](../coloroperationcollection), Dictionary, [DataLabelCollection](../datalabelcollection), [CommentCollection](../commentcollection), [SectionSlideCollection](../sectionslidecollection), [SequenceCollection](../sequencecollection), [ChartDataPointCollection](../chartdatapointcollection), [DigitalSignatureCollection](../digitalsignaturecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), ReadOnlyCollection, [SmartArtNodeCollection](../smartartnodecollection), Stack, [FillFormatCollection](../fillformatcollection), [PointCollection](../pointcollection), [MasterSlideCollection](../masterslidecollection), [ChartSeriesCollection](../chartseriescollection), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection)


---


### removeEmbeddedFont {#removeEmbeddedFont}

| Name | Description |
| --- | --- |
| removeEmbeddedFont([FontData](../fontdata)) | Removes the embedded font |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont([FontData](../fontdata), [FontData](../fontdata)) | Replace font in presentation |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Source font |
| destFont | [FontData](../fontdata) | Destination font |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont([FontSubstRule](../fontsubstrule)) | Replace font in presentation using information provided in FontSubstRule |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| substRule | [FontSubstRule](../fontsubstrule) | Font substitution info |


---


### replaceFont {#replaceFont}

| Name | Description |
| --- | --- |
| replaceFont([FontSubstRuleCollection](../fontsubstrulecollection)) | Replace font in presentation using information provided in collection of FontSubstRule |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection](../fontsubstrulecollection) | Font substitution rules collection |


---


### setFontFallBackRulesCollection {#setFontFallBackRulesCollection}

| Name | Description |
| --- | --- |
| setFontFallBackRulesCollection([FontFallBackRulesCollection](../fontfallbackrulescollection)) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |


---


### setFontSubstRuleList {#setFontSubstRuleList}

| Name | Description |
| --- | --- |
| setFontSubstRuleList([FontSubstRuleCollection](../fontsubstrulecollection)) | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |


---


