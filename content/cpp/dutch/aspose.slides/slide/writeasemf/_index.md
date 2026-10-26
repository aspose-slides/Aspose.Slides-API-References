---
title: WriteAsEmf()
second_title: Aspose.Slides voor C++ API-referentie
description: Slaat de inhoud van de dia op als een EMF-bestand.
type: docs
weight: 170
url: /nl/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) methode


Slaat de inhoud van de dia op als een EMF-bestand.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Doel-stream |
## Opmerkingen



Het volgende codevoorbeeld laat zien hoe je de eerste dia van een PowerPoint-presentatie kunt converteren naar een metafile. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Slaat de eerste dia op als een metafile
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Slide](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)