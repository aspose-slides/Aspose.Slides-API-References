---
title: Delimit
second_title: Справочник по API Aspose.Slides для .NET
description: Разделяет все дочерние элементы символом-разделителем без скобок
type: docs
weight: 30
url: /ru/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock.Delimit method

Разделяет все дочерние элементы символом-разделителем (без скобок)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | Char | Символ, используемый в качестве разделителя |

### Возвращаемое значение

Экземпляр элемента IMathDelimiter

### Примеры

Пример:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Смотрите также

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathBlock](../../imathblock)
* пространство имен [Aspose.Slides.MathText](../../imathblock)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
