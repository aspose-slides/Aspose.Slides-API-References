---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /zh-hant/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

表示 3d 圖表上的牆壁。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getThickness()](#getThickness--) | 返回或設定牆壁厚度，作為繪圖體積最大維度的百分比。 |
| [setThickness(int value)](#setThickness-int-) | 返回或設定牆壁厚度，作為繪圖體積最大維度的百分比。 |
| [getFormat()](#getFormat--) | 返回牆壁的填充、線條、效果、3D 風格。 |
| [getPictureType()](#getPictureType--) | 返回或設定圖片類型。 |
| [setPictureType(int value)](#setPictureType-int-) | 返回或設定圖片類型。 |

### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

返回或設定牆壁厚度，作為繪圖體積最大維度的百分比。可讀寫 int。

**返回:**  
int

### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

返回或設定牆壁厚度，作為繪圖體積最大維度的百分比。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回牆壁的填充、線條、效果、3D 風格。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)

### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

返回或設定圖片類型。可讀寫 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int))。

**返回:**  
int

### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

返回或設定圖片類型。可讀寫 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int))。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |