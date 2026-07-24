---
title: WriteAsEmf()
second_title: Aspose.Slides für C++ API-Referenz
description: Speichert das SVG-Bild als EMF-Datei.
type: docs
weight: 53
url: /de/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) Methode

Speichert das SVG-Bild als EMF-Datei.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ziel-Stream |
## Anmerkungen

Das nachfolgende Beispiel zeigt, wie das SVG-Bild in einer Metadatei gespeichert wird. 
```cpp
// Erstellt das neue SVG Bild
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Speichert das SVG Bild als Metadatei
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Dieses Beispiel zeigt, wie das SVG-Bild als Metadatei zur Bildsammlung der Präsentation hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Erstellt das neue SVG Bild
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Speichert das SVG Bild als Metadatei
svgImage->WriteAsEmf(memStream);
// Fügt die Metadatei zur Bildsammlung hinzu
pres->get_Images()->AddImage(memStream->ToArray());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ISvgImage](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)