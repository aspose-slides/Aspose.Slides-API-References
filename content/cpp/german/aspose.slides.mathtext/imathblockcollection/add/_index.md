---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt IMathBlock am Ende der Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) Methode


Fügt [IMathBlock](../../imathblock/) am Ende der Sammlung hinzu.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Ein mathematischer Block, der am Ende der Sammlung hinzugefügt wird. |
## Hinweise



Beispiel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)