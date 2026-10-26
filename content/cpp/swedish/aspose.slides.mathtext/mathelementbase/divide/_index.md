---
title: Divide()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett bråk med denna täljare och angiven nämnare
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) method

Skapar ett bråk med detta täljare och angiven nämnare

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nämnare |

### Returvärde

ny fraktion
## Anmärkningar

Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) method

Skapar ett bråk med detta täljare och angiven nämnare

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nämnare |

### Returvärde

ny fraktion
## Anmärkningar

Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) method

Skapar ett bråk av den specificerade typen med detta täljare och angiven nämnare

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nämnare |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraktionstyp: Bar, NoBar, Skewed, Linear |

### Returvärde

ny fraktion
## Anmärkningar

Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) method

Skapar ett bråk av den specificerade typen med detta täljare och angiven nämnare

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nämnare |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraktionstyp: Bar, NoBar, Skewed, Linear |

### Returvärde

ny fraktion
## Anmärkningar

Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Se även

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFraction](../../imathfraction/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)