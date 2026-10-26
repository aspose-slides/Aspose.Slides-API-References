---
title: FontsManager
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/fontsmanager/
---
## FontsManager 类

 管理整个演示文稿中的字体。

### addEmbeddedFont {#addEmbeddedFont}

| 名称 | 描述 |
| --- | --- |
| addEmbeddedFont ([FontData](../fontdata), int) | 添加嵌入的字体 |

**返回:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果字体数据为 null 或此字体已嵌入，则会抛出 ArgumentException。请注意，在复制任何字体时，大多数字体受版权保护。请先查找字体的许可证，并确认其可以自由转移到另一台机器。 |

---

### addEmbeddedFont {#addEmbeddedFont}

| 名称 | 描述 |
| --- | --- |
| addEmbeddedFont (byte[], int) | 添加嵌入的字体 |

**返回:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果字体数据为 null 或此字体已嵌入，则会抛出 ArgumentException。请注意，在复制任何字体时，大多数字体受版权保护。请先查找字体的许可证，并确认其可以自由转移到另一台机器。 |

---

### getEmbeddedFonts {#getEmbeddedFonts}

| 名称 | 描述 |
| --- | --- |
| getEmbeddedFonts () | 返回演示文稿中嵌入的字体 |

**返回:**  
[FontData](../fontdata)

---

### getFontBytes {#getFontBytes}

| 名称 | 描述 |
| --- | --- |
| getFontBytes ([FontData](../fontdata), int) | 检索表示指定字体样式和字体数据的字节数组 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontData | [FontData](../fontdata) | 包含字体信息的字体数据对象 IFontData |
| fontStyle | int | 要检索其数据的字体样式 FontStyleType |

**返回:**  
byte

---

### getFontEmbeddingLevel {#getFontEmbeddingLevel}

| 名称 | 描述 |
| --- | --- |
| getFontEmbeddingLevel (byte[], String) | 确定给定字节数组和字体名称的字体嵌入级别 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fontBytes | byte[] | 包含字体数据的字节数组 |
| fontName | String | 字体名称 |

**返回:**  
int

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 当 {@code fontBytes} 为 null 时抛出 |

---

### getFontFallBackRulesCollection {#getFontFallBackRulesCollection}

| 名称 | 描述 |
| --- | --- |
| getFontFallBackRulesCollection () | 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体的适当替代。读/写 IFontFallBackRulesCollection |

**返回:**  
[FontFallBackRulesCollection](../fontfallbackrulescollection)

---

### getFontSubstRuleList {#getFontSubstRuleList}

| 名称 | 描述 |
| --- | --- |
| getFontSubstRuleList () | 在渲染时使用的字体替换。读/写 IFontSubstRuleCollection |

**返回:**  
[FontSubstRuleCollection](../fontsubstrulecollection)

---

### getFonts {#getFonts}

| 名称 | 描述 |
| --- | --- |
| getFonts () | 返回演示文稿中使用的字体 |

**返回:**  
[FontData](../fontdata)

---

### getSubstitutions {#getSubstitutions}

| 名称 | 描述 |
| --- | --- |
| getSubstitutions () | 获取将在演示文稿渲染时被替换的字体信息 |

**返回:**  
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)

---

### getSubstitutions {#getSubstitutions}

| 名称 | 描述 |
| --- | --- |
| getSubstitutions (int[]) | 获取在指定幻灯片渲染期间将被替换的字体信息 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slides | int[] | 要检索字体替换信息的幻灯片索引数组，索引从 1 开始 |

**返回:**  
[CommentCollection](../commentcollection), [BehaviorPropertyCollection](../behaviorpropertycollection), [LineFormatCollection](../lineformatcollection), [ColumnCollection](../columncollection), SortedList, [ChartDataWorksheetCollection](../chartdataworksheetcollection), [SensitivityLabelCollection](../sensitivitylabelcollection), [EffectStyleCollection](../effectstylecollection), [GradientStopCollectionEffectiveData](../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../smartartnodecollection), [DigitalSignatureCollection](../digitalsignaturecollection), [TabCollection](../tabcollection), [PieSplitCustomPointCollection](../piesplitcustompointcollection), [SlideCollection](../slidecollection), List, [DrawingGuidesCollection](../drawingguidescollection), [ChartCategoryCollection](../chartcategorycollection), [SmartArtShapeCollection](../smartartshapecollection), [ShapeCollection](../shapecollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), [FontFallBackRulesCollection](../fontfallbackrulescollection), SortedDictionary, [Sequence](../sequence), [RowCollection](../rowcollection), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../chartseriescollection), Stack, [ChartCellCollection](../chartcellcollection), [CommentAuthorCollection](../commentauthorcollection), Collection, [Row](../row), [AudioCollection](../audiocollection), [CustomXmlPartCollection](../customxmlpartcollection), [DataLabelCollection](../datalabelcollection), Dictionary, [MathBlock](../mathblock), [ImageTransformOCollectionEffectiveData](../imagetransformocollectioneffectivedata), [CaptionsCollection](../captionscollection), [TrendlineCollection](../trendlinecollection), [ParagraphCollection](../paragraphcollection), [MasterSlideCollection](../masterslidecollection), [TextAnimationCollection](../textanimationcollection), ReadOnlyCollection, [SectionCollection](../sectioncollection), [ChartDataPointCollection](../chartdatapointcollection), [MotionPath](../motionpath), [ControlPropertiesCollection](../controlpropertiescollection), [FontSubstRuleCollection](../fontsubstrulecollection), [BehaviorCollection](../behaviorcollection), [Column](../column), [VbaReferenceCollection](../vbareferencecollection), [PointCollection](../pointcollection), [ImageCollection](../imagecollection), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [FillFormatCollection](../fillformatcollection), [GradientStopCollection](../gradientstopcollection), [PortionCollection](../portioncollection), [LayoutSlideCollection](../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../globallayoutslidecollection), [TagCollection](../tagcollection), [SequenceCollection](../sequencecollection), [ControlCollection](../controlcollection), [ExtraColorSchemeCollection](../extracolorschemecollection), [SectionSlideCollection](../sectionslidecollection), [ColorOperationCollection](../coloroperationcollection), [CellCollection](../cellcollection), [VbaModuleCollection](../vbamodulecollection), KeyedCollection, [MathParagraph](../mathparagraph), [VideoCollection](../videocollection)

---

### removeEmbeddedFont {#removeEmbeddedFont}

| 名称 | 描述 |
| --- | --- |
| removeEmbeddedFont ([FontData](../fontdata)) | 移除嵌入的字体 |

**返回:**  
void

---

### replaceFont {#replaceFont}

| 名称 | 描述 |
| --- | --- |
| replaceFont ([FontData](../fontdata), [FontData](../fontdata)) | 在演示文稿中替换字体 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | 源字体 |
| destFont | [FontData](../fontdata) | 目标字体 |

**返回:**  
void

---

### replaceFont {#replaceFont}

| 名称 | 描述 |
| --- | --- |
| replaceFont ([FontSubstRule](../fontsubstrule)) | 使用 FontSubstRule 中提供的信息在演示文稿中替换字体 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| substRule | [FontSubstRule](../fontsubstrule) | 字体替换信息 |

**返回:**  
void

---

### replaceFont {#replaceFont}

| 名称 | 描述 |
| --- | --- |
| replaceFont ([FontSubstRuleCollection](../fontsubstrulecollection)) | 使用 FontSubstRule 集合中提供的信息在演示文稿中替换字体 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| substRules | [FontSubstRuleCollection](../fontsubstrulecollection) | 字体替换规则集合 |

**返回:**  
void

---

### setFontFallBackRulesCollection {#setFontFallBackRulesCollection}

| 名称 | 描述 |
| --- | --- |
| setFontFallBackRulesCollection ([FontFallBackRulesCollection](../fontfallbackrulescollection)) | 表示用户的 FontFallBack 规则集合，用于通过回退功能管理字体的适当替代。读/写 IFontFallBackRulesCollection |

**返回:**  
void

---

### setFontSubstRuleList {#setFontSubstRuleList}

| 名称 | 描述 |
| --- | --- |
| setFontSubstRuleList ([FontSubstRuleCollection](../fontsubstrulecollection)) | 在渲染时使用的字体替换。读/写 IFontSubstRuleCollection |

**返回:**  
void

---