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
[MasterLayoutSlideCollection](../masterlayoutslidecollection), [ColumnCollection](../columncollection), [SectionCollection](../sectioncollection), [SmartArtNodeCollection](../smartartnodecollection), [TabCollection](../tabcollection), [ImageCollection](../imagecollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [FillFormatCollection](../fillformatcollection), [ControlCollection](../controlcollection), [EffectStyleCollection](../effectstylecollection), ReadOnlyCollection, [ChartCellCollection](../chartcellcollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [ControlPropertiesCollection](../controlpropertiescollection), Queue, [Sequence](../sequence), [SectionSlideCollection](../sectionslidecollection), [ChartDataPointCollection](../chartdatapointcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [CustomXmlPartCollection](../customxmlpartcollection), [VideoCollection](../videocollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [PortionCollection](../portioncollection), [MathBlock](../mathblock), SortedList, [ParagraphCollection](../paragraphcollection), [DataLabelCollection](../datalabelcollection), List, [ChartSeriesCollection](../chartseriescollection), [Column](../column), Collection, [ShapeCollection](../shapecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), Stack, [BehaviorCollection](../behaviorcollection), [CommentAuthorCollection](../commentauthorcollection), [MasterSlideCollection](../masterslidecollection), [MotionPath](../motionpath), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [FontSubstRuleCollection](../fontsubstrulecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [VbaReferenceCollection](../vbareferencecollection), [SequenceCollection](../sequencecollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [MathParagraph](../mathparagraph), [RowCollection](../rowcollection), [LineFormatCollection](../lineformatcollection), KeyedCollection, [PointCollection](../pointcollection), SortedDictionary, [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [TagCollection](../tagcollection), [DigitalSignatureCollection](../digitalsignaturecollection), Dictionary, [Row](../row), [AudioCollection](../audiocollection), [GradientStopCollection](../gradientstopcollection), [LayoutSlideCollection](../layoutslidecollection), [SlideCollection](../slidecollection), [SmartArtShapeCollection](../smartartshapecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TrendlineCollection](../trendlinecollection), [TextAnimationCollection](../textanimationcollection), LinkedList, [CommentCollection](../commentcollection), [ChartCategoryCollection](../chartcategorycollection), [VbaModuleCollection](../vbamodulecollection)


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


