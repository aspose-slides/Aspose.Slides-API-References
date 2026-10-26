---
title: MathParagraphFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать математический абзац
type: docs
url: /ru/com.aspose.slides/mathparagraphfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Позволяет создавать математический абзац

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Создать пустой математический абзац |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Создает математический абзац и помещает в него указанный математический блок |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Создать пустой математический абзац

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Создает математический абзац и помещает в него указанный математический блок

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | математический блок для размещения в абзаце |

**Возвращает:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац