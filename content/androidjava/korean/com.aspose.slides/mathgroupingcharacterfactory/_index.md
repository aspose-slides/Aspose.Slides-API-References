---
title: MathGroupingCharacterFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 그룹화 문자를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathgroupingcharacterfactory/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

수학 그룹화 문자를 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 수학 그룹화 문자를 생성합니다 |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | 수학 그룹화 문자를 생성합니다 |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

수학 그룹화 문자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 그룹화 문자를 적용할 수학 요소 |
| character | char | 그룹화 문자 |
| position | int | 그룹화 문자의 위치 |
| verticalJustification | int | 수직 정렬 |

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새로운 그룹화 문자 요소
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

수학 그룹화 문자를 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 그룹화 문자를 적용할 수학 요소 |

**반환값:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 새로운 그룹화 문자 요소