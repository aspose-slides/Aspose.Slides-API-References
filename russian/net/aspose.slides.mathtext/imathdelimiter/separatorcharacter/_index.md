---
title: SeparatorCharacter
second_title: Справочник по API Aspose.Slides для .NET
description: Символ разделителя-разделителя определяет символ разделяющий аргументы в объекте-разделителе. По умолчаниюx7C.
type: docs
weight: 70
url: /ru/net/aspose.slides.mathtext/imathdelimiter/separatorcharacter/
---
## IMathDelimiter.SeparatorCharacter property

Символ разделителя-разделителя определяет символ, разделяющий аргументы в объекте-разделителе. По умолчанию:'&#x7C;'.

```csharp
public char SeparatorCharacter { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.SeparatorCharacter = '$';
```

### Смотрите также

* interface [IMathDelimiter](../../imathdelimiter)
* пространство имен [Aspose.Slides.MathText](../../imathdelimiter)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->