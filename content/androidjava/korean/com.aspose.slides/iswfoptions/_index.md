---
title: ISwfOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 SWF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/iswfoptions/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

프레젠테이션을 SWF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 생성된 SWF 문서를 압축할지 여부를 지정합니다. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 생성된 SWF 문서를 압축할지 여부를 지정합니다. |
| [getViewerIncluded()](#getViewerIncluded--) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. |
| [getShowPageBorder()](#getShowPageBorder--) | 페이지 주변의 테두리를 표시할지 여부를 지정합니다. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 페이지 주변의 테두리를 표시할지 여부를 지정합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getShowFullScreen()](#getShowFullScreen--) | 전체 화면 버튼을 표시하거나 숨깁니다. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 전체 화면 버튼을 표시하거나 숨깁니다. |
| [getShowPageStepper()](#getShowPageStepper--) | 페이지 단계 조절기를 표시하거나 숨깁니다. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | 페이지 단계 조절기를 표시하거나 숨깁니다. |
| [getShowSearch()](#getShowSearch--) | 검색 섹션을 표시하거나 숨깁니다. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 검색 섹션을 표시하거나 숨깁니다. |
| [getShowTopPane()](#getShowTopPane--) | 상단 전체 패널을 표시하거나 숨깁니다. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 상단 전체 패널을 표시하거나 숨깁니다. |
| [getShowBottomPane()](#getShowBottomPane--) | 하단 패널을 표시하거나 숨깁니다. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 하단 패널을 표시하거나 숨깁니다. |
| [getShowLeftPane()](#getShowLeftPane--) | 왼쪽 패널을 표시하거나 숨깁니다. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 왼쪽 패널을 표시하거나 숨깁니다. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 왼쪽 패널을 열려 있는 상태로 시작합니다. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 왼쪽 패널을 열려 있는 상태로 시작합니다. |
| [getEnableContextMenu()](#getEnableContextMenu--) | 컨텍스트 메뉴를 사용하거나 사용 안 함합니다. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 컨텍스트 메뉴를 사용하거나 사용 안 함합니다. |
| [getLogoImageBytes()](#getLogoImageBytes--) | 뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. |
| [getLogoLink()](#getLogoLink--) | 로고의 전체 하이퍼링크 주소를 가져오거나 설정합니다. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 로고의 전체 하이퍼링크 주소를 가져오거나 설정합니다. |
| [getJpegQuality()](#getJpegQuality--) | JPEG 이미지의 품질을 지정합니다. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG 이미지의 품질을 지정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 true입니다.

**반환값:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 true입니다.

**반환값:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

페이지 주변의 테두리를 표시할지 여부를 지정합니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

페이지 주변의 테두리를 표시할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**반환값:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

전체 화면 버튼을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

전체 화면 버튼을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

페이지 단계 조절기를 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

페이지 단계 조절기를 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

검색 섹션을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

검색 섹션을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

상단 전체 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

상단 전체 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

하단 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

하단 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

왼쪽 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환값:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

왼쪽 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

왼쪽 패널을 열려 있는 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다.

**반환값:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

왼쪽 패널을 열려 있는 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

컨텍스트 메뉴를 사용하거나 사용 안 함합니다. 기본값은 true입니다.

**반환값:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

컨텍스트 메뉴를 사용하거나 사용 안 함합니다. 기본값은 true입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. 이미지는 32x64 픽셀 PNG이어야 하며, 그렇지 않으면 로고가 올바르게 표시되지 않을 수 있습니다.

**반환값:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. 이미지는 32x64 픽셀 PNG이어야 하며, 그렇지 않으면 로고가 올바르게 표시되지 않을 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

로고의 전체 하이퍼링크 주소를 가져오거나 설정합니다. (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[]))가 지정된 경우에만 효과가 있습니다.

**반환값:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

로고의 전체 하이퍼링크 주소를 가져오거나 설정합니다. (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[]))가 지정된 경우에만 효과가 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG 이미지의 품질을 지정합니다. 기본값은 95입니다.

**반환값:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG 이미지의 품질을 지정합니다. 기본값은 95입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). 이 속성은 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 유형의 개체 할당을 지원하지 않습니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). 이 속성은 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 유형의 개체 할당을 지원하지 않습니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |