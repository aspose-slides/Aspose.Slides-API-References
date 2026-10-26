---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for PHP via Java API 参考文档
description: 
type: docs

url: /zh/aspose.slides/imagetransformoperationcollection/
---
## ImageTransformOperationCollection 类

 表示对图像应用的效果集合。

### addAlphaBiLevelEffect {#addAlphaBiLevelEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaBiLevelEffect (float) | 将新的 Alpha Bi-Level 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | alpha bi-level effect 的阈值。 |

 **返回:**
[AlphaBiLevel](../alphabilevel)

---


### addAlphaCeilingEffect {#addAlphaCeilingEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaCeilingEffect () | 将新的 Alpha Ceiling 效果添加到集合的末尾。 |

 **返回:**
[AlphaCeiling](../alphaceiling)

---


### addAlphaFloorEffect {#addAlphaFloorEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaFloorEffect () | 将新的 Alpha Floor 效果添加到集合的末尾。 |

 **返回:**
[AlphaFloor](../alphafloor)

---


### addAlphaInverseEffect {#addAlphaInverseEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaInverseEffect () | 将新的 Alpha Inverse 效果添加到集合的末尾。 |

 **返回:**
[AlphaInverse](../alphainverse)

---


### addAlphaModulateEffect {#addAlphaModulateEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaModulateEffect () | 将新的 Alpha Modulate 效果添加到集合的末尾。 |

 **返回:**
[AlphaModulate](../alphamodulate)

---


### addAlphaModulateFixedEffect {#addAlphaModulateFixedEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaModulateFixedEffect (float) | 将新的 Alpha Modulate Fixed 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| amount | float | 用于缩放 alpha 的百分比。 |

 **返回:**
[AlphaModulateFixed](../alphamodulatefixed)

---


### addAlphaReplaceEffect {#addAlphaReplaceEffect}

| 名称 | 描述 |
| --- | --- |
| addAlphaReplaceEffect (float) | 将新的 Alpha Replace 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| alpha | float | 新的不透明度值。 |

 **返回:**
[AlphaReplace](../alphareplace)

---


### addBiLevelEffect {#addBiLevelEffect}

| 名称 | 描述 |
| --- | --- |
| addBiLevelEffect (float) | 将新的 Bi-Level（黑/白）效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| threshold | float | Bi-Level 效果的亮度阈值。大于等于阈值的值设为白色，小于阈值的值设为黑色。 |

 **返回:**
[BiLevel](../bilevel)

---


### addBlurEffect {#addBlurEffect}

| 名称 | 描述 |
| --- | --- |
| addBlurEffect (double, boolean) | 将新的 Blur 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 模糊半径。 |
| grow | boolean | 指定在模糊后是否应扩大对象的边界。True 表示扩展，false 表示不扩展。 |

 **返回:**
[Blur](../blur)

---


### addBrightnessContrastEffect {#addBrightnessContrastEffect}

| 名称 | 描述 |
| --- | --- |
| addBrightnessContrastEffect (float, float) | 将新的 BrightnessContrast 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| brightness | float | 用于更改亮度的百分比。 |
| contrast | float | 用于更改对比度的百分比。 |

 **返回:**
[BrightnessContrast](../brightnesscontrast)

---


### addColorChangeEffect {#addColorChangeEffect}

| 名称 | 描述 |
| --- | --- |
| addColorChangeEffect () | 将新的 Color Change 效果添加到集合的末尾。 |

 **返回:**
[ColorChange](../colorchange)

---


### addColorReplaceEffect {#addColorReplaceEffect}

| 名称 | 描述 |
| --- | --- |
| addColorReplaceEffect () | 将新的 Color Replacement 效果添加到集合的末尾。 |

 **返回:**
[ColorReplace](../colorreplace)

---


### addDuotoneEffect {#addDuotoneEffect}

| 名称 | 描述 |
| --- | --- |
| addDuotoneEffect () | 将新的 Duotone 效果添加到集合的末尾。 |

 **返回:**
[Duotone](../duotone)

---


### addFillOverlayEffect {#addFillOverlayEffect}

| 名称 | 描述 |
| --- | --- |
| addFillOverlayEffect () | 将新的 Fill Overlay 效果添加到集合的末尾。 |

 **返回:**
[FillOverlay](../filloverlay)

---


### addGrayScaleEffect {#addGrayScaleEffect}

| 名称 | 描述 |
| --- | --- |
| addGrayScaleEffect () | 将新的 Gray Scale 效果添加到集合的末尾。 |

 **返回:**
[GrayScale](../grayscale)

---


### addHSLEffect {#addHSLEffect}

| 名称 | 描述 |
| --- | --- |
| addHSLEffect (float, float, float) | 将新的 Hue/Saturation/Luminance 效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| hue | float | 调整色相的度数。 |
| saturation | float | 调整饱和度的百分比。 |
| luminance | float | 调整亮度的百分比。 |

 **返回:**
[HSL](../hsl)

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([SoftEdge](../softedge)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [SoftEdge](../softedge) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([ImageTransformOperation](../imagetransformoperation)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [ImageTransformOperation](../imagetransformoperation) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([Glow](../glow)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [Glow](../glow) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaModulateFixed](../alphamodulatefixed)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaModulateFixed](../alphamodulatefixed) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaFloor](../alphafloor)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaFloor](../alphafloor) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([OuterShadow](../outershadow)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [OuterShadow](../outershadow) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([Blur](../blur)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [Blur](../blur) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaReplace](../alphareplace)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaReplace](../alphareplace) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([FillOverlay](../filloverlay)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [FillOverlay](../filloverlay) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([HSL](../hsl)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [HSL](../hsl) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaBiLevel](../alphabilevel)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaBiLevel](../alphabilevel) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([BrightnessContrast](../brightnesscontrast)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [BrightnessContrast](../brightnesscontrast) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([ColorChange](../colorchange)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [ColorChange](../colorchange) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([InnerShadow](../innershadow)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [InnerShadow](../innershadow) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaModulate](../alphamodulate)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaModulate](../alphamodulate) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([Reflection](../reflection)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [Reflection](../reflection) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([GrayScale](../grayscale)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [GrayScale](../grayscale) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([Duotone](../duotone)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [Duotone](../duotone) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([Luminance](../luminance)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [Luminance](../luminance) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaInverse](../alphainverse)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaInverse](../alphainverse) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([AlphaCeiling](../alphaceiling)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [AlphaCeiling](../alphaceiling) | 要添加到集合末尾的图像效果。 |

 **返回:**
void

---


### addItem {#addItem}

| 名称 | 描述 |
| --- | --- |
| addItem ([PresetShadow](../presetshadow)) | 将新的图像效果添加到集合的末尾。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| operation | [PresetShadow](../presetshadow) | 要添加到集合末尾的图像效果。 |

 **返回:**
void
### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([BiLevel](../bilevel)) | 将新的图像效果添加到集合的末尾。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| operation | [BiLevel](../bilevel) | 要添加到集合末尾的图像效果。 |

**Returns：**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([ColorReplace](../colorreplace)) | 将新的图像效果添加到集合的末尾。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| operation | [ColorReplace](../colorreplace) | 要添加到集合末尾的图像效果。 |

**Returns：**
void


---


### addItem {#addItem}

| Name | Description |
| --- | --- |
| addItem ([Tint](../tint)) | 将新的图像效果添加到集合的末尾。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| operation | [Tint](../tint) | 要添加到集合末尾的图像效果。 |

**Returns：**
void


---


### addLuminanceEffect {#addLuminanceEffect}

| Name | Description |
| --- | --- |
| addLuminanceEffect (float, float) | 将新的 Luminance 效果添加到集合的末尾。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| brightness | float | 要更改亮度的百分比。 |
| contrast | float | 要更改对比度的百分比。 |

**Returns：**
[Luminance](../luminance)


---


### addTintEffect {#addTintEffect}

| Name | Description |
| --- | --- |
| addTintEffect (float, float) | 将新的 Tint 效果添加到集合的末尾。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| hue | float | 要着色的色相。 |
| amount | float | 指定颜色值的偏移量。 |

**Returns：**
[Tint](../tint)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | 从集合中移除所有图像效果。 |

**Returns：**
void


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([SoftEdge](../softedge)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ImageTransformOperation](../imagetransformoperation)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Glow](../glow)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Glow](../glow) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaModulateFixed](../alphamodulatefixed)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaFloor](../alphafloor)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([OuterShadow](../outershadow)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Blur](../blur)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Blur](../blur) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaReplace](../alphareplace)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([FillOverlay](../filloverlay)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([HSL](../hsl)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [HSL](../hsl) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaBiLevel](../alphabilevel)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([BrightnessContrast](../brightnesscontrast)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [BrightnessContrast](../brightnesscontrast) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ColorChange](../colorchange)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([InnerShadow](../innershadow)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaModulate](../alphamodulate)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Reflection](../reflection)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Reflection](../reflection) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([GrayScale](../grayscale)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Duotone](../duotone)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Duotone](../duotone) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Luminance](../luminance)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Luminance](../luminance) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaInverse](../alphainverse)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([AlphaCeiling](../alphaceiling)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([PresetShadow](../presetshadow)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([BiLevel](../bilevel)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([ColorReplace](../colorreplace)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### containsItem {#containsItem}

| Name | Description |
| --- | --- |
| containsItem ([Tint](../tint)) | 确定 IGenericCollection 是否包含特定值。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| item | [Tint](../tint) | 要在 IGenericCollection 中定位的对象。 |

**Returns：**
boolean


---


### copyToTArray {#copyToTArray}

| Name | Description |
| --- | --- |
| copyToTArray (com.aspose.slides.IImageTransformOperation[], int) | 将 IGenericCollection 的元素复制到数组，从特定的数组索引开始。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IImageTransformOperation[] | 从 IGenericCollection 复制的元素的目标的一维 Array。Array 必须使用从零开始的索引。 |
| arrayIndex | int | 复制开始时数组中的零基索引。 |

**Returns：**
void

**Exception**

| Error | Condition |
| --- | --- |
| ArgumentException | 源 IGenericCollection 中的元素数量大于从 arrayIndex 到目标数组末尾的可用空间。 |


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

**Returns：**
long


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 根据索引从集合中返回 ImageTransformOperation。 |

**Parameters：**

| Name | Type | Description |
| --- | --- | --- |
| index | int | 元素的索引。 |

**Returns：**
[SoftEdge](../softedge), [ImageTransformOperation](../imagetransformoperation), [Glow](../glow), [AlphaModulateFixed](../alphamodulatefixed), [AlphaFloor](../alphafloor), [OuterShadow](../outershadow), [Blur](../blur), [AlphaReplace](../alphareplace), [FillOverlay](../filloverlay), [HSL](../hsl), [AlphaBiLevel](../alphabilevel), [BrightnessContrast](../brightnesscontrast), [ColorChange](../colorchange), [InnerShadow](../innershadow), [AlphaModulate](../alphamodulate), [Reflection](../reflection), [GrayScale](../grayscale), [Duotone](../duotone), [Luminance](../luminance), [AlphaInverse](../alphainverse), [AlphaCeiling](../alphaceiling), [PresetShadow](../presetshadow), [BiLevel](../bilevel), [ColorReplace](../colorreplace), [Tint](../tint)


---


### isReadOnly {#isReadOnly}
| --- | --- |
| isReadOnly () | 获取一个值，指示 IGenericCollection 是否只读。只读布尔值。 |

**返回：**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

**返回：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回：**



---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从集合中删除指定索引处的图像效果。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的图像效果的索引。 |

**返回：**
void


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([SoftEdge](../softedge)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [SoftEdge](../softedge) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([ImageTransformOperation](../imagetransformoperation)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [ImageTransformOperation](../imagetransformoperation) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Glow](../glow)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Glow](../glow) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaModulateFixed](../alphamodulatefixed)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaModulateFixed](../alphamodulatefixed) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaFloor](../alphafloor)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaFloor](../alphafloor) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([OuterShadow](../outershadow)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [OuterShadow](../outershadow) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Blur](../blur)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Blur](../blur) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaReplace](../alphareplace)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaReplace](../alphareplace) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([FillOverlay](../filloverlay)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [FillOverlay](../filloverlay) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([HSL](../hsl)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [HSL](../hsl) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaBiLevel](../alphabilevel)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaBiLevel](../alphabilevel) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([BrightnessContrast](../brightnesscontrast)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BrightnessContrast](../brightnesscontrast) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([ColorChange](../colorchange)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [ColorChange](../colorchange) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([InnerShadow](../innershadow)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [InnerShadow](../innershadow) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaModulate](../alphamodulate)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaModulate](../alphamodulate) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Reflection](../reflection)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Reflection](../reflection) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([GrayScale](../grayscale)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [GrayScale](../grayscale) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Duotone](../duotone)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Duotone](../duotone) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Luminance](../luminance)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Luminance](../luminance) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaInverse](../alphainverse)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaInverse](../alphainverse) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([AlphaCeiling](../alphaceiling)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [AlphaCeiling](../alphaceiling) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([PresetShadow](../presetshadow)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [PresetShadow](../presetshadow) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([BiLevel](../bilevel)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [BiLevel](../bilevel) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |


---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([ColorReplace](../colorreplace)) | 从 IGenericCollection 中删除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [ColorReplace](../colorreplace) | 要从 IGenericCollection 中删除的对象。 |

**返回：**
boolean

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | IGenericCollection 为只读。 |
---


### removeItem {#removeItem}

| 名称 | 描述 |
| --- | --- |
| removeItem ([Tint](../tint)) | 从 IGenericCollection 中移除特定对象的第一次出现。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [Tint](../tint) | 要从 IGenericCollection 中移除的对象。 |

 **返回值:**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | IGenericCollection 是只读的。 |


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中图像效果的数量。只读 int。 |

 **返回值:**
int


---