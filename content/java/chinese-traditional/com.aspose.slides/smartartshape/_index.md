---
title: SmartArtShape
second_title: Aspose.Slides for Java API 參考
description: 表示 SmartArt 形狀
type: docs
url: /zh-hant/com.aspose.slides/smartartshape/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有已實作的介面:**  
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)  
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

表示 SmartArt 形狀
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeType()](#getShapeType--) | 返回或設定幾何預設類型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或設定幾何預設類型。 |
| [getTextFrame()](#getTextFrame--) | 返回 SmartArt 形狀的文字。 |

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或設定幾何預設類型。註：變更值時，所有調整值將重設為其預設值。讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**返回:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或設定幾何預設類型。註：變更值時，所有調整值將重設為其預設值。讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回 SmartArt 形狀的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回:**  
[ITextFrame](../../com.aspose.slides/itextframe)