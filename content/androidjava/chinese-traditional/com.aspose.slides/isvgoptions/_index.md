---
title: ISVGOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表 SVG 選項。
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

| 方法 | 說明 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | 決定投影片上的文字是否會以圖形方式儲存。 |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 決定投影片上的文字是否會以圖形方式儲存。 |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 取得或設定中繪圖檔光柵化的最低解析度限制。 |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 取得或設定中繪圖檔光柵化的最低解析度限制。 |
| [getDisable3DText()](#getDisable3DText--) | 決定 SVG 中的 3D 文字是否被停用。 |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | 決定 SVG 中的 3D 文字是否被停用。 |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | 停用 FromCornerX 與 FromCenter 漸層的分割。 |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 無法為標記定義內縮。 |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 無法為標記定義內縮。 |
| [getJpegQuality()](#getJpegQuality--) | 決定 JPEG 編碼品質。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 決定 JPEG 編碼品質。 |
| [getShapeFormattingController()](#getShapeFormattingController--) | 取得並設定回呼介面，讓使用者能控制形狀轉換。 |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 取得並設定回呼介面，讓使用者能控制形狀轉換。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示圖片壓縮等級 可讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示圖片壓縮等級 可讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布林旗標指示裁剪部分是否仍保留於文件中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布林旗標指示裁剪部分是否仍保留於文件中。 |
| [getUseFrameSize()](#getUseFrameSize--) | 決定文字框是否會被包含在渲染區域中。 |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 決定文字框是否會被包含在渲染區域中。 |
| [getUseFrameRotation()](#getUseFrameRotation--) | 決定在渲染時是否執行形狀的指定旋轉。 |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 決定在渲染時是否執行形狀的指定旋轉。 |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 決定外部載入字型的處理方式。 |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 決定外部載入字型的處理方式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制匯出文件中 Ink 物件外觀的選項。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 取得或設定一個值，以指示文字是否在渲染時不使用連字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 取得或設定一個值，以指示文字是否在渲染時不使用連字。 |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

決定投影片上的文字是否會以圖形方式儲存。 可讀寫布林。

**返回值:**  
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

決定投影片上的文字是否會以圖形方式儲存。 可讀寫布林。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

取得或設定中繪圖檔光柵化的最低解析度限制。 可讀寫整數。

**返回值:**  
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

取得或設定中繪圖檔光柵化的最低解析度限制。 可讀寫整數。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

決定 SVG 中的 3D 文字是否被停用。 可讀寫布林。

**返回值:**  
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

決定 SVG 中的 3D 文字是否被停用。 可讀寫布林。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

停用 FromCornerX 與 FromCenter 漸層的分割。 可讀寫布林。

**返回值:**  
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

停用 FromCornerX 與 FromCenter 漸層的分割。 可讀寫布林。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 無法為標記定義內縮。 Aspose.Slides SVG 寫入引擎對此問題有替代方案：它會裁剪帶箭頭的線段末端，使線段不會與標記重疊。此選項可關閉此行為。 可讀寫布林。

**返回值:**  
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 無法為標記定義內縮。 Aspose.Slides SVG 寫入引擎對此問題有替代方案：它會裁剪帶箭頭的線段末端，使線段不會與標記重疊。此選項可關閉此行為。 可讀寫布林。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

決定 JPEG 編碼品質。 可讀寫整數。

**返回值:**  
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

決定 JPEG 編碼品質。 可讀寫整數。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

取得並設定回呼介面，讓使用者能控制形狀轉換。 可讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**返回值:**  
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

取得並設定回呼介面，讓使用者能控制形狀轉換。 可讀寫 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

表示圖片壓縮等級 可讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**返回值:**  
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

表示圖片壓縮等級 可讀寫 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

布林旗標指示裁剪部分是否仍保留於文件中。 若為 true，裁剪部分將被移除；若為 false，則會序列化於文件中（可能導致檔案變大）。 可讀寫布林。

**返回值:**  
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

布林旗標指示裁剪部分是否仍保留於文件中。 若為 true，裁剪部分將被移除；若為 false，則會序列化於文件中（可能導致檔案變大）。 可讀寫布林。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

決定文字框是否會被包含在渲染區域中。 可讀寫布林。 預設值為 false。

**返回值:**  
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

決定文字框是否會被包含在渲染區域中。 可讀寫布林。 預設值為 false。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

決定在渲染時是否執行形狀的指定旋轉。 可讀寫布林。 預設值為 true。

**返回值:**  
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

決定在渲染時是否執行形狀的指定旋轉。 可讀寫布林。 預設值為 true。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

決定外部載入字型的處理方式。 可讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**返回值:**  
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

決定外部載入字型的處理方式。 可讀寫 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制匯出文件中 Ink 物件外觀的選項。 唯讀 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回值:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

取得或設定一個值，以指示文字是否在渲染時不使用連字。 設為 true 時，渲染輸出將停用連字。 預設為 false。

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


**返回值:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

取得或設定一個值，以指示文字是否在渲染時不使用連字。 設為 true 時，渲染輸出將停用連字。 預設為 false。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |