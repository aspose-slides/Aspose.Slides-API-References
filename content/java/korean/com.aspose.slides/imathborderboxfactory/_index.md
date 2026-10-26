---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: 수학 경계 상자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

수학 경계 상자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 요소에 적용하여 수학 경계 상자를 생성합니다 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 요소에 적용하여 수학 경계 상자를 생성합니다 |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

요소에 적용하여 수학 경계 상자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 경계 상자를 적용할 수학 요소 |

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 새 경계 상자 요소
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

요소에 적용하여 수학 경계 상자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 경계 상자를 적용할 수학 요소 |
| hideTop | boolean | 위쪽 가장자리 숨기기 |
| hideBottom | boolean | 아래쪽 가장자리 숨기기 |
| hideLeft | boolean | 왼쪽 가장자리 숨기기 |
| hideRight | boolean | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | boolean | 경계 상자 가로 취소선 |
| strikethroughVertical | boolean | 경계 상자 세로 취소선 |
| strikethroughBottomLeftToTopRight | boolean | 경계 상자 왼쪽 아래-오른쪽 위 대각선 취소선 |
| strikethroughTopLeftToBottomRight | boolean | 경계 상자 왼쪽 위-오른쪽 아래 대각선 취소선 |

**반환값:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 새 경계 상자 요소