---
title: SlideSize
second_title: Java용 Aspose.Slides API 참조
description: 슬라이드의 크기와 방향을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slidesize/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

슬라이드의 크기와 방향을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSize()](#getSize--) | 슬라이드 크기를 포인트 단위로 가져옵니다. |
| [getType()](#getType--) | 슬라이드 크기 유형을 가져옵니다. |
| [getOrientation()](#getOrientation--) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setOrientation(int value)](#setOrientation-int-) | 슬라이드 방향을 가져오거나 설정합니다. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 스케일합니다. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 슬라이드 크기를 명시적으로 설정하고 기존 콘텐츠를 스케일합니다. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

슬라이드 크기를 포인트 단위로 가져옵니다.

--------------------

새 값을 할당하면 \#getType.getType 속성을 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 로 재설정하고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)를 설정합니다.

**반환값:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

슬라이드 크기 유형을 가져옵니다.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 사전 정의된 치수에 따라 \#getSize.getSize 를 조정하고 현재 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 유지합니다.

**반환값:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 가로와 세로가 서로 바뀝니다.

**반환값:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

슬라이드 방향을 가져오거나 설정합니다.

--------------------

이 값을 변경하면 슬라이드의 가로와 세로가 서로 바뀝니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

유형에 따라 슬라이드 크기를 설정하고 기존 콘텐츠를 스케일합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| type | int | 적용할 사전 정의된 슬라이드 크기. |
| scaleType | int | 사용할 콘텐츠 스케일링 모드. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 이외의 값을 할당하면 선택된 유형에 따라 \#getSize.getSize 를 조정하고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 보존합니다. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

슬라이드 크기를 명시적으로 설정하고 기존 콘텐츠를 스케일합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| width | float | 새 슬라이드 너비(포인트 단위). |
| height | float | 새 슬라이드 높이(포인트 단위). |
| scaleType | int | 사용할 콘텐츠 스케일링 모드. |

--------------------

이것은 \#getType.getType 속성을 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 로 재설정하고 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 를 설정합니다. |