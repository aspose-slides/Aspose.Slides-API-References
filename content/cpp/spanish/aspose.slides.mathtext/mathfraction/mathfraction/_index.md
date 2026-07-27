---
title: MathFraction()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicializa MathFraction con el numerador, denominador y tipo especificados
type: docs
weight: 53
url: /es/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) constructor


Inicializa [MathFraction](../) con el numerador, denominador y tipo especificados

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción |
## Observaciones



Ejemplo: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Inicializa un [MathFraction](../) de tipo 'Bar' con el numerador y denominador especificados

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
## Observaciones



Ejemplo: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## Ver también

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)