---
title: IBehaviorProperty
second_title: Aspose.Slides for Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /ru/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Представляет типы свойств для поведения анимации. Следует список свойств из https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx и https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Значение свойства |
| [isCustom()](#isCustom--) | Показывает, не относится ли это свойство к списку предопределённых свойств в спецификации: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |

### getValue() {#getValue--}
```
public abstract String getValue()
```

Значение свойства

**Возвращаемое значение:**
java.lang.String

### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

Показывает, не относится ли это свойство к списку предопределённых свойств в спецификации: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Возвращаемое значение:**
boolean