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
[PointCollection](../pointcollection), [Row](../row), [TabCollection](../tabcollection), LinkedList, [MotionPath](../motionpath), [CustomXmlPartCollection](../customxmlpartcollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [TagCollection](../tagcollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [MasterSlideCollection](../masterslidecollection), KeyedCollection, [BehaviorPropertyCollection](../behaviorpropertycollection), [VbaReferenceCollection](../vbareferencecollection), [SectionCollection](../sectioncollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [ExtraColorSchemeCollection](../extracolorschemecollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [ParagraphCollection](../paragraphcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [GradientStopCollection](../gradientstopcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [CommentAuthorCollection](../commentauthorcollection), Queue, [SectionSlideCollection](../sectionslidecollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ColorOperationCollection](../coloroperationcollection), List, [SmartArtNodeCollection](../smartartnodecollection), [TrendlineCollection](../trendlinecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [CaptionsCollection](../captionscollection), [LayoutSlideCollection](../layoutslidecollection), [FontSubstRuleCollection](../fontsubstrulecollection), [CommentCollection](../commentcollection), [SlideCollection](../slidecollection), [ChartDataPointCollection](../chartdatapointcollection), [ControlPropertiesCollection](../controlpropertiescollection), [LineFormatCollection](../lineformatcollection), [Column](../column), ReadOnlyCollection, [SequenceCollection](../sequencecollection), SortedList, [TextAnimationCollection](../textanimationcollection), Dictionary, [AudioCollection](../audiocollection), [MathParagraph](../mathparagraph), [EffectStyleCollection](../effectstylecollection), [BehaviorCollection](../behaviorcollection), [ChartCellCollection](../chartcellcollection), [DataLabelCollection](../datalabelcollection), [ControlCollection](../controlcollection), [Sequence](../sequence), [RowCollection](../rowcollection), [ShapeCollection](../shapecollection), Collection, [MathBlock](../mathblock), [ChartSeriesCollection](../chartseriescollection), Stack, [ImageCollection](../imagecollection), [PortionCollection](../portioncollection), [ColumnCollection](../columncollection), [FillFormatCollection](../fillformatcollection), [VideoCollection](../videocollection), [DrawingGuidesCollection](../drawingguidescollection), SortedDictionary, [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection)


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
[PointCollection](../pointcollection), [Row](../row), [TabCollection](../tabcollection), LinkedList, [MotionPath](../motionpath), [CustomXmlPartCollection](../customxmlpartcollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [ChartDataWorksheetCollection](../chartdataworksheetcollection), [TagCollection](../tagcollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [MasterSlideCollection](../masterslidecollection), KeyedCollection, [BehaviorPropertyCollection](../behaviorpropertycollection), [VbaReferenceCollection](../vbareferencecollection), [SectionCollection](../sectioncollection), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [ExtraColorSchemeCollection](../extracolorschemecollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [ParagraphCollection](../paragraphcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [GradientStopCollection](../gradientstopcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [CommentAuthorCollection](../commentauthorcollection), Queue, [SectionSlideCollection](../sectionslidecollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ColorOperationCollection](../coloroperationcollection), List, [SmartArtNodeCollection](../smartartnodecollection), [TrendlineCollection](../trendlinecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [CaptionsCollection](../captionscollection), [LayoutSlideCollection](../layoutslidecollection), [FontSubstRuleCollection](../fontsubstrulecollection), [CommentCollection](../commentcollection), [SlideCollection](../slidecollection), [ChartDataPointCollection](../chartdatapointcollection), [ControlPropertiesCollection](../controlpropertiescollection), [LineFormatCollection](../lineformatcollection), [Column](../column), ReadOnlyCollection, [SequenceCollection](../sequencecollection), SortedList, [TextAnimationCollection](../textanimationcollection), Dictionary, [AudioCollection](../audiocollection), [MathParagraph](../mathparagraph), [EffectStyleCollection](../effectstylecollection), [BehaviorCollection](../behaviorcollection), [ChartCellCollection](../chartcellcollection), [DataLabelCollection](../datalabelcollection), [ControlCollection](../controlcollection), [Sequence](../sequence), [RowCollection](../rowcollection), [ShapeCollection](../shapecollection), Collection, [MathBlock](../mathblock), [ChartSeriesCollection](../chartseriescollection), Stack, [ImageCollection](../imagecollection), [PortionCollection](../portioncollection), [ColumnCollection](../columncollection), [FillFormatCollection](../fillformatcollection), [VideoCollection](../videocollection), [DrawingGuidesCollection](../drawingguidescollection), SortedDictionary, [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection)


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


