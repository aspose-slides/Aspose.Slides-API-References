---
title: IFormatFactory
second_title: Aspose.Slides for Java API 참조
description: COM 인터페이스를 통해 형식을 생성할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

COM 인터페이스를 통해 형식을 생성할 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | 새 [IPortionFormat](../../com.aspose.slides/iportionformat)를 생성합니다. |
| [createParagraphFormat()](#createParagraphFormat--) | 새 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)를 생성합니다. |
| [createTextFrameFormat()](#createTextFrameFormat--) | 새 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)를 생성합니다. |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

새 [IPortionFormat](../../com.aspose.slides/iportionformat)를 생성합니다.

**반환:**  
[IPortionFormat](../../com.aspose.slides/iportionformat) - 새 portion 형식.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

새 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)를 생성합니다.

**반환:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 새 paragraph 형식.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

새 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)를 생성합니다.

**반환:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 새 text frame 형식.