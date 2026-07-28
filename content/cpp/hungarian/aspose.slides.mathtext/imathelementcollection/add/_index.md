---
title: Add()
second_title: Aspose.Slides C++ API referenciája
description: A gyűjtemény végére ad egy matematikai elemet.
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) metódus

A gyűjtemény végére ad egy matematikai elemet.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A [IMathElement](../../imathelement/) a gyűjtemény végére hozzáadandó. |
## Megjegyzések


Példa: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)