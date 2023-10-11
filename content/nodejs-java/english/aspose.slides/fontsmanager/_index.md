---
title: FontsManager
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/fontsmanager/
---

## FontsManager class

 Manages fonts across the presentation.
 
| [addEmbeddedFont] ([FontData], [int]) Adds the embedded font |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


| [addEmbeddedFont] ([byte[]], [int]) Adds the embedded font |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | An ArgumentException can be thrown if font data is null or this font is already embedded Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |


---


| [getEmbeddedFonts] () Returns the fonts embedded in the presentation |

### Result
[FontData]


---


| [getFontFallBackRulesCollection] () Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |

### Result
[FontFallBackRulesCollection]


---


| [getFontSubstRuleList] () Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |

### Result
[FontSubstRuleCollection]


---


| [getFonts] () Returns the fonts used in the presentation |

### Result
[FontData]


---


| [getSubstitutions] () Gets the information about fonts that will be replaced on the presentation's rendering. |

### Result
[LineFormatCollection], [MathParagraph], [ExtraColorSchemeCollection], [SmartArtShapeCollection], [RowCollection], [PortionCollection], [VbaModuleCollection], [VbaReferenceCollection], [FontSubstRuleCollection], [SectionSlideCollection], [CellCollection], [SortedList], [SectionCollection], [DataLabelCollection], [MotionPath], [ReadOnlyCollection], [ColumnCollection], [TabCollection], [KeyedCollection], [ShapeCollection], [CommentAuthorCollection], [ChartCategoryCollection], [CustomXmlPartCollection], [Dictionary], [SlideCollection], [SortedDictionary], [Sequence], [Stack], [LinkedList], [Column], [ColorOperationCollection], [ChartDataPointCollection], [Collection], [MasterSlideCollection], [MasterLayoutSlideCollection], [SummaryZoomSectionCollection], [BehaviorCollection], [ImageCollection], [GradientStopCollectionEffectiveData], [SmartArtNodeCollection], [SequenceCollection], [BehaviorPropertyCollection], [VideoCollection], [TextAnimationCollection], [ChartCellCollection], [EffectStyleCollection], [ControlCollection], [PieSplitCustomPointCollection], [FontFallBackRulesCollection], [ImageTransformOCollectionEffectiveData], [TrendlineCollection], [DigitalSignatureCollection], [AudioCollection], [ChartSeriesCollection], [ControlPropertiesCollection], [MathBlock], [ParagraphCollection], [Row], [CommentCollection], [ImageTransformOperationCollection], [TagCollection], [GradientStopCollection], [List], [GlobalLayoutSlideCollection], [ChartDataWorksheetCollection], [LayoutSlideCollection], [Queue], [FillFormatCollection], [PointCollection]


---


| [removeEmbeddedFont] ([FontData]) Removes the embedded font |


---


| [replaceFont] ([FontData], [FontData]) Replace font in presentation |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData] | Source font |
| destFont | [FontData] | Destination font |


---


| [replaceFont] ([FontSubstRule]) Replace font in presentation using information provided in FontSubstRule |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| substRule | [FontSubstRule] | Font substitution info |


---


| [replaceFont] ([FontSubstRuleCollection]) Replace font in presentation using information provided in collection of FontSubstRule |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection] | Font substitution rules collection |


---


| [setFontFallBackRulesCollection] ([FontFallBackRulesCollection]) Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |


---


| [setFontSubstRuleList] ([FontSubstRuleCollection]) Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |


---


