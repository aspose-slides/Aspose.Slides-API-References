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


### getFontBytes {#getFontBytes}

| Name | Description |
| --- | --- |
| getFontBytes ([FontData](../fontdata), int) | Retrieves the byte array representing the font data for a specified font style and font data. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontData | [FontData](../fontdata) | The font data object containing the information about the font IFontData. |
| fontStyle | int | The style of the font for which the data is to be retrieved FontStyleType. |

 **Returns:**
byte


---


### getFontEmbeddingLevel {#getFontEmbeddingLevel}

| Name | Description |
| --- | --- |
| getFontEmbeddingLevel (byte[], String) | Determines the embedding level of a font from the given byte array and font name. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | The byte array containing the font data. |
| fontName | String | The name of the font. |

 **Returns:**
int

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown when {@code fontBytes} is null. |


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
[TabCollection](../tabcollection), [SmartArtShapeCollection](../smartartshapecollection), SortedList, [CommentCollection](../commentcollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [ChartDataPointCollection](../chartdatapointcollection), [SectionCollection](../sectioncollection), [PointCollection](../pointcollection), [MathParagraph](../mathparagraph), [FontFallBackRulesCollection](../fontfallbackrulescollection), ReadOnlyCollection, [ControlPropertiesCollection](../controlpropertiescollection), [CellCollection](../cellcollection), [ParagraphCollection](../paragraphcollection), [ControlCollection](../controlcollection), [CaptionsCollection](../captionscollection), [ShapeCollection](../shapecollection), [Row](../row), [PortionCollection](../portioncollection), [ChartCellCollection](../chartcellcollection), [CustomXmlPartCollection](../customxmlpartcollection), [DrawingGuidesCollection](../drawingguidescollection), [ChartSeriesCollection](../chartseriescollection), [LayoutSlideCollection](../layoutslidecollection), [GradientStopCollection](../gradientstopcollection), Stack, [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [Column](../column), [FillFormatCollection](../fillformatcollection), [VbaReferenceCollection](../vbareferencecollection), [VbaModuleCollection](../vbamodulecollection), [MasterSlideCollection](../masterslidecollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [ColorOperationCollection](../coloroperationcollection), Queue, [MasterLayoutSlideCollection](../masterlayoutslidecollection), [SectionSlideCollection](../sectionslidecollection), [SlideCollection](../slidecollection), SortedDictionary, KeyedCollection, [CommentAuthorCollection](../commentauthorcollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [TextAnimationCollection](../textanimationcollection), LinkedList, [LineFormatCollection](../lineformatcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [DataLabelCollection](../datalabelcollection), [SequenceCollection](../sequencecollection), [Sequence](../sequence), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ColumnCollection](../columncollection), [SmartArtNodeCollection](../smartartnodecollection), [FontSubstRuleCollection](../fontsubstrulecollection), List, [ImageCollection](../imagecollection), [TagCollection](../tagcollection), [AudioCollection](../audiocollection), [EffectStyleCollection](../effectstylecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [ChartCategoryCollection](../chartcategorycollection), Dictionary, [MotionPath](../motionpath), [DigitalSignatureCollection](../digitalsignaturecollection), [MathBlock](../mathblock), [TrendlineCollection](../trendlinecollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [RowCollection](../rowcollection), [VideoCollection](../videocollection), [BehaviorCollection](../behaviorcollection), Collection


---


### getSubstitutions {#getSubstitutions}

| Name | Description |
| --- | --- |
| getSubstitutions (int[]) | Gets the information about fonts that will be replaced during rendering of the specified slides. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slides | int[] | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

 **Returns:**
[TabCollection](../tabcollection), [SmartArtShapeCollection](../smartartshapecollection), SortedList, [CommentCollection](../commentcollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [ChartDataPointCollection](../chartdatapointcollection), [SectionCollection](../sectioncollection), [PointCollection](../pointcollection), [MathParagraph](../mathparagraph), [FontFallBackRulesCollection](../fontfallbackrulescollection), ReadOnlyCollection, [ControlPropertiesCollection](../controlpropertiescollection), [CellCollection](../cellcollection), [ParagraphCollection](../paragraphcollection), [ControlCollection](../controlcollection), [CaptionsCollection](../captionscollection), [ShapeCollection](../shapecollection), [Row](../row), [PortionCollection](../portioncollection), [ChartCellCollection](../chartcellcollection), [CustomXmlPartCollection](../customxmlpartcollection), [DrawingGuidesCollection](../drawingguidescollection), [ChartSeriesCollection](../chartseriescollection), [LayoutSlideCollection](../layoutslidecollection), [GradientStopCollection](../gradientstopcollection), Stack, [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [Column](../column), [FillFormatCollection](../fillformatcollection), [VbaReferenceCollection](../vbareferencecollection), [VbaModuleCollection](../vbamodulecollection), [MasterSlideCollection](../masterslidecollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [ColorOperationCollection](../coloroperationcollection), Queue, [MasterLayoutSlideCollection](../masterlayoutslidecollection), [SectionSlideCollection](../sectionslidecollection), [SlideCollection](../slidecollection), SortedDictionary, KeyedCollection, [CommentAuthorCollection](../commentauthorcollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [TextAnimationCollection](../textanimationcollection), LinkedList, [LineFormatCollection](../lineformatcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [DataLabelCollection](../datalabelcollection), [SequenceCollection](../sequencecollection), [Sequence](../sequence), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ColumnCollection](../columncollection), [SmartArtNodeCollection](../smartartnodecollection), [FontSubstRuleCollection](../fontsubstrulecollection), List, [ImageCollection](../imagecollection), [TagCollection](../tagcollection), [AudioCollection](../audiocollection), [EffectStyleCollection](../effectstylecollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [ChartCategoryCollection](../chartcategorycollection), Dictionary, [MotionPath](../motionpath), [DigitalSignatureCollection](../digitalsignaturecollection), [MathBlock](../mathblock), [TrendlineCollection](../trendlinecollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [RowCollection](../rowcollection), [VideoCollection](../videocollection), [BehaviorCollection](../behaviorcollection), Collection


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


