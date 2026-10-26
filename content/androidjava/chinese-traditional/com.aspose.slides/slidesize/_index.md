---
title: SlideSize
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片的大小與方向。
type: docs
url: /zh-hant/com.aspose.slides/slidesize/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

表示投影片的大小與方向。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSize()](#getSize--) | 取得投影片的尺寸（以點為單位）。 |
| [getType()](#getType--) | 取得投影片的尺寸類型。 |
| [getOrientation()](#getOrientation--) | 取得或設定投影片的方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 取得或設定投影片的方向。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 依類型設定投影片尺寸，並縮放現有內容。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 明確設定投影片尺寸，並縮放現有內容。 |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


取得投影片的尺寸（以點為單位）。

--------------------

指派新值會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**傳回：**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


取得投影片的尺寸類型。

--------------------

指派任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值會依預先定義的尺寸調整 \#getSize.getSize，同時保留目前的 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**傳回：**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


取得或設定投影片的方向。

--------------------

變更此值會交換投影片的寬度與高度。

**傳回：**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


取得或設定投影片的方向。

--------------------

變更此值會交換投影片的寬度與高度。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


依類型設定投影片尺寸，並縮放現有內容。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要套用的預先定義投影片尺寸。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

指派任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值會根據所選類型調整 \#getSize.getSize，同時保留 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


明確設定投影片尺寸，並縮放現有內容。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | float | 新的投影片寬度（以點為單位）。 |
| height | float | 新的投影片高度（以點為單位）。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

此動作會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |