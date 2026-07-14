---
title: MathRadicalFactory
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수학 라디칼을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathradicalfactory/
---
**상속:**
java.lang.Object

**구현한 모든 인터페이스:**
[com.aspose.slides.IMathRadicalFactory](../../com.aspose.slides/imathradicalfactory)
```
public class MathRadicalFactory implements IMathRadicalFactory
```

수학 라디칼을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathRadicalFactory()](#MathRadicalFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 수학 라디칼을 생성합니다 |
### MathRadicalFactory() {#MathRadicalFactory--}
```
public MathRadicalFactory()
```


### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


수학 라디칼을 생성합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 라디칼을 적용할 기본 인수 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 차수 값 |

**반환값:**
[IMathRadical](../../com.aspose.slides/imathradical) - 새 라디칼 요소