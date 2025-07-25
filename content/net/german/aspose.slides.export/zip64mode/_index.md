---
title: Zip64Mode
second_title: Aspose.Sildes für .NET API Referenz
description: Legt fest, wann ZIP64-Format Erweiterungen für OpenXML-Dateien verwendet werden sollen.
type: docs
weight: 4550
url: /de/aspose.slides.export/zip64mode/
---

## Zip64Mode Enumeration

Legt fest, wann ZIP64-Format Erweiterungen für OpenXML-Dateien verwendet werden sollen.

```csharp
public enum Zip64Mode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Never | `0` | ZIP64-Format Erweiterungen nicht verwenden. |
| IfNecessary | `1` | ZIP64-Format Erweiterungen verwenden, wenn nötig. |
| Always | `2` | Immer ZIP64-Format Erweiterungen verwenden. |

### Anmerkungen

Eine OpenXML-Datei ist ein ZIP-Archiv, das eine Grenze von 4 GB (2^32 Byte) für die unkomprimierte Größe einer Datei, die komprimierte Größe einer Datei und die gesamte Größe des Archivs sowie eine Grenze von 65.535 (2^16-1) Dateien im Archiv hat. ZIP64-Format Erweiterungen erhöhen diese Grenzen auf 2^64.

### Siehe Auch

* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->