---
title: Join()
second_title: Aspose.Slides für C++ API-Referenz
description: Verbindet ein mathematisches Element und bildet einen mathematischen Block
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) Methode


Verbindet ein mathematisches Element und bildet einen mathematischen Block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Das zu verbindende Element |

### Rückgabewert

Ein neues [IMathBlock](../../imathblock/) das diese Instanz und das angegebene Argument enthält
## Anmerkungen



Beispiel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) Methode


Verbindet einen mathematischen Text und bildet einen mathematischen Block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Mathematischer Text, der verbunden werden soll |

### Rückgabewert

Ein neues [IMathBlock](../../imathblock/) das diese Instanz und das angegebene Argument enthält
## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)