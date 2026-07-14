---  
title: SVGOptions  
second_title: Java API 참조를 통한 Android용 Aspose.Slides  
description: SVG 옵션을 나타냅니다.  
type: docs  
url: /ko/com.aspose.slides/svgoptions/  
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

SVG 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions 클래스의 새 인스턴스를 초기화합니다. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | 링크 임베딩 컨트롤러 개체를 지정하여 SVGOptions 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getUseFrameSize()](#getUseFrameSize--) | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. |
| [getUseFrameRotation()](#getUseFrameRotation--) | 렌더링 시 형태에 지정된 회전을 수행할지 여부를 결정합니다. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 렌더링 시 형태에 지정된 회전을 수행할지 여부를 결정합니다. |
| [getVectorizeText()](#getVectorizeText--) | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 메타파일 래스터화에 대한 낮은 해상도 한도를 반환하거나 설정합니다. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 메타파일 래스터화에 대한 낮은 해상도 한도를 반환하거나 설정합니다. |
| [getDisable3DText()](#getDisable3DText--) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. |
| [getDefault()](#getDefault--) | 기본 설정을 반환합니다. |
| [getSimple()](#getSimple--) | 가장 간단하고 작은 SVG 파일 생성을 위한 설정을 반환합니다. |
| [getWYSIWYG()](#getWYSIWYG--) | 가장 정확한 SVG 파일 생성을 위한 설정을 반환합니다. |
| [getJpegQuality()](#getJpegQuality--) | JPEG 인코딩 품질을 결정합니다. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG 인코딩 품질을 결정합니다. |
| [getShapeFormattingController()](#getShapeFormattingController--) | 형태 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 형태 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. |
| [getPicturesCompression()](#getPicturesCompression--) | 그림 압축 레벨을 나타냅니다. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 그림 압축 레벨을 나타냅니다. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 잘린 부분이 문서의 일부로 유지되는지 여부를 나타내는 부울 플래그입니다. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 잘린 부분이 문서의 일부로 유지되는지 여부를 나타내는 부울 플래그입니다. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

SVGOptions 클래스의 새 인스턴스를 초기화합니다.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

링크 임베딩 컨트롤러 개체를 지정하여 SVGOptions 클래스의 새 인스턴스를 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 링크 임베딩 컨트롤러 참조. |

--------------------

링크 임베딩 컨트롤러는 리소스(예: 이미지)를 임베드할지 외부 리소스로 참조할지 결정하는 역할을 하는 위임 객체입니다. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환값:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

**반환값:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

렌더링 시 형태에 지정된 회전을 수행할지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 true입니다.

**반환값:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

렌더링 시 형태에 지정된 회전을 수행할지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

메타파일 래스터화에 대한 낮은 해상도 한도를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환값:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

메타파일 래스터화에 대한 낮은 해상도 한도를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. Aspose.Slides SVG 작성 엔진은 해당 문제에 대한 해결책으로 화살표가 있는 선의 끝을 잘라 마커와 겹치지 않게 합니다. 이 옵션은 해당 동작을 끕니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. Aspose.Slides SVG 작성 엔진은 해당 문제에 대한 해결책으로 화살표가 있는 선의 끝을 잘라 마커와 겹치지 않게 합니다. 이 옵션은 해당 동작을 끕니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

기본 설정을 반환합니다. 읽기 전용 [SVGOptions](../../com.aspose.slides/svgoptions).

**반환값:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

가장 간단하고 작은 SVG 파일 생성을 위한 설정을 반환합니다. 읽기 전용 [SVGOptions](../../com.aspose.slides/svgoptions).

**반환값:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

가장 정확한 SVG 파일 생성을 위한 설정을 반환합니다. 읽기 전용 [SVGOptions](../../com.aspose.slides/svgoptions).

**반환값:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG 인코딩 품질을 결정합니다. 읽기/쓰기 int.

**반환값:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG 인코딩 품질을 결정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

형태 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. 읽기/쓰기 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**반환값:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

형태 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. 읽기/쓰기 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

그림 압축 레벨을 나타냅니다.

**반환값:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

그림 압축 레벨을 나타냅니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

잘린 부분이 문서의 일부로 유지되는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일 크기가 커질 수 있음).

**반환값:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

잘린 부분이 문서의 일부로 유지되는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일 크기가 커질 수 있음).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기/쓰기 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**반환값:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기/쓰기 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 출력에서 리가처가 비활성화됩니다. 기본값은 false입니다.

**반환값:**
boolean

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 출력에서 리가처가 비활성화됩니다. 기본값은 false입니다.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |