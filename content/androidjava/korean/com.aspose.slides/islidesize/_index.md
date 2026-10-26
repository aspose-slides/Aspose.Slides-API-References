---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: 슬라이드의 크기와 방향을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

슬라이드의 크기와 방향을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSize()](#getSize--) | 슬라이드 크기를 포인트 단위로 가져옵니다. |
| [getType()](#getType--) | 슬라이드 크기 유형을 가져옵니다. |
| [getOrientation()](#getOrientation--) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setOrientation(int value)](#setOrientation-int-) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 확대/축소합니다. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 슬라이드 크기를 명시적으로 설정하고 기존 콘텐츠를 확대/축소합니다. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


슬라이드 크기를 포인트 단위로 가져옵니다.

--------------------

새 값을 할당하면 \#getType.getType 속성이 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)(으)로 재설정되고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 설정합니다.

**반환값:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


슬라이드 크기 유형을 가져옵니다.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 \#getSize.getSize 가 사전 정의된 차원에 따라 조정되고, 현재 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 유지합니다.

**반환값:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 너비와 높이가 서로 바뀝니다.

**반환값:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 너비와 높이가 서로 바뀝니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 확대/축소합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| type | int | 적용할 미리 정의된 슬라이드 크기. |
| scaleType | int | 사용할 콘텐츠 확대/축소 모드. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 \#getSize.getSize 가 선택된 유형에 따라 조정되고, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 가 유지됩니다. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


슬라이드 크기를 명시적으로 설정하고 기존 콘텐츠를 확대/축소합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| width | float | 새 슬라이드 너비(포인트 단위). |
| height | float | 새 슬라이드 높이(포인트 단위). |
| scaleType | int | 사용할 콘텐츠 확대/축소 모드. |

--------------------

이것은 \#getType.getType 속성을 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)(으)로 재설정하고 \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 설정합니다. |