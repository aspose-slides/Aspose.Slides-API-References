---
title: MathAccentFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать математический акцент
type: docs
url: /ru/com.aspose.slides/mathaccentfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Позволяет создавать математический акцент

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Создаёт математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Создаёт математический акцент, применяемый к указанному математическому элементу |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Создаёт математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется акцент |

**Возвращаемое значение:**
[IMathAccent](../../com.aspose.slides/imathaccent) - новый математический акцент
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Создаёт математический акцент, применяемый к указанному математическому элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется акцент |
| accentCharacter | char | символ акцента |

**Возвращаемое значение:**
[IMathAccent](../../com.aspose.slides/imathaccent) - новый математический акцент