---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: 表示投影片的大小和方向。
type: docs
url: /zh-hant/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

表示投影片的大小和方向。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 取得投影片的尺寸（以點為單位）。 |
| [getType()](#getType--) | 取得投影片的大小類型。 |
| [getOrientation()](#getOrientation--) | 取得或設定投影片的方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 取得或設定投影片的方向。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 依類型設定投影片大小並縮放現有內容。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 明確設定投影片尺寸並縮放現有內容。 |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

取得投影片的尺寸（以點為單位）。

--------------------

指派新值會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**傳回:**
[SizeF](../../com.aspose.slides.android/sizef)

### getType() {#getType--}
```
public abstract int getType()
```

取得投影片的大小類型。

--------------------

指派除 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 之外的任何值，會根據預先定義的尺寸調整 \#getSize.getSize，同時保留目前的 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**傳回:**
int

### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

取得或設定投影片的方向。

--------------------

變更此值會交換投影片的寬度與高度。

**傳回:**
int

### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

取得或設定投影片的方向。

--------------------

變更此值會交換投影片的寬度與高度。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

依類型設定投影片大小並縮放現有內容。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要套用的預先定義投影片大小。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

指派除 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 之外的任何值，會根據選取的類型調整 \#getSize.getSize，同時保留 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

明確設定投影片尺寸並縮放現有內容。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | float | 新的投影片寬度（單位：點）。 |
| height | float | 新的投影片高度（單位：點）。 |
| scaleType | int | 要使用的內容縮放模式。 |

--------------------

這會將 \#getType.getType 屬性重設為 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，並設定 \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |