---
title: MathDelimiter()
second_title: Aspose.Slides för C++ API-referens
description: Initierar MathDelimiter med det angivna elementet som enda basargument
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) konstruktor


Initierar [MathDelimiter](../) med det specificerade elementet som enda basargument

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Baselementet som avgränsaren tillämpas på. Kan vara null. |
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)