---
title: MathDelimiter()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert MathDelimiter mit dem angegebenen Element als einziges Basisargument
type: docs
weight: 144
url: /de/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) constructor


Initialisiert [MathDelimiter](../) mit dem angegebenen Element als einziges Basisargument

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement, auf das das Trennzeichen angewendet wird. Kann null sein. |
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)