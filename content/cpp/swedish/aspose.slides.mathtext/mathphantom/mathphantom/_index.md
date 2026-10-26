---
title: MathPhantom()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av MathPhantom-klassen med det angivna basmatteelementet.
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) konstruktor


Initierar en ny instans av klassen [MathPhantom](../) med det angivna basmatteelementet.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Den bas-[IMathElement](../../imathelement/) vars synlighet och layout kommer att kontrolleras av phantom. Detta element definierar innehållet som kan döljas eller visas, men som fortfarande påverkar den geometriska justeringen av den omgivande matematiken. |
## Anmärkningar



Phantom-elementet används för att reservera eller undertrycka det visuella utrymmet för dess basuttryck utan att nödvändigtvis visa det. Det motsvarar OMML-elementet **<m:phant>**. 

Exempel: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathPhantom](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)