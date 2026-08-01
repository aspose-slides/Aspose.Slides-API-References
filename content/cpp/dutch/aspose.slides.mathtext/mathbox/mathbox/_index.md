---
title: MathBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert MathBox met het opgegeven element als argument
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) constructor

Initialiseert [MathBox](../) met het opgegeven element als argument

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waarop de doos wordt toegepast. Kan null zijn. |
## Opmerkingen



Voorbeeld: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)