---
title: Integral
second_title: Справочник по API Aspose.Slides для .NET
description: Принимает интеграл
type: docs
weight: 70
url: /ru/net/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Принимает интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | IMathElement | Нижний предел интеграла |
| upperLimit | IMathElement | Верхний предел интеграла |
| limitLocations | MathLimitLocations | местоположение пределов |

### Возвращаемое значение

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Принимает интеграл

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

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Берет интеграл без ограничений

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |

### Возвращаемое значение

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Принимает интеграл

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | MathIntegralTypes | Тип интеграла |
| lowerLimit | String | Нижний предел интеграла |
| upperLimit | String | Верхний предел интеграла |
| limitLocations | MathLimitLocations | местоположение пределов |

### Возвращаемое значение

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Принимает интеграл

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

Новый экземпляр типа[`IMathNaryOperator`](../../imathnaryoperator)

### Примеры

Пример:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Смотрите также

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* пространство имен [Aspose.Slides.MathText](../../mathelementbase)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
