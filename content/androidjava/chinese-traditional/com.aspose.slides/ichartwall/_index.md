---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: 代表 3d 圖表上的牆壁。
type: docs
url: /zh-hant/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

代表牆壁在 3d 圖表上。
## Methods

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | 返回或設定牆壁厚度，作為繪圖體積最大尺寸的百分比。 |
| [setThickness(int value)](#setThickness-int-) | 返回或設定牆壁厚度，作為繪圖體積最大尺寸的百分比。 |
| [getFormat()](#getFormat--) | 返回牆壁的填充、線條、效果、3d 樣式。 |
| [getPictureType()](#getPictureType--) | 返回或設定圖片類型。 |
| [setPictureType(int value)](#setPictureType-int-) | 返回或設定圖片類型。 |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

返回或設定牆壁厚度，作為繪圖體積最大尺寸的百分比。 讀寫 int。

**返回：**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

返回或設定牆壁厚度，作為繪圖體積最大尺寸的百分比。 讀寫 int。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回牆壁的填充、線條、效果、3d 樣式。 唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

返回或設定圖片類型。 讀寫 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int))。

**返回：**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

返回或設定圖片類型。 讀寫 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int))。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |