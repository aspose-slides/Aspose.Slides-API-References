---
title: IPdfOptions
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 프레젠테이션이 PDF 형식으로 저장되는 방식을 제어하는 옵션을 제공합니다.
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
| [getTextCompression()](#getTextCompression--) | 문서의 모든 텍스트 콘텐츠에 사용될 압축 유형을 지정합니다. |
| [setTextCompression(int value)](#setTextCompression-int-) | 문서의 모든 텍스트 콘텐츠에 사용될 압축 유형을 지정합니다. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | 각 이미지에 대해 기본 압축 대신 가장 효율적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | 각 이미지에 대해 기본 압축 대신 가장 효율적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII 문자 32-127에 대한 True Type 글꼴을 임베드하려면 true를 설정합니다. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII 문자 32-127에 대한 True Type 글꼴을 임베드하려면 true를 설정합니다. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides가 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides가 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | 글꼴의 모든 문자를 임베드할지, 사용된 서브셋만 임베드할지 결정합니다. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | 글꼴의 모든 문자를 임베드할지, 사용된 서브셋만 임베드할지 결정합니다. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | 글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | 글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. |
| [getJpegQuality()](#getJpegQuality--) | PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. |
| [getCompliance()](#getCompliance--) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [setCompliance(int value)](#setCompliance-int-) | 생성된 PDF 문서에 대한 원하는 호환성 수준입니다. |
| [getPassword()](#getPassword--) | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. |
| [getAccessPermissions()](#getAccessPermissions--) | 문서를 사용자 액세스로 열 때 부여해야 할 액세스 권한을 지정하는 플래그 집합을 포함합니다. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | 문서를 사용자 액세스로 열 때 부여해야 할 액세스 권한을 지정하는 플래그 집합을 포함합니다. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 설정합니다. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | 프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 설정합니다. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환하거나 설정합니다. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | 각 슬라이드 주변에 검은 프레임을 그리려면 true를 설정합니다. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | 각 슬라이드 주변에 검은 프레임을 그리려면 true를 설정합니다. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | true인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | true인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 잉크 객체의 외관을 제어하는 옵션을 제공합니다. |
| [getIncludeOleData()](#getIncludeOleData--) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드 파일로 변환하려면 true를 설정합니다. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드 파일로 변환하려면 true를 설정합니다. |
### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

문서의 모든 텍스트 콘텐츠에 사용될 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)입니다.

**반환값:**  
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

문서의 모든 텍스트 콘텐츠에 사용될 압축 유형을 지정합니다. 읽기/쓰기 [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

기본값은 [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

각 이미지에 대해 기본 압축 대신 가장 효율적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 줄어듭니다.

--------------------

최적 이미지 압축 비율 선택은 계산 비용이 많이 들며 추가 메모리를 사용하므로 기본값은 false입니다.

--------------------

기본값은 false입니다.

**반환값:**  
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

각 이미지에 대해 기본 압축 대신 가장 효율적인 압축을 자동으로 선택해야 하는지 여부를 나타냅니다. true로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 줄어듭니다.

--------------------

최적 이미지 압축 비율 선택은 계산 비용이 많이 들며 추가 메모리를 사용하므로 기본값은 false입니다.

--------------------

기본값은 false입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

ASCII 문자 32-127에 대한 True Type 글꼴을 임베드하려면 true를 설정합니다. 127보다 큰 문자 코드는 항상 임베드됩니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다.

**반환값:**  
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII 문자 32-127에 대한 True Type 글꼴을 임베드하려면 true를 설정합니다. 127보다 큰 문자 코드는 항상 임베드됩니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides가 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**반환값:**  
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides가 공통으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다. 읽기/쓰기 String[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

글꼴의 모든 문자를 임베드할지, 사용된 서브셋만 임베드할지 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

글꼴의 모든 문자를 임베드할지, 사용된 서브셋만 임베드할지 결정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. 이 방법은 특정 글꼴의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다. 이 방법은 특정 글꼴의 텍스트 품질을 향상시킬 수 있습니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 줍니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 설정하거나 가져올 수 있습니다. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축을 의미하고 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

**반환값:**  
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 byte.

--------------------

문서에 JPEG 이미지가 포함된 경우에만 영향을 줍니다.

이 속성을 사용하여 PDF 형식으로 저장할 때 문서 내부 이미지의 품질을 설정하거나 가져올 수 있습니다. 값은 0에서 100 사이이며, 0은 최악의 품질이지만 최대 압축을 의미하고 100은 최고의 품질이지만 최소 압축을 의미합니다.

기본값은 **100**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)입니다.

**반환값:**  
int
### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 읽기/쓰기 [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

기본값은 [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF 문서를 보호하기 위해 사용자 비밀번호를 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

문서를 사용자 액세스로 열 때 부여해야 할 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)를 참조하십시오.

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


**반환값:**  
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

문서를 사용자 액세스로 열 때 부여해야 할 액세스 권한을 지정하는 플래그 집합을 포함합니다. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions)를 참조하십시오.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 설정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng이 true이면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. false이면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어 메타파일이 PNG로 변환되면 결과 문서 크기 조정 시 품질 손실이 발생할 수 있습니다. PDF 벡터 그래픽으로 변환되면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**반환값:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

프레젠테이션에 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true를 설정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **true**입니다. PDF 문서는 벡터 그래픽과 래스터 이미지를 포함할 수 있습니다. SaveMetafilesAsPng이 true이면 원본 메타파일 이미지가 PNG 형식으로 변환되어 래스터 이미지로 PDF에 저장됩니다. false이면 원본 메타파일이 PDF 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장단점이 있습니다. 예를 들어 메타파일이 PNG로 변환되면 결과 문서 크기 조정 시 품질 손실이 발생할 수 있습니다. PDF 벡터 그래픽으로 변환되면 PDF 뷰어에서 성능 문제가 발생할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 여러 요인에 따라 달라집니다. 알고리즘은 속성값, 원본 이미지 크기 및 이미지 프레임 크기에 따라 최적 출력 이미지 크기를 얻으려고 합니다. 유사한 속성값을 사용하면 동일한 결과가 나올 수 있습니다. 가시적인 효과를 얻으려면 16 또는 32 단계를 사용하는 것이 권장됩니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

**반환값:**  
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환하거나 설정합니다. 읽기/쓰기 float.

값: 이 매개변수의 효과는 여러 요인에 따라 달라집니다. 알고리즘은 속성값, 원본 이미지 크기 및 이미지 프레임 크기에 따라 최적 출력 이미지 크기를 얻으려고 합니다. 유사한 속성값을 사용하면 동일한 결과가 나올 수 있습니다. 가시적인 효과를 얻으려면 16 또는 32 단계를 사용하는 것이 권장됩니다.

--------------------

속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.

기본값은 **96**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

각 슬라이드 주변에 검은 프레임을 그리려면 true를 설정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**반환값:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

각 슬라이드 주변에 검은 프레임을 그리려면 true를 설정합니다. 읽기/쓰기 boolean.

--------------------

기본값은 **false**입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**반환값:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

이미지 투명 색상을 가져오거나 설정합니다.

값: 이미지 투명 색상.

**반환값:**  
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

이미지 투명 색상을 가져오거나 설정합니다.

값: 이미지 투명 색상.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

true인 경우 지정된 투명 색상을 이미지에 적용합니다.

**반환값:**  
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

true인 경우 지정된 투명 색상을 이미지에 적용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

내보낸 문서에서 잉크 객체의 외관을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환값:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드 파일로 변환하려면 true를 설정합니다. 읽기/쓰기  boolean .

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

기본값은  **false**  입니다.

**반환값:**  
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

프레젠테이션의 모든 OLE 데이터를 결과 PDF의 임베드 파일로 변환하려면 true를 설정합니다. 읽기/쓰기  boolean .

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

기본값은  **false**  입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |