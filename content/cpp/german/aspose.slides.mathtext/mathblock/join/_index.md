---
title: Join()
second_title: Aspose.Slides für C++ API-Referenz
description: Verknüpft ein mathematisches Element mit diesem mathematischen Block
type: docs
weight: 183
url: /de/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) Methode


Verknüpft ein mathematisches Element mit diesem mathematischen Block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das zu verknüpfende Element |

### Rückgabewert

Die aktuelle Instanz von [IMathBlock](../../imathblock/)
## Hinweise



Beispiel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) Methode


Verknüpft einen mathematischen Text mit diesem mathematischen Block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Der zu verknüpfende mathematische Text |

### Rückgabewert

Eine neue [IMathBlock](../../imathblock/), die diese Instanz und das angegebene Argument enthält
## Hinweise



Beispiel: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)