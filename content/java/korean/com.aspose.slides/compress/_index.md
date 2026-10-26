---
title: Compress
second_title: Aspose.Slides for Java API 레퍼런스
description: 압축을 위해 설계된 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/compress/
---
**Inheritance:**  
상속:
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation)을 압축하기 위해 설계된 메서드 그룹을 나타냅니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Compress()](#Compress--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation)의 사용되지 않은 마스터 슬라이드를 제거하여 압축합니다. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation)의 사용되지 않은 레이아웃 슬라이드를 제거하여 압축합니다. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation)의 포함된 글꼴에서 사용되지 않은 문자를 제거하여 압축합니다. |

### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation)의 사용되지 않은 마스터 슬라이드를 제거하여 압축합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스 |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation)의 사용되지 않은 레이아웃 슬라이드를 제거하여 압축합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스 |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation)의 포함된 글꼴에서 사용되지 않은 문자를 제거하여 압축합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스 |