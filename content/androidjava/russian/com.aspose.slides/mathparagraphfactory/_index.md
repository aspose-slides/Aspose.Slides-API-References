---
title: MathParagraphFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создать математический абзац
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
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Создать пустой математический абзац

**Возвращаемое значение:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Создает математический абзац и помещает в него указанный математический блок

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | математический блок, который будет помещен в абзац |

**Возвращаемое значение:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - новый математический абзац