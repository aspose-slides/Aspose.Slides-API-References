---
title: ViewProperties
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션 전체 뷰 속성.
type: docs
url: /ko/com.aspose.slides/viewproperties/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

프레젠테이션 전체 뷰 속성.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLastView()](#getLastView--) | 프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. |
| [setLastView(int value)](#setLastView-int-) | 프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. |
| [getShowComments()](#getShowComments--) | 슬라이드 주석을 표시할지 여부를 지정합니다. |
| [setShowComments(byte value)](#setShowComments-byte-) | 슬라이드 주석을 표시할지 여부를 지정합니다. |
| [getNormalViewProperties()](#getNormalViewProperties--) | 일반 보기 속성을 나타냅니다. |
| [getSlideViewProperties()](#getSlideViewProperties--) | 슬라이드 보기 모드와 연관된 공통 보기 속성을 지정합니다. |
| [getNotesViewProperties()](#getNotesViewProperties--) | 노트 보기 모드와 연관된 공통 보기 속성을 지정합니다. |
| [getGridSpacing()](#getGridSpacing--) | 프레젠테이션 문서의 기본 그리드에 사용될 그리드 간격을 포인트 단위로 반환하거나 설정합니다. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 프레젠테이션 문서의 기본 그리드에 사용될 그리드 간격을 포인트 단위로 반환하거나 설정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. 읽기/쓰기 [ViewType](../../com.aspose.slides/viewtype).

**반환:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. 읽기/쓰기 [ViewType](../../com.aspose.slides/viewtype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

슬라이드 주석을 표시할지 여부를 지정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

슬라이드 주석을 표시할지 여부를 지정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

일반 보기 속성을 나타냅니다. 일반 보기에는 슬라이드 자체, 측면 콘텐츠 영역, 하단 콘텐츠 영역의 세 가지 콘텐츠 영역이 포함됩니다. 읽기 전용 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**반환:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

슬라이드 보기 모드와 연관된 공통 보기 속성을 지정합니다. 읽기 전용 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**반환:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

노트 보기 모드와 연관된 공통 보기 속성을 지정합니다. 읽기 전용 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**반환:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

프레젠테이션 문서의 기본 그리드에 사용될 그리드 간격을 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm (2.8349607 포인트)에서 2 인치 (144 포인트)입니다.

**반환:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

프레젠테이션 문서의 기본 그리드에 사용될 그리드 간격을 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm (2.8349607 포인트)에서 2 인치 (144 포인트)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject