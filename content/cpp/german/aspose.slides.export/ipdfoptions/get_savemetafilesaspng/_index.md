---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides für C++ API Referenz
description: True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen bool.
type: docs
weight: 287
url: /de/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() Methode


True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Bemerkungen


Standard ist **true**. Ein Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf **true** gesetzt ist, wird das Quell-Metadatei-Bild in das Png-Format konvertiert und als Rasterbild im Pdf gespeichert. Wenn SaveMetafilesAsPng auf **false** gesetzt ist, wird die Quell-Metadatei in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel, wenn Metadatei in PNG konvertiert wird, kann beim Skalieren des resultierenden Dokuments ein gewisser Qualitätsverlust auftreten. Wenn Metadatei in Pdf-Vektorgrafiken konvertiert wird, können Leistungsprobleme im Pdf-Betrachter auftreten. 
## Siehe auch

* Klasse [IPdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)