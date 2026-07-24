---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides für C++ API-Referenz
description: True, um alle in einer Präsentation verwendeten Metafiles in PNG-Bilder zu konvertieren. Lies bool.
type: docs
weight: 326
url: /de/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() method


True, um alle in einer Präsentation verwendeten Metafiles in PNG-Bilder zu konvertieren. Lesen **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Bemerkungen


Standard ist **true**. Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das Png-Format konvertiert und als Rasterbild in Pdf gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann bei der Konvertierung von Metafile zu PNG bei der Skalierung des resultierenden Dokuments ein Qualitätsverlust auftreten. Bei der Konvertierung von Metafile zu Pdf-Vektorgrafiken können Performance-Probleme im Pdf-Betrachtungsprogramm auftreten.

## Siehe Auch

* Klasse [PdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)