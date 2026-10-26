---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 수학 배열을 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

수학 배열을 만들 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | 수학 배열을 생성하고 지정된 요소를 그 안에 배치합니다 |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | 수학 배열을 생성하고 지정된 여러 요소를 그 안에 배치합니다 |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


수학 배열을 생성하고 지정된 요소를 그 안에 배치합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 배열에 배치할 수학 요소 |

**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 수학 배열
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


수학 배열을 생성하고 지정된 여러 요소를 그 안에 배치합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 배열에 배치할 수학 요소들 |

**반환값:**
[IMathArray](../../com.aspose.slides/imatharray) - 새 수학 배열