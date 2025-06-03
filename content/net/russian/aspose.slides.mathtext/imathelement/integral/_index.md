---
title: Integral
second_title: Ссылка API Aspose.Slides для .NET
description: Берет интеграл
type: docs
weight: 80
url: /ru/aspose.slides.mathtext/imathelement/integral/
---

## Интеграл(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Берет интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | IMathElement | Нижний предел интеграла |
| upperLimit | IMathElement | Верхний предел интеграла |
| limitLocations | MathLimitLocations | Местоположение пределов |

### Возвращаемое значение

Новый экземпляр типа [`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### См. также

* интерфейс [IMathNaryOperator](../../imathnaryoperator)
* перечисление [MathIntegralTypes](../../mathintegraltypes)
* перечисление [MathLimitLocations](../../mathlimitlocations)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## Интеграл(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Берет интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | IMathElement | Нижний предел интеграла |
| upperLimit | IMathElement | Верхний предел интеграла |

### Возвращаемое значение

Новый экземпляр типа [`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### См. также

* интерфейс [IMathNaryOperator](../../imathnaryoperator)
* перечисление [MathIntegralTypes](../../mathintegraltypes)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## Интеграл(MathIntegralTypes) {#integral}

Берет интеграл без пределов

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |

### Возвращаемое значение

Новый экземпляр типа [`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### См. также

* интерфейс [IMathNaryOperator](../../imathnaryoperator)
* перечисление [MathIntegralTypes](../../mathintegraltypes)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## Интеграл(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Берет интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | String | Нижний предел интеграла |
| upperLimit | String | Верхний предел интеграла |
| limitLocations | MathLimitLocations | Местоположение пределов |

### Возвращаемое значение

Новый экземпляр типа [`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### См. также

* интерфейс [IMathNaryOperator](../../imathnaryoperator)
* перечисление [MathIntegralTypes](../../mathintegraltypes)
* перечисление [MathLimitLocations](../../mathlimitlocations)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

---

## Интеграл(MathIntegralTypes, string, string) {#integral_3}

Берет интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | String | Нижний предел интеграла |
| upperLimit | String | Верхний предел интеграла |

### Возвращаемое значение

Новый экземпляр типа [`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### См. также

* интерфейс [IMathNaryOperator](../../imathnaryoperator)
* перечисление [MathIntegralTypes](../../mathintegraltypes)
* интерфейс [IMathElement](../../imathelement)
* пространство имен [Aspose.Slides.MathText](../../imathelement)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->