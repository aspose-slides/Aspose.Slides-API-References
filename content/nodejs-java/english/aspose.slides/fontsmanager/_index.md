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
[MotionPath](../motionpath), [TabCollection](../tabcollection), [SectionSlideCollection](../sectionslidecollection), [CellCollection](../cellcollection), [MasterSlideCollection](../masterslidecollection), [MathBlock](../mathblock), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ChartDataPointCollection](../chartdatapointcollection), [VbaReferenceCollection](../vbareferencecollection), SortedDictionary, [LineFormatCollection](../lineformatcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [ColorOperationCollection](../coloroperationcollection), LinkedList, [ChartCellCollection](../chartcellcollection), [FillFormatCollection](../fillformatcollection), ReadOnlyCollection, [FontFallBackRulesCollection](../fontfallbackrulescollection), [ImageCollection](../imagecollection), [VideoCollection](../videocollection), [TextAnimationCollection](../textanimationcollection), [ControlCollection](../controlcollection), [ChartCategoryCollection](../chartcategorycollection), [Sequence](../sequence), [CommentAuthorCollection](../commentauthorcollection), List, [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [CommentCollection](../commentcollection), [ShapeCollection](../shapecollection), [DataLabelCollection](../datalabelcollection), [MathParagraph](../mathparagraph), [VbaModuleCollection](../vbamodulecollection), [LayoutSlideCollection](../layoutslidecollection), [BehaviorPropertyCollection](../behaviorpropertycollection), Collection, [BehaviorCollection](../behaviorcollection), [ParagraphCollection](../paragraphcollection), Stack, [Row](../row), [MasterLayoutSlideCollection](../masterlayoutslidecollection), SortedList, [FontSubstRuleCollection](../fontsubstrulecollection), [TrendlineCollection](../trendlinecollection), [ColumnCollection](../columncollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [AudioCollection](../audiocollection), [EffectStyleCollection](../effectstylecollection), [SmartArtShapeCollection](../smartartshapecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [SlideCollection](../slidecollection), [SectionCollection](../sectioncollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [RowCollection](../rowcollection), [TagCollection](../tagcollection), [GradientStopCollection](../gradientstopcollection), [PointCollection](../pointcollection), [PortionCollection](../portioncollection), [CustomXmlPartCollection](../customxmlpartcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SequenceCollection](../sequencecollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [ChartSeriesCollection](../chartseriescollection), KeyedCollection, [ControlPropertiesCollection](../controlpropertiescollection), [SmartArtNodeCollection](../smartartnodecollection), Dictionary, [Column](../column), Queue


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


