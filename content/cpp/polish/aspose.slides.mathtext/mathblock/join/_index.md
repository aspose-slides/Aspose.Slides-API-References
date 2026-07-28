---
title: Join()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dołącza element matematyczny do tego bloku matematycznego
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metoda


Dołącza element matematyczny do tego bloku matematycznego

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element do dołączenia |

### Return Value

Aktualna instancja [IMathBlock](../../imathblock/)
## Uwagi



Przykład: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metoda


Dołącza tekst matematyczny do tego bloku matematycznego

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Tekst matematyczny do dołączenia |

### Return Value

Nowy [IMathBlock](../../imathblock/) zawierający tę instancję i określony argument
## Uwagi



Przykład: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBlock](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)