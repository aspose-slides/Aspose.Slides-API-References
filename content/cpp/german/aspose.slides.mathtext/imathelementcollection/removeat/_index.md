---
title: RemoveAt()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt das Element am angegebenen Index der Sammlung.
type: docs
weight: 105
url: /de/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) Methode


Entfernt das Element am angegebenen Index der Sammlung.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index des zu entfernenden Elements. |
## Anmerkungen



Beispiel: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## Siehe auch

* Klasse [IMathElementCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)