---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: IMathLimit을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

IMathLimit을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit을 생성합니다 |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 아래에 제한이 있는 IMathLimit을 생성합니다 |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit을 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 제한을 적용할 기본 인수 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 제한 요소 |
| upperLimit | boolean | 제한을 위에 배치하도록 설정합니다 |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 수학 제한
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


아래에 제한이 있는 IMathLimit을 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 제한을 적용할 기본 인수 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 제한 요소 |

**반환값:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 새 수학 제한