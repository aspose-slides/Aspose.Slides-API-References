---
title: InkOptions
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/inkoptions/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)  
```
public class InkOptions implements IInkOptions
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHideInk()](#getHideInk--) | 내보낸 문서에서 Ink 요소를 표시하거나 숨깁니다. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | 내보낸 문서에서 Ink 요소를 표시하거나 숨깁니다. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | 브러시 렌더링에 ROP 연산 또는 불투명도를 사용합니다. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | 브러시 렌더링에 ROP 연산 또는 불투명도를 사용합니다. |

### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

내보낸 문서에서 Ink 요소를 표시하거나 숨깁니다.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

--------------------

기본값은 false입니다.

**반환값:**  
boolean

### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

내보낸 문서에서 Ink 요소를 표시하거나 숨깁니다.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 false입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

브러시 렌더링에 ROP 연산 또는 불투명도를 사용합니다.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 true입니다.

**반환값:**  
boolean

### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

브러시 렌더링에 ROP 연산 또는 불투명도를 사용합니다.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

기본값은 true입니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |