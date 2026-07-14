---
title: MarkdownSaveOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 마크다운으로 저장하는 방식을 제어하는 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/markdownsaveoptions/
---
**상속:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)  
```
public class MarkdownSaveOptions extends SaveOptions
```

프레젠테이션을 마크다운으로 저장하는 방식을 제어하는 옵션을 나타냅니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getExportType()](#getExportType--) | 프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. |
| [setExportType(int value)](#setExportType-int-) | 프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. |
| [getBasePath()](#getBasePath--) | 문서와 리소스가 저장될 기본 경로를 지정합니다. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | 문서와 리소스가 저장될 기본 경로를 지정합니다. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | 이미지를 저장할 폴더 이름을 지정합니다. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | 이미지를 저장할 폴더 이름을 지정합니다. |
| [getNewLineType()](#getNewLineType--) | 생성된 문서가 \\r(Macintosh), \\n(Unix) 또는 \\r\\n(Windows) 중 어떤 줄 바꿈을 사용할지 지정합니다. |
| [setNewLineType(int value)](#setNewLineType-int-) | 생성된 문서가 \\r(Macintosh), \\n(Unix) 또는 \\r\\n(Windows) 중 어떤 줄 바꿈을 사용할지 지정합니다. |
| [getShowComments()](#getShowComments--) | 생성된 문서가 주석을 표시할지 여부를 지정합니다. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | 생성된 문서가 주석을 표시할지 여부를 지정합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getShowSlideNumber()](#getShowSlideNumber--) | 생성된 문서가 각 슬라이드 번호를 표시할지 여부를 지정합니다. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | 생성된 문서가 각 슬라이드 번호를 표시할지 여부를 지정합니다. |
| [getFlavor()](#getFlavor--) | 프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. |
| [setFlavor(int value)](#setFlavor-int-) | 프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Markdown 출력에서 슬라이드 번호 헤더에 사용되는 형식 문자열을 가져오거나 설정합니다. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Markdown 출력에서 슬라이드 번호 헤더에 사용되는 형식 문자열을 가져오거나 설정합니다. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Markdown 내보내기 중 반복되는 일반 공백 문자를 처리하는 방법을 지정합니다. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Markdown 내보내기 중 반복되는 일반 공백 문자를 처리하는 방법을 지정합니다. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | true로 설정하면 최종 Markdown 출력에서 빈 줄이나 공백만 있는 줄을 제거합니다. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | true로 설정하면 최종 Markdown 출력에서 빈 줄이나 공백만 있는 줄을 제거합니다. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)마다 발생합니다. 이미지를 저장하고 참조하는 방식을 사용자 정의할 수 있습니다. 처리되지 않으면 이미지는 로컬에 상대 링크로 저장됩니다. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Markdown 내보내기 중 각 SVG 이미지마다 발생합니다. 기본 저장 및 링크 생성을 재정의할 수 있습니다. 처리되지 않으면 SVG는 로컬에 상대 링크로 저장됩니다. |

### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

생성자.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. 기본값은 TextOnly 입니다.

**반환:**  
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. 기본값은 TextOnly 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

문서와 리소스가 저장될 기본 경로를 지정합니다. 기본값은 애플리케이션의 현재 디렉터리입니다.

**반환:**  
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

문서와 리소스가 저장될 기본 경로를 지정합니다. 기본값은 애플리케이션의 현재 디렉터리입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

이미지를 저장할 폴더 이름을 지정합니다. 기본값은 Images 입니다.

**반환:**  
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

이미지를 저장할 폴더 이름을 지정합니다. 기본값은 Images 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

생성된 문서가 \\r(Macintosh), \\n(Unix) 또는 \\r\\n(Windows) 중 어떤 줄 바꿈을 사용할지 지정합니다. 기본값은 Unix 입니다.

**반환:**  
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

생성된 문서가 \\r(Macintosh), \\n(Unix) 또는 \\r\\n(Windows) 중 어떤 줄 바꿈을 사용할지 지정합니다. 기본값은 Unix 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

생성된 문서가 주석을 표시할지 여부를 지정합니다. 기본값은 false 입니다.

**반환:**  
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

생성된 문서가 주석을 표시할지 여부를 지정합니다. 기본값은 false 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false 입니다.

**반환:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 false 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

생성된 문서가 각 슬라이드 번호를 표시할지 여부를 지정합니다. 기본값은 false 입니다.

**반환:**  
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

생성된 문서가 각 슬라이드 번호를 표시할지 여부를 지정합니다. 기본값은 false 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. 기본값은 Multi-markdown 입니다.

**반환:**  
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

프레젠테이션을 변환하기 위한 마크다운 사양을 지정합니다. 기본값은 Multi-markdown 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Markdown 출력에서 슬라이드 번호 헤더에 사용되는 형식 문자열을 가져오거나 설정합니다. 형식에는 "\{0\}" 자리표시자가 포함되어야 하며, 내보내기 시 슬라이드 인덱스로 대체됩니다. 예시: "\# Slide \{0\}" 은 "\# Slide 1", "\# Slide 2" 등으로 변환됩니다.

**반환:**  
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Markdown 출력에서 슬라이드 번호 헤더에 사용되는 형식 문자열을 가져오거나 설정합니다. 형식에는 "\{0\}" 자리표시자가 포함되어야 하며, 내보내기 시 슬라이드 인덱스로 대체됩니다. 예시: "\# Slide \{0\}" 은 "\# Slide 1", "\# Slide 2" 등으로 변환됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Markdown 내보내기 중 반복되는 일반 공백 문자를 처리하는 방법을 지정합니다. 이 속성은 연속 공백을 다음 중 하나로 정의합니다: - 일반 공백 문자 그대로 보존, - 일반 공백과 비공백 문자(&#65279;)를 번갈아 사용, - 첫 번째 이후를 비공백 문자로 완전 교체하여 시각적 정렬을 유지. 기본값은 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**반환:**  
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Markdown 내보내기 중 반복되는 일반 공백 문자를 처리하는 방법을 지정합니다. 이 속성은 연속 공백을 다음 중 하나로 정의합니다: - 일반 공백 문자 그대로 보존, - 일반 공백과 비공백 문자(&#65279;)를 번갈아 사용, - 첫 번째 이후를 비공백 문자로 완전 교체하여 시각적 정렬을 유지. 기본값은 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

true로 설정하면 최종 Markdown 출력에서 빈 줄이나 공백만 있는 줄을 제거합니다. 기본값은 false 입니다.

**반환:**  
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

true로 설정하면 최종 Markdown 출력에서 빈 줄이나 공백만 있는 줄을 제거합니다. 기본값은 false 입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)마다 발생합니다. 이미지 저장 및 참조 방식을 사용자 정의할 수 있습니다. 처리되지 않으면 이미지는 로컬에 상대 링크로 저장됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown 이미지 저장 이벤트. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Markdown 내보내기 중 각 SVG 이미지마다 발생합니다. 기본 저장 및 링크 생성을 재정의할 수 있습니다. 처리되지 않으면 SVG는 로컬에 상대 링크로 저장됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG 이미지 저장 이벤트. |