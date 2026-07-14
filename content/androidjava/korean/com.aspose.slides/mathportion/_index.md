---
title: MathPortion
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학적 컨텍스트가 포함된 부분을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/mathportion/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Portion](../../com.aspose.slides/portion)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathPortion](../../com.aspose.slides/imathportion)  
```
public final class MathPortion extends Portion implements IMathPortion
```

수학적 컨텍스트가 포함된 부분을 나타냅니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathPortion()](#MathPortion--) | MathPortion 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMathParagraph()](#getMathParagraph--) | 수학 단락 |
### MathPortion() {#MathPortion--}
```
public MathPortion()
```

MathPortion 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>  	 IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>  	 IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>  	 MathPortion mathPortion = new MathPortion();
>  	 paragraph.getPortions().add(mathPortion);
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

### getMathParagraph() {#getMathParagraph--}
```
public final IMathParagraph getMathParagraph()
```

수학 단락

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 300, 50);
>      IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      mathParagraph.add(new MathBlock(new MathematicalText("x+y")));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph)