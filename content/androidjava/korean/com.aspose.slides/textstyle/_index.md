---
title: TextStyle
second_title: Java API 참조를 통한 Aspose.Slides for Android
description: 이 클래스는 텍스트 스타일 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/textstyle/
---
**Inheritance:** 상속:
[com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:** 구현된 모든 인터페이스:
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

이 클래스는 텍스트 스타일 서식 속성을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | 스타일 수준이 존재하면 반환하고, 그렇지 않으면 null을 반환합니다. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 기본 단락 속성. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

스타일 수준이 존재하면 반환하고, 그렇지 않으면 null을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 레벨의 0부터 시작하는 인덱스. 0..8 구간 내에 있어야 합니다. |

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 레벨 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)의 서식.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

기본 단락 속성. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 하나의 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).