---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de eerste voorkoming van een specifiek object uit de collectie.
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method


Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het object dat uit de collectie moet worden verwijderd. |

### Retourwaarde

true als *item* succesvol uit de collectie is verwijderd; anders false. Deze methode geeft ook false terug als *item* niet wordt gevonden in de oorspronkelijke collectie.
## Opmerkingen



Voorbeeld: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathElementCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)