---
title: Join()
second_title: Aspose.Slides för C++ API-referens
description: Fogar samman ett matematiskt element och bildar ett matematiskt block
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metod

Fogar samman ett matematiskt element och bildar ett matematiskt block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The element to be joined |

### Returvärde

Ett nytt [IMathBlock](../../imathblock/) som innehåller detta objekt och angivet argument

## Anmärkningar



Exempel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metod

Fogar samman en matematisk text och bildar ett matematiskt block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Mathematical text to be joined |

### Returvärde

Ett nytt [IMathBlock](../../imathblock/) som innehåller detta objekt och angivet argument

## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)