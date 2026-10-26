---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 表示共用投影片檢視屬性。
type: docs
url: /zh-hant/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

表示共用投影片檢視屬性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getScale()](#getScale--) | 指定檢視縮放比例（百分比）。 |
| [setScale(int value)](#setScale-int-) | 指定檢視縮放比例（百分比）。 |
| [getVariableScale()](#getVariableScale--) | 指定檢視內容應自動縮放以最佳符合目前視窗大小。 |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | 指定檢視內容應自動縮放以最佳符合目前視窗大小。 |
| [getDrawingGuides()](#getDrawingGuides--) | 返回繪圖參考線的集合。 |

### getScale() {#getScale--}
```
public abstract int getScale()
```

指定檢視縮放比例（百分比）。讀寫 int。

**返回:**  
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

指定檢視縮放比例（百分比）。讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

指定檢視內容應自動縮放以最佳符合目前視窗大小。讀寫 boolean。

**返回:**  
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

指定檢視內容應自動縮放以最佳符合目前視窗大小。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

返回繪圖參考線的集合。唯讀 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // 在投影片中心右側新增垂直繪製參考線
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // 在投影片中心下方新增水平繪製參考線
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)