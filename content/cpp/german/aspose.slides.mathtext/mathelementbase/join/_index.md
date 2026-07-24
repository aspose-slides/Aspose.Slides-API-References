---
title: Join()
second_title: Aspose.Slides für C++ API-Referenz
description: Verbindet ein mathematisches Element und bildet einen mathematischen Block
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) Methode

Verbindet ein mathematisches Element und bildet einen mathematischen Block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das zu verbindende Element |

### Rückgabewert

Ein neues [IMathBlock](../../imathblock/) das diese Instanz und das angegebene Argument enthält
## Bemerkungen



Beispiel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) Methode

Verbindet einen mathematischen Text und bildet einen mathematischen Block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Der zu verbindende mathematische Text |

### Rückgabewert

Ein neues [IMathBlock](../../imathblock/) das diese Instanz und das angegebene Argument enthält
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)