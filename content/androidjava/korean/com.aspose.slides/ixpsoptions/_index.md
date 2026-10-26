---
title: IXpsOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 XPS 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/ixpsoptions/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

프레젠테이션을 XPS 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 각 슬라이드 주변에 검은 프레임을 그리려면 true |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 각 슬라이드 주변에 검은 프레임을 그리려면 true |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다 |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **true**입니다.

**반환:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **true**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

각 슬라이드 주변에 검은 프레임을 그리려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **false**입니다.

**반환:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

각 슬라이드 주변에 검은 프레임을 그리려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false.

**반환:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |