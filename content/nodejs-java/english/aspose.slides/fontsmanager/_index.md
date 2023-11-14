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

 **Result:**
[FontData](../fontdata)


---


### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| Name | Description |
| --- | --- |
| getFontFallBackRulesCollection () | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |

 **Result:**
[FontFallBackRulesCollection](../fontfallbackrulescollection)


---


### getFontSubstRuleList {#getFontSubstRuleList}

| Name | Description |
| --- | --- |
| getFontSubstRuleList () | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |

 **Result:**
[FontSubstRuleCollection](../fontsubstrulecollection)


---


### getFonts {#getFonts}

| Name | Description |
| --- | --- |
| getFonts () | Returns the fonts used in the presentation |

 **Result:**
[FontData](../fontdata)


---


### getSubstitutions {#getSubstitutions}

| Name | Description |
| --- | --- |
| getSubstitutions () | Gets the information about fonts that will be replaced on the presentation's rendering. |

 **Result:**
[FontSubstRuleCollection](../fontsubstrulecollection), [ShapeCollection](../shapecollection), [RowCollection](../rowcollection), [ImageCollection](../imagecollection), SortedList, [PointCollection](../pointcollection), [TextAnimationCollection](../textanimationcollection), KeyedCollection, [ImageTransformOperationCollection](../imagetransformoperationcollection), [ControlPropertiesCollection](../controlpropertiescollection), [VbaReferenceCollection](../vbareferencecollection), Stack, [SmartArtShapeCollection](../smartartshapecollection), Dictionary, [GradientStopCollection](../gradientstopcollection), [CommentAuthorCollection](../commentauthorcollection), [ChartCellCollection](../chartcellcollection), [CommentCollection](../commentcollection), [PortionCollection](../portioncollection), [ColorOperationCollection](../coloroperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), List, [Sequence](../sequence), [CustomXmlPartCollection](../customxmlpartcollection), [MathBlock](../mathblock), LinkedList, Collection, [Row](../row), [DigitalSignatureCollection](../digitalsignaturecollection), [EffectStyleCollection](../effectstylecollection), [AudioCollection](../audiocollection), [FillFormatCollection](../fillformatcollection), [SectionCollection](../sectioncollection), [ChartCategoryCollection](../chartcategorycollection), [TagCollection](../tagcollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [VbaModuleCollection](../vbamodulecollection), [MotionPath](../motionpath), [SequenceCollection](../sequencecollection), [VideoCollection](../videocollection), [SmartArtNodeCollection](../smartartnodecollection), [ParagraphCollection](../paragraphcollection), [Column](../column), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColumnCollection](../columncollection), [CellCollection](../cellcollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [ControlCollection](../controlcollection), [MasterSlideCollection](../masterslidecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [DataLabelCollection](../datalabelcollection), [TrendlineCollection](../trendlinecollection), [ChartSeriesCollection](../chartseriescollection), [MathParagraph](../mathparagraph), [BehaviorPropertyCollection](../behaviorpropertycollection), [ChartDataPointCollection](../chartdatapointcollection), [TabCollection](../tabcollection), [BehaviorCollection](../behaviorcollection), [LineFormatCollection](../lineformatcollection), [LayoutSlideCollection](../layoutslidecollection), SortedDictionary, ReadOnlyCollection, [SlideCollection](../slidecollection), Queue


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


