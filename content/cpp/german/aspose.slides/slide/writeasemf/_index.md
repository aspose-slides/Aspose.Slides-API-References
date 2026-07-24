---
title: WriteAsEmf()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert den Folieninhalt als EMF-Datei.
type: docs
weight: 170
url: /de/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) Methode

Speichert den Folieninhalt als EMF-Datei.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Zielstream |
## Anmerkungen

Das folgende Codebeispiel demonstriert, wie die erste Folie einer PowerPoint-Präsentation in eine Metadatei konvertiert wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Speichert die erste Folie als Metadatei
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Slide](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)