---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 수학 그룹화 문자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

수학 그룹화 문자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

수학 그룹화 문자를 생성합니다

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 그룹화 문자를 적용할 수학 요소 |
| character | char | 그룹화 문자 |
| position | int | 그룹화 문자의 위치 |
| verticalJustification | int | 수직 정렬 |

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 그룹화 문자 요소
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

수학 그룹화 문자를 생성합니다

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 그룹화 문자를 적용할 수학 요소 |

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새 그룹화 문자 요소