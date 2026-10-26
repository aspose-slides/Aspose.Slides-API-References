---
title: MathBoxFactory
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수학 상자를 만들 수 있습니다
type: docs
url: /ko/com.aspose.slides/mathboxfactory/
---
**상속:**  
java.lang.Object  

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMathBoxFactory](../../com.aspose.slides/imathboxfactory)  
```
public class MathBoxFactory implements IMathBoxFactory
```  

수학 상자를 만들 수 있습니다  

--------------------  

COM 호환성을 위해  

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathBoxFactory()](#MathBoxFactory--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createMathBox(IMathElement element)](#createMathBox-com.aspose.slides.IMathElement-) |  |

### MathBoxFactory() {#MathBoxFactory--}
```
public MathBoxFactory()
```

### createMathBox(IMathElement element) {#createMathBox-com.aspose.slides.IMathElement-}
```
public final IMathBox createMathBox(IMathElement element)
```

요소에 적용하여 수학 상자를 생성합니다  

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 상자를 적용할 수학 요소 |

**반환값:**  
[IMathBox](../../com.aspose.slides/imathbox) - 새 상자 요소