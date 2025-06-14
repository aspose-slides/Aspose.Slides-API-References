---
title: Join
second_title: Aspose.Sildes для .NET API Reference
description: Объединяет математический элемент и формирует математический блок
type: docs
weight: 90
url: /ru/aspose.slides.mathtext/imathelement/join/
---

## Join(IMathElement) {#join}

Объединяет математический элемент и формирует математический блок

```csharp
public IMathBlock Join(IMathElement mathElement)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | IMathElement | Элемент, который нужно объединить |

### Значение, возвращаемое методом

Новый IMathBlock, содержащий этот экземпляр и указанный аргумент

### Примеры

Пример:

```csharp
[C#]
IMathElement element1 = new MathematicalText("x");
IMathElement element2 = new MathematicalText("y");
IMathBlock block = element1.Join(element2);
```

### Смотрите также

* интерфейс [IMathBlock](../../imathblock)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## Join(string) {#join_1}

Объединяет математический текст и формирует математический блок

```csharp
public IMathBlock Join(string mathText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | String | Математический текст для объединения |

### Значение, возвращаемое методом

Н новый IMathBlock, содержащий этот экземпляр и указанный аргумент

### Примеры

Пример:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathBlock block = element.Join("+y");
```

### Смотрите также

* интерфейс [IMathBlock](../../imathblock)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->