---
title: MathematicalText
second_title: Справочник по API Aspose.Slides для .NET
description: Конструктор по умолчанию создать String.Empty Value
type: docs
weight: 10
url: /ru/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText() {#constructor}

Конструктор по умолчанию (создать String.Empty Value)

```csharp
public MathematicalText()
```

### Примеры

Пример:

```csharp
[C#]
MathematicalText mathText = new MathematicalText();
```

### Смотрите также

* class [MathematicalText](../../mathematicaltext)
* пространство имен [Aspose.Slides.MathText](../../mathematicaltext)
* сборка [Aspose.Slides](../../../)

---

## MathematicalText(char) {#constructor_1}

Создать MathText с одиночным символом

```csharp
public MathematicalText(char mathSymbol)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | Char | одиночный символ |

### Примеры

Пример:

```csharp
[C#]
MathematicalText mathText = new MathematicalText('$');
```

### Смотрите также

* class [MathematicalText](../../mathematicaltext)
* пространство имен [Aspose.Slides.MathText](../../mathematicaltext)
* сборка [Aspose.Slides](../../../)

---

## MathematicalText(string) {#constructor_2}

Создать MathematicalText из текста

```csharp
public MathematicalText(string mathText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | String | текстовое значение |

### Примеры

Пример:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Смотрите также

* class [MathematicalText](../../mathematicaltext)
* пространство имен [Aspose.Slides.MathText](../../mathematicaltext)
* сборка [Aspose.Slides](../../../)

---

## MathematicalText(string, IPortionFormat) {#constructor_3}

Создать MathematicalText из текста и настроек формата

```csharp
public MathematicalText(string mathText, IPortionFormat portionFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | String | text value |
| partionFormat | IPortionFormat | настройки формата текста |

### Примеры

Пример:

```csharp
[C#]
IPortionFormat format = new PortionFormat() { FontHeight = 12 };
MathematicalText mathText = new MathematicalText("x+y", format);
```

### Смотрите также

* interface [IPortionFormat](../../../aspose.slides/iportionformat)
* class [MathematicalText](../../mathematicaltext)
* пространство имен [Aspose.Slides.MathText](../../mathematicaltext)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
