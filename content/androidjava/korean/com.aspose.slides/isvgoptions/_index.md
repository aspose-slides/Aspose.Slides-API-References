---
title: ISVGOptions
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: SVG 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isvgoptions/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | 슬라이드의 텍스트가 그래픽으로 저장되는지 여부를 결정합니다. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | 슬라이드의 텍스트가 그래픽으로 저장되는지 여부를 결정합니다. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | 메타파일 래스터화의 하위 해상도 제한을 반환하거나 설정합니다. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | 메타파일 래스터화의 하위 해상도 제한을 반환하거나 설정합니다. |
| [getDisable3DText()](#getDisable3DText--) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. |
| [getJpegQuality()](#getJpegQuality--) | JPEG 인코딩 품질을 결정합니다. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG 인코딩 품질을 결정합니다. |
| [getShapeFormattingController()](#getShapeFormattingController--) | 사용자가 형태 변환을 제어할 수 있도록 하는 콜백 인터페이스를 반환하고 설정합니다. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | 사용자가 형태 변환을 제어할 수 있도록 하는 콜백 인터페이스를 반환하고 설정합니다. |
| [getPicturesCompression()](#getPicturesCompression--) | 그림 압축 수준을 나타냅니다 읽기/쓰기 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 그림 압축 수준을 나타냅니다 읽기/쓰기 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. |
| [getUseFrameSize()](#getUseFrameSize--) | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. |
| [getUseFrameRotation()](#getUseFrameRotation--) | 렌더링 시 지정된 회전을 형태에 적용할지 여부를 결정합니다. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | 렌더링 시 지정된 회전을 형태에 적용할지 여부를 결정합니다. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 잉크 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 결합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 결합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

슬라이드의 텍스트가 그래픽으로 저장되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

슬라이드의 텍스트가 그래픽으로 저장되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

메타파일 래스터화의 하위 해상도 제한을 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**  
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

메타파일 래스터화의 하위 해상도 제한을 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. Aspose.Slides SVG 작성 엔진은 해당 문제를 회피하기 위해 화살표가 있는 선의 끝을 잘라냅니다. 이 옵션은 해당 동작을 끕니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다. Aspose.Slides SVG 작성 엔진은 해당 문제를 회피하기 위해 화살표가 있는 선의 끝을 잘라냅니다. 이 옵션은 해당 동작을 끕니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG 인코딩 품질을 결정합니다. 읽기/쓰기 int.

**반환:**  
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG 인코딩 품질을 결정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

사용자가 형태 변환을 제어할 수 있도록 하는 콜백 인터페이스를 반환하고 설정합니다. 읽기/쓰기 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**반환:**  
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

사용자가 형태 변환을 제어할 수 있도록 하는 콜백 인터페이스를 반환하고 설정합니다. 읽기/쓰기 [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

그림 압축 수준을 나타냅니다 읽기/쓰기 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**반환:**  
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

그림 압축 수준을 나타냅니다 읽기/쓰기 \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화되어 파일 크기가 커질 수 있습니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화되어 파일 크기가 커질 수 있습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

**반환:**  
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

렌더링 시 지정된 회전을 형태에 적용할지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 true입니다.

**반환:**  
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

렌더링 시 지정된 회전을 형태에 적용할지 여부를 결정합니다. 읽기/쓰기 boolean. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기/쓰기 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**반환:**  
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기/쓰기 [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

내보낸 문서에서 잉크 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

텍스트가 결합자를 사용하지 않고 렌더링되는지 여부를 가져오거나 설정합니다. true로 설정하면 렌더링 결과에서 결합자가 비활성화됩니다. 기본적으로 이 속성은 false로 설정됩니다.

--------------------

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

**반환:**  
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

텍스트가 결합자를 사용하지 않고 렌더링되는지 여부를 가져오거나 설정합니다. true로 설정하면 렌더링 결과에서 결합자가 비활성화됩니다. 기본적으로 이 속성은 false로 설정됩니다.

--------------------

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |