---
title: XpsOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 XPS 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/xpsoptions/
---
**상속:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

프레젠테이션을 XPS 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // 프레젠테이션을 XPS 문서로 저장합니다
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions 클래스를 인스턴스화합니다
>      XpsOptions options = new XpsOptions();
>      // 메타파일을 PNG로 저장합니다
>      options.setSaveMetafilesAsPng(true);
>      // 프레젠테이션을 XPS 문서로 저장합니다
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | 기본 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 각 슬라이드 주위에 검은 프레임을 그리려면 true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 각 슬라이드 주위에 검은 프레임을 그리려면 true. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


기본 생성자.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**반환값:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **true**입니다.

**반환값:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
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
public final boolean getDrawSlidesFrame()
```


각 슬라이드 주위에 검은 프레임을 그리려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **false**입니다.

**반환값:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


각 슬라이드 주위에 검은 프레임을 그리려면 true. 읽기/쓰기 부울.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |