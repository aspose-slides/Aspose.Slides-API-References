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
| fontData | [FontData](../fontdata) | The font data object containing the information about the font FontData. |
| fontStyle | int | The style of the font for which the data is to be retrieved FontStyle. |

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
[BehaviorCollection](../behaviorcollection), [Column](../column), KeyedCollection, [MathBlock](../mathblock), [VbaModuleCollection](../vbamodulecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), Queue, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SlideCollection](../slidecollection), [TextAnimationCollection](../textanimationcollection), [TagCollection](../tagcollection), [ChartDataPointCollection](../chartdatapointcollection), [MathParagraph](../mathparagraph), [VbaReferenceCollection](../vbareferencecollection), [MotionPath](../motionpath), [ImageCollection](../imagecollection), [SmartArtNodeCollection](../smartartnodecollection), [DrawingGuidesCollection](../drawingguidescollection), [SectionSlideCollection](../sectionslidecollection), [LayoutSlideCollection](../layoutslidecollection), [SmartArtShapeCollection](../smartartshapecollection), [CellCollection](../cellcollection), ReadOnlyCollection, [PointCollection](../pointcollection), SortedDictionary, [VideoCollection](../videocollection), [GradientStopCollection](../gradientstopcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), Collection, [EffectStyleCollection](../effectstylecollection), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [CommentAuthorCollection](../commentauthorcollection), [DigitalSignatureCollection](../digitalsignaturecollection), List, [SectionCollection](../sectioncollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), [DataLabelCollection](../datalabelcollection), [TrendlineCollection](../trendlinecollection), Stack, [ControlCollection](../controlcollection), [TabCollection](../tabcollection), [LineFormatCollection](../lineformatcollection), [ShapeCollection](../shapecollection), [FillFormatCollection](../fillformatcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [Sequence](../sequence), [ControlPropertiesCollection](../controlpropertiescollection), Dictionary, [MasterSlideCollection](../masterslidecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [ColumnCollection](../columncollection), [SequenceCollection](../sequencecollection), [CommentCollection](../commentcollection), [PortionCollection](../portioncollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [FontSubstRuleCollection](../fontsubstrulecollection), [CustomXmlPartCollection](../customxmlpartcollection), LinkedList, [Row](../row), [ChartCellCollection](../chartcellcollection), [RowCollection](../rowcollection), [ChartCategoryCollection](../chartcategorycollection), SortedList, [AudioCollection](../audiocollection), [ParagraphCollection](../paragraphcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [ColorOperationCollection](../coloroperationcollection), [ChartSeriesCollection](../chartseriescollection)


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


