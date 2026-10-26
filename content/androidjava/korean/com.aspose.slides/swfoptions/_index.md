---
title: SwfOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 Swf 형식으로 저장하는 방법을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/swfoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)  
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

프레젠테이션을 Swf 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 개체를 인스턴스화합니다
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // 프레젠테이션 및 노트 페이지를 저장합니다
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | 기본 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getCompressed()](#getCompressed--) | 생성된 SWF 문서를 압축할지 여부를 지정합니다. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 생성된 SWF 문서를 압축할지 여부를 지정합니다. |
| [getViewerIncluded()](#getViewerIncluded--) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. |
| [getShowPageBorder()](#getShowPageBorder--) | 페이지 주위의 테두리를 표시할지 여부를 지정합니다. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 페이지 주위의 테두리를 표시할지 여부를 지정합니다. |
| [getShowFullScreen()](#getShowFullScreen--) | 전체 화면 버튼을 표시/숨깁니다. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 전체 화면 버튼을 표시/숨깁니다. |
| [getShowPageStepper()](#getShowPageStepper--) | 페이지 스테퍼를 표시/숨깁니다. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | 페이지 스테퍼를 표시/숨깁니다. |
| [getShowSearch()](#getShowSearch--) | 검색 섹션을 표시/숨깁니다. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 검색 섹션을 표시/숨깁니다. |
| [getShowTopPane()](#getShowTopPane--) | 전체 상단 패인을 표시/숨깁니다. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 전체 상단 패인을 표시/숨깁니다. |
| [getShowBottomPane()](#getShowBottomPane--) | 하단 패인을 표시/숨깁니다. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 하단 패인을 표시/숨깁니다. |
| [getShowLeftPane()](#getShowLeftPane--) | 왼쪽 패인을 표시/숨깁니다. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 왼쪽 패인을 표시/숨깁니다. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 왼쪽 패인을 열린 상태로 시작합니다. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 왼쪽 패인을 열린 상태로 시작합니다. |
| [getEnableContextMenu()](#getEnableContextMenu--) | 컨텍스트 메뉴를 활성화/비활성화합니다. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 컨텍스트 메뉴를 활성화/비활성화합니다. |
| [getLogoImageBytes()](#getLogoImageBytes--) | 뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. |
| [getLogoLink()](#getLogoLink--) | 로고에 대한 전체 하이퍼링크 주소를 가져오거나 설정합니다. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 로고에 대한 전체 하이퍼링크 주소를 가져오거나 설정합니다. |
| [getJpegQuality()](#getJpegQuality--) | JPEG 이미지의 품질을 지정합니다. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG 이미지의 품질을 지정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

기본 생성자.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false입니다.

**반환:**  
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

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 true입니다.

**반환:**  
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 true입니다.

**반환:**  
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

페이지 주위의 테두리를 표시할지 여부를 지정합니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

페이지 주위의 테두리를 표시할지 여부를 지정합니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

전체 화면 버튼을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

전체 화면 버튼을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

페이지 스테퍼를 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

페이지 스테퍼를 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

검색 섹션을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

검색 섹션을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

전체 상단 패인을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

전체 상단 패인을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

하단 패인을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

하단 패인을 표시/숨깁니다. flashmates에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

왼쪽 패인을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**반환:**  
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

왼쪽 패인을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

왼쪽 패인을 열린 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다.

**반환:**  
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

왼쪽 패인을 열린 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

컨텍스트 메뉴를 활성화/비활성화합니다. 기본값은 true입니다.

**반환:**  
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

컨텍스트 메뉴를 활성화/비활성화합니다. 기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. 이미지 크기는 32x64 픽셀 PNG 이미지여야 하며, 그렇지 않을 경우 로고가 제대로 표시되지 않을 수 있습니다.

**반환:**  
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

뷰어 오른쪽 상단에 로고로 표시될 이미지입니다. 이미지 크기는 32x64 픽셀 PNG 이미지여야 하며, 그렇지 않을 경우 로고가 제대로 표시되지 않을 수 있습니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

로고에 대한 전체 하이퍼링크 주소를 가져오거나 설정합니다. (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[]))이 지정된 경우에만 효과가 있습니다.

**반환:**  
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

로고에 대한 전체 하이퍼링크 주소를 가져오거나 설정합니다. (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[]))이 지정된 경우에만 효과가 있습니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG 이미지의 품질을 지정합니다. 기본값은 95입니다.

**반환:**  
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG 이미지의 품질을 지정합니다. 기본값은 95입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). 이 속성은 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 유형의 객체 할당을 지원하지 않습니다.

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

**반환:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). 이 속성은 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 유형의 객체 할당을 지원하지 않습니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |