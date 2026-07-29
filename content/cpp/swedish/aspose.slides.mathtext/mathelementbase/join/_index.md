---
title: Join()
second_title: Aspose.Slides för C++ API-referens
description: Förenar ett matematiskt element och bildar ett matematiskt block
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metod


Förenar ett matematiskt element och bildar ett matematiskt block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elementet som ska förenas |

### Returvärde

Ett nytt [IMathBlock](../../imathblock/) som innehåller detta objekt och angivet argument
## Anmärkningar



Exempel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metod


Förenar en matematisk text och bildar ett matematiskt block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Matematisk text som ska förenas |

### Returvärde

Ett nytt [IMathBlock](../../imathblock/) som innehåller detta objekt och angivet argument
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)