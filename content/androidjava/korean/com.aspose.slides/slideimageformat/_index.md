---
title: SlideImageFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션을 HTML로 내보낼 때 슬라이드 이미지가 저장되는 형식을 결정합니다.
type: docs
url: /ko/com.aspose.slides/slideimageformat/
---
**상속:**  
java.lang.Object  

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```  

프레젠테이션을 HTML로 내보낼 때 슬라이드 이미지가 저장되는 형식을 결정합니다.  

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | 슬라이드를 SVG 형식으로 변환해야 합니다. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | 슬라이드를 래스터 이미지로 변환해야 합니다. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

슬라이드를 SVG 형식으로 변환해야 합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG 내보내기 옵션. |

**반환값:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) 객체.

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

슬라이드를 래스터 이미지로 변환해야 합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scale | float | 출력 이미지를 스케일링하는 비율. |
| imageFormat | int | 결과 이미지의 형식 (예: PNG, JPEG). |

**반환값:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -