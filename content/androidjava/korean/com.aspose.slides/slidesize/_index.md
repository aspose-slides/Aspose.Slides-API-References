---
title: SlideSize
second_title: Android용 Aspose.Slides Java API 참조
description: 슬라이드의 크기와 방향을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slidesize/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)  
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

슬라이드의 크기와 방향을 나타냅니다.

## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | 슬라이드 차원을 포인트 단위로 가져옵니다. |
| [getType()](#getType--) | 슬라이드 크기 유형을 가져옵니다. |
| [getOrientation()](#getOrientation--) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setOrientation(int value)](#setOrientation-int-) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 확대/축소합니다. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 슬라이드 차원을 명시적으로 설정하고 기존 콘텐츠를 확대/축소합니다. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

슬라이드 차원을 포인트 단위로 가져옵니다.

--------------------

새 값을 할당하면 \#getType.getType 속성이 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 로 재설정되고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 가 설정됩니다.

**Returns:**  
[SizeF](../../com.aspose.slides.android/sizef)

### getType() {#getType--}
```
public final int getType()
```

슬라이드 크기 유형을 가져옵니다.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 미리 정의된 차원에 따라 \#getSize.getSize 가 조정되며, 현재 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 은 유지됩니다.

**Returns:**  
int

### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 너비와 높이가 서로 교환됩니다.

**Returns:**  
int

### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 너비와 높이가 서로 교환됩니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 확대/축소합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 적용할 미리 정의된 슬라이드 크기입니다. |
| scaleType | int | 사용할 콘텐츠 확대/축소 모드입니다. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 선택된 유형에 따라 \#getSize.getSize 가 조정되며, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 은 유지됩니다. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

슬라이드 차원을 명시적으로 설정하고 기존 콘텐츠를 확대/축소합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | 새 슬라이드 너비(포인트 단위)입니다. |
| height | float | 새 슬라이드 높이(포인트 단위)입니다. |
| scaleType | int | 사용할 콘텐츠 확대/축소 모드입니다. |

--------------------

이 작업은 \#getType.getType 속성을 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 로 재설정하고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 설정합니다. |