---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt IMathElement op op de opgegeven index.
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) methode


Haalt [IMathElement](../../imathelement/) op op de opgegeven index.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het item |

### Retourwaarde

Het wiskundige element.
## Opmerkingen


 

Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)