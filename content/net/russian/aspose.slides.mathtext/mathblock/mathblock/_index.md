---
title: MathBlock
second_title: Справочник по API Aspose.Slides для .NET
description: Инициализирует новый экземпляр класса MathBlock.
type: docs
weight: 10
url: /ru/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock() {#constructor}

Инициализирует новый экземпляр класса MathBlock.

```csharp
public MathBlock()
```

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Смотрите также

* class [MathBlock](../../mathblock)
* пространство имен [Aspose.Slides.MathText](../../mathblock)
* сборка [Aspose.Slides](../../../)

---

## MathBlock(IMathElement) {#constructor_1}

Создает новый математический блок и помещает в него указанный элемент

```csharp
public MathBlock(IMathElement mathElement)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | IMathElement | Математический элемент для помещения в блок |

### Примеры

Пример:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
```

### Смотрите также

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* пространство имен [Aspose.Slides.MathText](../../mathblock)
* сборка [Aspose.Slides](../../../)

---

## MathBlock(IEnumerable&lt;IMathElement&gt;) {#constructor_2}

Создает новый математический блок и помещает в него указанные элементы

```csharp
public MathBlock(IEnumerable<IMathElement> mathElements)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | IEnumerable`1 | Математические элементы для размещения в блоке |

### Примеры

Пример:

```csharp
[C#]
var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
MathBlock mathBlock = new MathBlock(elems);
```

### Смотрите также

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* пространство имен [Aspose.Slides.MathText](../../mathblock)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
