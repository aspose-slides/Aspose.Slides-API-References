---
title: ISVGOptions
second_title: Aspose.Slides for Java API 參考
description: 表示 SVG 選項。
type: docs
url: /zh-hant/com.aspose.slides/isvgoptions/
---
**所有已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

表示 SVG 選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | 判斷投影片上的文字是否將保存為圖形。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 判斷投影片上的文字是否將保存為圖形。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 返回或設定圖形檔光柵化的較低解析度限制。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 返回或設定圖形檔光柵化的較低解析度限制。 |
| [getDisable3DText()](#getDisable3DText--) | 判斷 SVG 中的 3D 文字是否已停用。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | 判斷 SVG 中的 3D 文字是否已停用。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 無法定義標記的內縮。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 無法定義標記的內縮。 |
| [getJpegQuality()](#getJpegQuality--) | 判斷 JPEG 編碼品質。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 判斷 JPEG 編碼品質。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 返回並設定回呼介面，允許使用者控制形狀轉換。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 返回並設定回呼介面，允許使用者控制形狀轉換。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示圖片壓縮等級 讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示圖片壓縮等級 讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布林旗標指示裁剪的部分是否仍作為文件的一部分。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布林旗標指示裁剪的部分是否仍作為文件的一部分。 |
| [getUseFrameSize()](#getUseFrameSize--) | 判斷文字框是否會包含在渲染區域中。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 判斷文字框是否會包含在渲染區域中。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | 判斷在渲染時是否執行形狀指定的旋轉。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 判斷在渲染時是否執行形狀指定的旋轉。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 判斷外部載入字型的處理方式。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 判斷外部載入字型的處理方式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 取得或設定一個值，指示文字在渲染時是否不使用連字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 取得或設定一個值，指示文字在渲染時是否不使用連字。 |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

判斷投影片上的文字是否將保存為圖形。讀寫 boolean.

**返回值：**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

判斷投影片上的文字是否將保存為圖形。讀寫 boolean.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

返回或設定圖形檔光柵化的較低解析度限制。讀寫 int。

**返回值：**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

返回或設定圖形檔光柵化的較低解析度限制。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

判斷 SVG 中的 3D 文字是否已停用。讀寫 boolean。

**返回值：**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

判斷 SVG 中的 3D 文字是否已停用。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

停用 FromCornerX 與 FromCenter 漸層的分割。讀寫 boolean。

**返回值：**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

停用 FromCornerX 與 FromCenter 漸層的分割。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 無法定義標記的內縮。Aspose.Slides SVG 寫入引擎對此問題有變通方法：它會裁剪帶箭頭的線段末端，使線不會與標記重疊。此選項可關閉此行為。讀寫 boolean。

**返回值：**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 無法定義標記的內縮。Aspose.Slides SVG 寫入引擎對此問題有變通方法：它會裁剪帶箭頭的線段末端，使線不會與標記重疊。此選項可關閉此行為。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

判斷 JPEG 編碼品質。讀寫 int。

**返回值：**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

判斷 JPEG 編碼品質。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

返回並設定回呼介面，允許使用者控制形狀轉換。讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**返回值：**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

返回並設定回呼介面，允許使用者控制形狀轉換。讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

表示圖片壓縮等級 讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**返回值：**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

表示圖片壓縮等級 讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

布林旗標指示裁剪的部分是否仍作為文件的一部分。若為 true，裁剪的部分將被移除；若為 false，將會序列化至文件中（可能導致檔案較大）。讀寫 boolean。

**返回值：**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

布林旗標指示裁剪的部分是否仍作為文件的一部分。若為 true，裁剪的部分將被移除；若為 false，將會序列化至文件中（可能導致檔案較大）。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

判斷文字框是否會包含在渲染區域中。讀寫 boolean。預設值為 false。

**返回值：**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

判斷文字框是否會包含在渲染區域中。讀寫 boolean。預設值為 false。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

判斷在渲染時是否執行形狀指定的旋轉。讀寫 boolean。預設值為 true。

**返回值：**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

判斷在渲染時是否執行形狀指定的旋轉。讀寫 boolean。預設值為 true。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

判斷外部載入字型的處理方式。讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**返回值：**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

判斷外部載入字型的處理方式。讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回值：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

取得或設定一個值，指示文字在渲染時是否不使用連字。設定為 true 時，渲染輸出將停用連字。預設情況下，此屬性設定為 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

取得或設定一個值，指示文字在渲染時是否不使用連字。設定為 true 時，渲染輸出將停用連字。預設情況下，此屬性設定為 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |