---
title: IMathParagraphFactory
second_title: Aspose.Slides для Android через Java API Reference
description: Позволяет создавать математический абзац
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
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Создать пустой математический абзац

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Создаёт математический абзац и помещает в него указанный математический блок

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | математический блок для размещения в абзаце |

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph