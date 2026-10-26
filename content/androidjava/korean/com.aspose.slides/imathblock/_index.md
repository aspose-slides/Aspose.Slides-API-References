---
title: IMathBlock
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: MathParagraph에 포함되고 자체 라인에서 시작하는 수학 텍스트 인스턴스를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathblock/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

수학 텍스트 인스턴스를 지정하며, 이는 MathParagraph에 포함되고 자체 라인에서 시작합니다. 방정식, 식, 방정식이나 식 배열, 그리고 수식 등을 포함한 모든 수학 영역은 수학 블록으로 표현됩니다.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | 구분자를 사용하여 모든 하위 요소를 구분합니다 (대괄호 없이) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 이 블록의 하위 요소를 괄호와 같은 지정된 문자로 둘러싸고 구분자를 사용하여 구분합니다 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 다른 수학 블록을 이 블록과 결합합니다 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 이 [IMathBlock](../../com.aspose.slides/imathblock)의 내용을 MathML로 저장합니다 |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

구분자를 사용하여 모든 하위 요소를 구분합니다 (대괄호 없이)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char | 구분자로 사용되는 문자 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter 요소의 인스턴스
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

이 블록의 하위 요소를 괄호와 같은 지정된 문자로 둘러싸고 구분자를 사용하여 구분합니다

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char | 끝 문자(보통 오른쪽 괄호) |
| separatorCharacter | char | 구분 문자 |

**반환값:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 지정된 문자를 프레임 및 구분자로 포함하는 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 유형의 수학 요소
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

다른 수학 블록을 이 블록과 결합합니다

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 결합되는 블록 |

**반환값:**
[IMathBlock](../../com.aspose.slides/imathblock) - 결합 후 이 수학 블록
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

이 [IMathBlock](../../com.aspose.slides/imathblock)의 내용을 MathML로 저장합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |