---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /ru/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Позволяет создавать математический абзац

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Создает пустой математический абзац |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Создает математический абзац и помещает в него указанный математический блок |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Создает пустой математический абзац

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Создает математический абзац и помещает в него указанный математический блок

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | математический блок для размещения в абзаце |

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац