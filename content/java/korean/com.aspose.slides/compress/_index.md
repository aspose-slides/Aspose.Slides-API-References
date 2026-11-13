---
title: Compress
second_title: Aspose.Slides for Java API 레퍼런스
description: 압축을 위해 설계된 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/compress/
---
**상속:**
java.lang.Object
```
public class Compress
```

[Presentation](../../com.aspose.slides/presentation)를 압축하기 위한 메서드 그룹을 나타냅니다.

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | 사용 가능한 모든 압축 단계를 적용하여 프레젠테이션의 크기를 감소시킵니다:

 *  사용되지 않은 마스터 슬라이드 제거 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  사용되지 않은 레이아웃 슬라이드 제거 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  포함된 글꼴에서 실제로 사용된 글리프만 유지 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  그림 해상도를 150 DPI로 낮추고 그림의 잘린 영역을 삭제 \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | 사용되지 않은 마스터 슬라이드를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | 사용되지 않은 레이아웃 슬라이드를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | 포함된 글꼴에서 사용되지 않은 문자를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | 프레젠테이션의 그림 해상도를 낮추고 잘린 영역을 삭제합니다. 이는 모든 그림에 적용되는 PowerPoint의 "Compress Pictures"와 유사합니다. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


사용 가능한 모든 압축 단계를 적용하여 프레젠테이션의 크기를 감소시킵니다:

 *  사용되지 않은 마스터 슬라이드 제거 \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  사용되지 않은 레이아웃 슬라이드 제거 \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  포함된 글꼴에서 실제로 사용된 글리프만 유지 \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  그림 해상도를 150 DPI로 낮추고 그림의 잘린 영역을 삭제 \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | 압축할 프레젠테이션.

--------------------

압축을 사용자 지정하려면, 예를 들어 다른 그림 해상도를 사용하거나 단계를 건너뛰려면, 이 메서드 대신 위에 나열된 메서드를 개별적으로 호출하십시오. 그림의 잘린 영역은 영구적으로 제거되며 PowerPoint에서 복원할 수 없습니다.

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


사용되지 않은 마스터 슬라이드를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


사용되지 않은 레이아웃 슬라이드를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


포함된 글꼴에서 사용되지 않은 문자를 제거하여 [Presentation](../../com.aspose.slides/presentation)를 압축합니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 프레젠테이션 인스턴스

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


프레젠테이션의 그림 해상도를 낮추고 잘린 영역을 삭제합니다. 이는 모든 그림에 적용되는 PowerPoint의 "Compress Pictures"와 유사합니다. 슬라이드, 레이아웃 슬라이드 및 마스터 슬라이드의 그림이 처리되며, 그룹 형태 내부의 그림 및 형태의 그림 채우기도 포함됩니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 처리할 프레젠테이션.
| resolution | int | 각 그림이 표시되는 크기에 대한 상대적인 목표 해상도입니다. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution)는 그림을 변경하지 않습니다.

--------------------

이미 목표 해상도 이하인 그림은 변경되지 않고 그대로 유지됩니다. 그림이 확대되는 일은 없습니다.

처리되지 않는 항목: 슬라이드 배경, 표 셀 채우기, 차트, SmartArt, GIF 이미지(애니메이션 유지), SVG 및 메타파일(EMF/WMF) 이미지.

잘린 영역은 영구적으로 제거되며 PowerPoint에서 복원할 수 없습니다.