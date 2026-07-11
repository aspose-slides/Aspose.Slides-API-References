---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math accent
type: docs
url: /ru/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Позволяет создать математический акцент

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Создаёт математический акцент, применяемый к указанному математическому элементу с значением символа акцента по умолчанию |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Создаёт математический акцент, применяемый к указанному математическому элементу |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Создаёт математический акцент, применяемый к указанному математическому элементу с значением символа акцента по умолчанию

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


Создаёт математический акцент, применяемый к указанному математическому элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется акцент |
| accentCharacter | char | символ акцента |

**Возвращаемое значение:**
[IMathAccent](../../com.aspose.slides/imathaccent) - новый математический акцент