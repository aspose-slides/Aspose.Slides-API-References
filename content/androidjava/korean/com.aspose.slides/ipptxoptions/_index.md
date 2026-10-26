---
title: IPptxOptions
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: OpenXml 프레젠테이션(PPTX, PPSX, POTX, PPTM, PPSM, POTM)을 저장하기 위한 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipptxoptions/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Presentation 문서를 저장하기 위한 옵션을 나타냅니다 (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getConformance()](#getConformance--) | Presentation 문서가 준수하는 호환성 클래스를 지정합니다. |
| [setConformance(int value)](#setConformance-int-) | Presentation 문서가 준수하는 호환성 클래스를 지정합니다. |
| [getZip64Mode()](#getZip64Mode--) | Presentation 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Presentation 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | 프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | 프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. |
| [getCompressionLevel()](#getCompressionLevel--) | 프레젠테이션 문서를 저장할 때 사용되는 압축 레벨을 지정합니다. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 프레젠테이션 문서를 저장할 때 사용되는 압축 레벨을 지정합니다. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Presentation 문서가 준수하는 호환성 클래스를 지정합니다. 기본값은 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**반환값:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Presentation 문서가 준수하는 호환성 클래스를 지정합니다. 기본값은 [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Presentation 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. 기본값은 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

Presentation 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. 기본값은 [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. 읽기/쓰기 boolean. 기본값은 **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

옵션 값이 **true**이면 새 썸네일이 생성됩니다.

옵션 값이 **false**이면 현재 썸네일이 그대로 저장됩니다.

**반환값:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다. 읽기/쓰기 boolean. 기본값은 **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

옵션 값이 **true**이면 새 썸네일이 생성됩니다.

옵션 값이 **false**이면 현재 썸네일이 그대로 저장됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

프레젠테이션 문서를 저장할 때 사용되는 압축 레벨을 지정합니다. 기본값은 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

높은 압축 레벨은 파일 크기를 줄이지만 처리 시간이 더 많이 소요됩니다. 실제 압축 비율은 프레젠테이션 내용에 따라 달라집니다.

**반환값:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

프레젠테이션 문서를 저장할 때 사용되는 압축 레벨을 지정합니다. 기본값은 [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

높은 압축 레벨은 파일 크기를 줄이지만 처리 시간이 더 많이 소요됩니다. 실제 압축 비율은 프레젠테이션 내용에 따라 달라집니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |