---
title: CommonSlideViewProperties
second_title: Aspose.Slides for Java API 參考文件
description: 代表一般投影片檢視屬性。
type: docs
url: /zh-hant/com.aspose.slides/commonslideviewproperties/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

代表一般投影片檢視屬性。

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // 建立代表投影片檔案的 Presentation 物件
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 設定投影片檢視屬性
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // 投影片檢視的縮放百分比值
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // 投影片備註檢視的縮放百分比值
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getScale()](#getScale--) | 指定檢視的縮放比例（以百分比表示）。 |
| [setScale(int value)](#setScale-int-) | 指定檢視的縮放比例（以百分比表示）。 |
| [getVariableScale()](#getVariableScale--) | 指定檢視內容應自動縮放以最佳適應目前的視窗大小。 |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | 指定檢視內容應自動縮放以最佳適應目前的視窗大小。 |
| [getDrawingGuides()](#getDrawingGuides--) | 傳回繪圖參考線的集合。 |
### getScale() {#getScale--}
```
public final int getScale()
```

指定檢視的縮放比例（以百分比表示）。讀寫 int。

**傳回：**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

指定檢視的縮放比例（以百分比表示）。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

指定檢視內容應自動縮放以最佳適應目前的視窗大小。讀寫 boolean。

**傳回：**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

指定檢視內容應自動縮放以最佳適應目前的視窗大小。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

傳回繪圖參考線的集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // 在投影片中心右側新增垂直繪製參考線
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // 在投影片中心下方新增水平繪製參考線
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)