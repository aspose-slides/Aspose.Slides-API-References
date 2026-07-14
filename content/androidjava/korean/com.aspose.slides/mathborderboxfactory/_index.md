---
title: MathBorderBoxFactory
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수학 테두리 상자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathborderboxfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

수학 테두리 상자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 테두리 상자를 생성합니다 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 요소에 적용하여 수학 테두리 상자를 생성합니다 |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

요소에 적용하여 수학 테두리 상자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 테두리 상자를 적용할 수학 요소 |

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 새 테두리 상자 요소
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

요소에 적용하여 수학 테두리 상자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 테두리 상자를 적용할 수학 요소 |
| hideTop | boolean | 상단 가장자리 숨기기 |
| hideBottom | boolean | 하단 가장자리 숨기기 |
| hideLeft | boolean | 왼쪽 가장자리 숨기기 |
| hideRight | boolean | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | boolean | 수평으로 테두리 상자 취소선 |
| strikethroughVertical | boolean | 수직으로 테두리 상자 취소선 |
| strikethroughBottomLeftToTopRight | boolean | 왼쪽 하단에서 오른쪽 상단으로 테두리 상자 취소선 |
| strikethroughTopLeftToBottomRight | boolean | 왼쪽 상단에서 오른쪽 하단으로 테두리 상자 취소선 |

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 새 테두리 상자 요소