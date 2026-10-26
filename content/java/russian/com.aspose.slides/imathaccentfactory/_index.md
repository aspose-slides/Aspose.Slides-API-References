---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Позволяет создавать математический акцент
type: docs
url: /ru/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Позволяет создавать математический акцент

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Создает математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Создает математический акцент, применяемый к указанному математическому элементу |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Создает математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется акцент |

**Возвращаемое значение:**
[IMathAccent](../../com.aspose.slides/imathaccent) - новый математический акцент
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Создает математический акцент, применяемый к указанному математическому элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется акцент |
| accentCharacter | char | символ акцента |

**Возвращаемое значение:**
[IMathAccent](../../com.aspose.slides/imathaccent) - новый математический акцент