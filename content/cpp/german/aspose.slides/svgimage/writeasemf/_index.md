---
title: WriteAsEmf()
second_title: Aspose.Slides für C++ API Referenz
description: Speichert das SVG-Bild als EMF-Datei.
type: docs
weight: 66
url: /de/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) Methode


Speichert das SVG-Bild als EMF-Datei.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Zielstream |
## Bemerkungen



Das folgende Beispiel zeigt, wie das SVG-Bild in eine Metadatei gespeichert wird. 
```cpp
// Erstellt das neue SVG-Bild
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Speichert das SVG-Bild als Metadatei
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Dieses Beispiel zeigt, wie das SVG-Bild als Metadatei zur Bildsammlung der Präsentation hinzugefügt wird. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Erstellt das neue SVG-Bild
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Speichert das SVG-Bild als Metadatei
svgImage->WriteAsEmf(memStream);
// Fügt Metadatei zur Bildsammlung hinzu
pres->get_Images()->AddImage(memStream->ToArray());
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [SvgImage](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)