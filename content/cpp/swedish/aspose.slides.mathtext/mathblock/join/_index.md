---
title: Join()
second_title: Aspose.Slides för C++ API-referens
description: Går samman med ett matematiskt element med detta matematiska block
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metod


Går samman med ett matematiskt element med detta matematiska block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elementet som ska gå samman |

### Returvärde

Den aktuella instansen av [IMathBlock](../../imathblock/)
## Anmärkningar



Exempel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metod


Går samman med en matematisk text med detta matematiska block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Matematisk text som ska gå samman |

### Returvärde

En ny [IMathBlock](../../imathblock/) som innehåller denna instans och angivet argument
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBlock](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)