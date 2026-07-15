---
title: SmartArtShape
second_title: Aspose.Slides for Android via Java API 參考文件
description: 代表 SmartArt 形狀
type: docs
url: /zh-hant/com.aspose.slides/smartartshape/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有已實作的介面：**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

代表 SmartArt 形狀
## 方法

| Method | Description |
| --- | --- |
| [getShapeType()](#getShapeType--) | 取得或設定幾何預設類型。 |
| [setShapeType(int value)](#setShapeType-int-) | 取得或設定幾何預設類型。 |
| [getTextFrame()](#getTextFrame--) | 取得 SmartArt 形狀的文字。 |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

取得或設定幾何預設類型。注意：值變更時，所有調整值將重設為預設值。讀/寫 [ShapeType](../../com.aspose.slides/shapetype).

**傳回值：**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

取得或設定幾何預設類型。注意：值變更時，所有調整值將重設為預設值。讀/寫 [ShapeType](../../com.aspose.slides/shapetype).

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

取得 SmartArt 形狀的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe).

**傳回值：**
[ITextFrame](../../com.aspose.slides/itextframe)