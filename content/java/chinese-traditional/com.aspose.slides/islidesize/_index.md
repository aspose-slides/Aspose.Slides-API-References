---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: 表示投影片的大小與方向。
type: docs
url: /zh-hant/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

表示投影片的大小與方向。
## 方法

| Method | 說明 |
| --- | --- |
| [getSize()](#getSize--) | 取得投影片尺寸（點數）。 |
| [getType()](#getType--) | 取得投影片大小類型。 |
| [getOrientation()](#getOrientation--) | 取得或設定投影片方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 取得或設定投影片方向。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 依類型設定投影片大小，並縮放現有內容。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 明確設定投影片尺寸，並縮放現有內容。 |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


取得投影片尺寸（點數）。

--------------------

指派新值會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**返回:**  
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


取得投影片大小類型。

--------------------

指派任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值時，會根據預先定義的尺寸調整 \#getSize.getSize，同時保留目前的 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**返回:**  
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


取得或設定投影片方向。

--------------------

變更此值會交換投影片的寬度與高度。

**返回:**  
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


取得或設定投影片方向。

--------------------

變更此值會交換投影片的寬度與高度。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


依類型設定投影片大小，並縮放現有內容。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 要套用的預定義投影片大小。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

指派任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值時，會根據所選類型調整 \#getSize.getSize，同時保留 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


明確設定投影片尺寸，並縮放現有內容。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | 以點數為單位的新投影片寬度。 |
| height | float | 以點數為單位的新投影片高度。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

此操作會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |