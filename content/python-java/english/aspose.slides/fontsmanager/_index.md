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
[CellCollection](../cellcollection), [FontSubstRuleCollection](../fontsubstrulecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [FillFormatCollection](../fillformatcollection), [Column](../column), [EffectStyleCollection](../effectstylecollection), [PointCollection](../pointcollection), ReadOnlyCollection, [MasterLayoutSlideCollection](../masterlayoutslidecollection), [TrendlineCollection](../trendlinecollection), [VbaReferenceCollection](../vbareferencecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [Sequence](../sequence), [ShapeCollection](../shapecollection), [VbaModuleCollection](../vbamodulecollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [SectionSlideCollection](../sectionslidecollection), [ImageCollection](../imagecollection), [CommentAuthorCollection](../commentauthorcollection), Collection, Queue, [SmartArtNodeCollection](../smartartnodecollection), [RowCollection](../rowcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), SortedDictionary, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [MathBlock](../mathblock), [TabCollection](../tabcollection), [ColorOperationCollection](../coloroperationcollection), [ChartSeriesCollection](../chartseriescollection), [PortionCollection](../portioncollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [SmartArtShapeCollection](../smartartshapecollection), [ChartCategoryCollection](../chartcategorycollection), [Row](../row), SortedList, [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [VideoCollection](../videocollection), [ParagraphCollection](../paragraphcollection), [ControlCollection](../controlcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), Dictionary, List, [BehaviorCollection](../behaviorcollection), [TextAnimationCollection](../textanimationcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [MasterSlideCollection](../masterslidecollection), [MathParagraph](../mathparagraph), [AudioCollection](../audiocollection), [MotionPath](../motionpath), Stack, [LayoutSlideCollection](../layoutslidecollection), [SectionCollection](../sectioncollection), [DataLabelCollection](../datalabelcollection), [ColumnCollection](../columncollection), [ChartDataPointCollection](../chartdatapointcollection), [LineFormatCollection](../lineformatcollection), LinkedList, [CommentCollection](../commentcollection), [SequenceCollection](../sequencecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [SlideCollection](../slidecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ControlPropertiesCollection](../controlpropertiescollection), [ChartCellCollection](../chartcellcollection), [CustomXmlPartCollection](../customxmlpartcollection), [TagCollection](../tagcollection), KeyedCollection, [GradientStopCollection](../gradientstopcollection)


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


