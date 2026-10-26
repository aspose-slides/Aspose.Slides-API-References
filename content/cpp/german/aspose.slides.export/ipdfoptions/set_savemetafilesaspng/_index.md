---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides für C++ API-Referenz
description: True, um alle in einer Präsentation verwendeten Metafiles in PNG-Bilder zu konvertieren. Write bool.
type: docs
weight: 300
url: /de/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) Methode


True, um alle in einer Präsentation verwendeten Metafiles in PNG-Bilder zu konvertieren. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Hinweise


Standard ist **true**. Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das Png-Format konvertiert und als Rasterbild in Pdf gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel kann bei einer Konvertierung von Metafile zu PNG während der Skalierung des resultierenden Dokuments ein gewisser Qualitätsverlust auftreten. Wenn Metafile zu Pdf-Vektorgrafiken konvertiert wird, können Leistungsprobleme im Pdf-Ansichtstool auftreten.

## Siehe auch

* Klasse [IPdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)