---
title: IPdfOptions
second_title: Aspose.Slides for Java API 참조
description: 프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/ipdfoptions/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | 문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. |
| [setTextCompression(int value)](#setTextCompression-int-) | 문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII 문자 32-127에 대한 TrueType 글꼴을 포함하려면 true. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII 문자 32-127에 대한 TrueType 글꼴을 포함하려면 true. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides에서 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides에서 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 글꼴의 모든 문자를 포함할지 아니면 사용된 부분집합만 포함할지 결정합니다. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 글꼴의 모든 문자를 포함할지 아니면 사용된 부분집합만 포함할지 결정합니다. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. |
| [getJpegQuality()](#getJpegQuality--) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. |
| [getCompliance()](#getCompliance--) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [setCompliance(int value)](#setCompliance-int-) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [getPassword()](#getPassword--) | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. |
| [getAccessPermissions()](#getAccessPermissions--) | 문서를 사용자 접근으로 열 때 부여될 접근 권한을 지정하는 플래그 집합을 포함합니다. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 문서를 사용자 접근으로 열 때 부여될 접근 권한을 지정하는 플래그 집합을 포함합니다. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 각 슬라이드 주변에 검은 프레임을 그리려면 true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 각 슬라이드 주변에 검은 프레임을 그리려면 true. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | 이미지 투명 색을 가져오거나 설정합니다. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | 이미지 투명 색을 가져오거나 설정합니다. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | true인 경우 지정된 투명 색을 이미지에 적용합니다. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | true인 경우 지정된 투명 색을 이미지에 적용합니다. |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getIncludeOleData()](#getIncludeOleData--) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**반환:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

문서의 모든 텍스트 콘텐츠에 사용할 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.

--------------------

최고 이미지 압축 비율 선택은 계산 비용이 많이 들며 추가 메모리를 사용합니다. 이 옵션은 기본값이 false입니다.

--------------------

기본값은 false.

**반환:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

각 이미지에 대해 기본 압축 대신 가장 효과적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.

--------------------

최고 이미지 압축 비율 선택은 계산 비용이 많이 들며 추가 메모리를 사용합니다. 이 옵션은 기본값이 false입니다.

--------------------

기본값은 false.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. 읽기/쓰기 boolean.

--------------------

기본값은 **true**.

**반환:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. 읽기/쓰기 boolean.

--------------------

기본값은 **true**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides에서 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**반환:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides에서 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

글꼴의 모든 문자를 포함할지 아니면 사용된 부분집합만 포함할지 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**반환:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

글꼴의 모든 문자를 포함할지 아니면 사용된 부분집합만 포함할지 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 글꼴에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**반환:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다. 이 방법은 특정 글꼴에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 줍니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내 이미지 품질을 설정하거나 가져올 수 있습니다. 값은 0에서 100 사이이며 0은 최악의 품질이지만 최대 압축을 의미하고 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**.

**반환:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF 문서 내 JPEG 이미지 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 줍니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내 이미지 품질을 설정하거나 가져올 수 있습니다. 값은 0에서 100 사이이며 0은 최악의 품질이지만 최대 압축을 의미하고 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**반환:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

문서를 사용자 접근으로 열 때 부여될 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)를 참조하십시오.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

문서를 사용자 접근으로 열 때 부여될 접근 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)를 참조하십시오.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **true**. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng을 true로 설정하면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. SaveMetafilesAsPng을 false로 설정하면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어 메타파일을 PNG로 변환하면 결과 문서가 확대될 때 일부 품질 손실이 발생할 수 있습니다. 메타파일을 PDF 벡터 그래픽으로 변환하면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**반환:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **true**. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng을 true로 설정하면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. SaveMetafilesAsPng을 false로 설정하면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어 메타파일을 PNG로 변환하면 결과 문서가 확대될 때 일부 품질 손실이 발생할 수 있습니다. 메타파일을 PDF 벡터 그래픽으로 변환하면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 몇 가지 요인에 따라 달라집니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기를 기준으로 최적의 출력 이미지 크기를 얻으려고 합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 눈에 보이는 효과를 얻으려면 16 또는 32 단계 사용을 권장합니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**.

**반환:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 몇 가지 요인에 따라 달라집니다. 알고리즘은 속성 값, 원본 이미지 크기 및 이미지 프레임 크기를 기준으로 최적의 출력 이미지 크기를 얻으려고 합니다. 유사한 속성 값을 사용하면 동일한 결과가 나올 수 있습니다. 눈에 보이는 효과를 얻으려면 16 또는 32 단계 사용을 권장합니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

각 슬라이드 주변에 검은 프레임을 그리려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**반환:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

각 슬라이드 주변에 검은 프레임을 그리려면 true. 읽기/쓰기 boolean.

--------------------

기본값은 **false**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> 예제:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

이미지 투명 색을 가져오거나 설정합니다.

값: 이미지 투명 색.

**반환:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

이미지 투명 색을 가져오거나 설정합니다.

값: 이미지 투명 색.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

true인 경우 지정된 투명 색을 이미지에 적용합니다.

**반환:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

true인 경우 지정된 투명 색을 이미지에 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false**.

**반환:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true. 읽기/쓰기 boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 **false**.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |