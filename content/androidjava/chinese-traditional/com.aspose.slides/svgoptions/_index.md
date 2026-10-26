---
title: SVGOptions
second_title: Aspose.Slides Android 版 Java API 參考
description: 代表 SVG 選項。
type: docs
url: /zh-hant/com.aspose.slides/svgoptions/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

代表 SVG 選項。

## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | 初始化 SVGOptions 類別的新執行個體。 |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | 初始化 SVGOptions 類別的新執行個體，並指定連結嵌入控制器物件。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getUseFrameSize()](#getUseFrameSize--) | 判斷文字框是否會包含在渲染區域中。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 判斷文字框是否會包含在渲染區域中。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | 判斷在渲染時是否對形狀執行指定的旋轉。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 判斷在渲染時是否對形狀執行指定的旋轉。 |
| [getVectorizeText()](#getVectorizeText--) | 判斷投影片上的文字是否會儲存為圖形。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 判斷投影片上的文字是否會儲存為圖形。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 取得或設定中繪檔光柵化的最低解析度限制。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 取得或設定中繪檔光柵化的最低解析度限制。 |
| [getDisable3DText()](#getDisable3DText--) | 判斷 SVG 中的 3D 文字是否已停用。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | 判斷 SVG 中的 3D 文字是否已停用。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 無法定義標記的內縮。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 無法定義標記的內縮。 |
| [getDefault()](#getDefault--) | 取得預設設定。 |
| [getSimple()](#getSimple--) | 取得產生最簡單與最小 SVG 檔案的設定。 |
| [getWYSIWYG()](#getWYSIWYG--) | 取得產生最精確 SVG 檔案的設定。 |
| [getJpegQuality()](#getJpegQuality--) | 判斷 JPEG 編碼品質。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 判斷 JPEG 編碼品質。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 取得並設定回呼介面，以允許使用者控制形狀轉換。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 取得並設定回呼介面，以允許使用者控制形狀轉換。 |
| [getPicturesCompression()](#getPicturesCompression--) | 代表圖片壓縮等級。 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 代表圖片壓縮等級。 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布林旗標，指示裁剪的部分是否保留在文件中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布林旗標，指示裁剪的部分是否保留在文件中。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 判斷外部載入字型的處理方式。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 判斷外部載入字型的處理方式。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 取得或設定一個值，指示文字是否在渲染時不使用連字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 取得或設定一個值，指示文字是否在渲染時不使用連字。 |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

初始化 SVGOptions 類別的新執行個體。

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

初始化 SVGOptions 類別的新執行個體，並指定連結嵌入控制器物件。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 連結嵌入控制器的參考。 |

--------------------

連結嵌入控制器是一個委派物件，負責決定資源（例如影像）是否需要嵌入或以外部資源參照。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**傳回值:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

判斷文字框是否會包含在渲染區域中。可讀寫 boolean。預設值為 false。

**傳回值:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

判斷文字框是否會包含在渲染區域中。可讀寫 boolean。預設值為 false。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

判斷在渲染時是否對形狀執行指定的旋轉。可讀寫 boolean。預設值為 true。

**傳回值:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

判斷在渲染時是否對形狀執行指定的旋轉。可讀寫 boolean。預設值為 true。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

判斷投影片上的文字是否會儲存為圖形。可讀寫 boolean。

**傳回值:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

判斷投影片上的文字是否會儲存為圖形。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

取得或設定中繪檔光柵化的最低解析度限制。可讀寫 int。

**傳回值:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

取得或設定中繪檔光柵化的最低解析度限制。可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

判斷 SVG 中的 3D 文字是否已停用。可讀寫 boolean。

**傳回值:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

判斷 SVG 中的 3D 文字是否已停用。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

停用 FromCornerX 與 FromCenter 漸層的分割。可讀寫 boolean。

**傳回值:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

停用 FromCornerX 與 FromCenter 漸層的分割。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 無法定義標記的內縮。Aspose.Slides SVG 寫入引擎針對此問題提供了替代方案：它會裁剪含箭頭的線段尾端，使線段不會與標記重疊。此選項可關閉此行為。可讀寫 boolean。

**傳回值:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 無法定義標記的內縮。Aspose.Slides SVG 寫入引擎針對此問題提供了替代方案：它會裁剪含箭頭的線段尾端，使線段不會與標記重疊。此選項可關閉此行為。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

取得預設設定。唯讀 [SVGOptions](../../com.aspose.slides/svgoptions)。

**傳回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

取得產生最簡單與最小 SVG 檔案的設定。唯讀 [SVGOptions](../../com.aspose.slides/svgoptions)。

**傳回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

取得產生最精確 SVG 檔案的設定。唯讀 [SVGOptions](../../com.aspose.slides/svgoptions)。

**傳回值:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

判斷 JPEG 編碼品質。可讀寫 int。

**傳回值:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

判斷 JPEG 編碼品質。可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

取得並設定回呼介面，以允許使用者控制形狀轉換。可讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**傳回值:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

取得並設定回呼介面，以允許使用者控制形狀轉換。可讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

代表圖片壓縮等級

**傳回值:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

代表圖片壓縮等級

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

布林旗標，指示裁剪的部分是否保留在文件中。若為 true，裁剪的部分將被移除；若為 false，則會序列化至文件中（可能導致檔案較大）。

**傳回值:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

布林旗標，指示裁剪的部分是否保留在文件中。若為 true，裁剪的部分將被移除；若為 false，則會序列化至文件中（可能導致檔案較大）。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

判斷外部載入字型的處理方式。可讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**傳回值:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

判斷外部載入字型的處理方式。可讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

取得或設定一個值，指示文字是否在渲染時不使用連字。設定為 true 時，渲染輸出將停用連字。預設為 false。

--------------------

> ```
> 範例：
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


**傳回值:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

取得或設定一個值，指示文字是否在渲染時不使用連字。設定為 true 時，渲染輸出將停用連字。預設為 false。

--------------------

> ```
> 範例：
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


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |