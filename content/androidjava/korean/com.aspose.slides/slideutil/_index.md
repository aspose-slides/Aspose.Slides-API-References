---
title: SlideUtil
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션에서 도형과 텍스트를 검색하는 데 도움이 되는 메서드를 제공합니다.
type: docs
url: /ko/com.aspose.slides/slideutil/
---
**상속:**
java.lang.Object
```
public class SlideUtil
```

프레젠테이션에서 도형과 텍스트를 검색하는 데 도움이 되는 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | PPTX 프레젠테이션에서 대체 텍스트로 도형을 찾습니다. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 도형을 찾습니다. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | 지정된 슬라이드에서 주어진 자리표시자 유형과 일치하는 모든 도형을 검색합니다. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | 슬라이드의 모든 도형 배치를 변경합니다. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | 슬라이드에서 선택된 도형의 배치를 변경합니다. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | 그룹 도형 내 모든 도형의 배치를 변경합니다. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | 그룹 도형 내 선택된 도형의 배치를 변경합니다. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | 지정된 형식으로 프레젠테이션의 텍스트를 찾고 교체합니다. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | 지정된 형식으로 프레젠테이션의 텍스트를 찾고 교체합니다. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | PPTX 프레젠테이션의 슬라이드에 있는 모든 텍스트 프레임을 반환합니다. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | 지정된 슬라이드에서 지정된 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | 소스 파일 형식을 해당 [SaveFormat](../../com.aspose.slides/saveformat) 로 변환합니다. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


PPTX 프레젠테이션에서 대체 텍스트로 도형을 찾습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| altText | java.lang.String | 도형의 대체 텍스트. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - Shape 또는 null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 도형을 찾습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 스캔된 슬라이드. |
| altText | java.lang.String | 도형의 대체 텍스트. |

**반환값:**
[IShape](../../com.aspose.slides/ishape) - Shape 또는 null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


지정된 슬라이드에서 주어진 자리표시자 유형과 일치하는 모든 도형을 검색합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 도형을 검색할 슬라이드. |
| placeholderType | byte | 도형을 필터링할 자리표시자 유형. |

**반환값:**
com.aspose.slides.IShape[] - 지정된 자리표시자 유형과 일치하는 [IShape](../../com.aspose.slides/ishape) 객체 배열.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


슬라이드의 모든 도형 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| alignmentType | int | 적용할 정렬 유형을 결정합니다. |
| alignToSlide | boolean | true인 경우, 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 부모 슬라이드. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


슬라이드에서 선택된 도형의 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| alignmentType | int | 적용할 정렬 유형을 결정합니다. |
| alignToSlide | boolean | true인 경우, 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 부모 슬라이드. |
| shapeIndexes | int[] | 정렬할 도형의 인덱스. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


그룹 도형 내 모든 도형의 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| alignmentType | int | 적용할 정렬 유형을 결정합니다. |
| alignToSlide | boolean | true인 경우, 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 부모 그룹 도형. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


그룹 도형 내 선택된 도형의 배치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| alignmentType | int | 적용할 정렬 유형을 결정합니다. |
| alignToSlide | boolean | true인 경우, 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 부모 그룹 도형. |
| shapeIndexes | int[] | 정렬할 도형의 인덱스. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


지정된 형식으로 프레젠테이션의 텍스트를 찾고 교체합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| withMasters | boolean | 마스터 슬라이드를 스캔할지 여부를 결정합니다. |
| find | java.lang.String | 찾을 문자열 값. |
| replace | java.lang.String | 교체할 문자열 값. 찾은 문자열의 문자 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


지정된 형식으로 프레젠테이션의 텍스트를 찾고 교체합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| withMasters | boolean | 마스터 슬라이드를 스캔할지 여부를 결정합니다. |
| find | java.lang.String | 찾을 문자열 값. |
| replace | java.lang.String | 교체할 문자열 값. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | 텍스트 부분을 교체하기 위한 형식. null인 경우 찾은 문자열 첫 번째 문자의 형식이 사용됩니다. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


PPTX 프레젠테이션의 슬라이드에 있는 모든 텍스트 프레임을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 스캔된 슬라이드. |

**반환값:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 객체 배열.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


지정된 슬라이드에서 지정된 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 검색할 슬라이드. |
| text | java.lang.String | 텍스트 프레임 내에서 검색할 텍스트. |
| checkPlaceholderText | boolean | 텍스트 프레임이 비어 있어도 자리표시자 텍스트에 검색 텍스트가 포함되어 있으면 포함할지 여부를 나타냅니다. |

**반환값:**
com.aspose.slides.ITextFrame[] - 지정된 텍스트를 포함하는 [ITextFrame](../../com.aspose.slides/itextframe) 객체 배열.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


PPTX 프레젠테이션의 모든 텍스트 프레임을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| withMasters | boolean | 마스터 슬라이드를 스캔할지 여부를 결정합니다. |

**반환값:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 객체 배열.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


소스 파일 형식을 해당 [SaveFormat](../../com.aspose.slides/saveformat) 로 변환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| format | int | 소스 파일 형식. |

**반환값:**
int - 해당 [SaveFormat](../../com.aspose.slides/saveformat) 값.