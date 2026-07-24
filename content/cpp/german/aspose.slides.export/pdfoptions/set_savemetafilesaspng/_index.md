---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides für C++ API-Referenz
description: true, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Schreiben bool.
type: docs
weight: 339
url: /de/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) Methode


true, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Schreiben **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Hinweise


Standard ist **true**. Das Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das Png-Format konvertiert und als Rasterbild im Pdf gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel kann bei der Konvertierung des Metafile in PNG während der Skalierung des resultierenden Dokuments ein Qualitätsverlust auftreten. Wenn das Metafile in Pdf-Vektorgrafiken konvertiert wird, können Leistungsprobleme im Pdf-Betrachter auftreten. 
## Siehe auch

* Klasse [PdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)