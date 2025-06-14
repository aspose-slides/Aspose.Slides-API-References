---
title: IBlobManagementOptions
second_title: Aspose.Slides für .NET API Referenz
description: Ein Binary Large Object BLOB ist eine binäre Daten, die als eine einzige Einheit gespeichert ist – d.h. BLOB kann ein Audio-, Video- oder die Präsentation selbst sein. Eine Reihe von Techniken wird verwendet, um den Speicherverbrauch beim Arbeiten mit BLOBs zu optimieren – die bereits in der Präsentation gespeichert wurden oder später programmgesteuert hinzugefügt werden können. Mit IBlobManagementOptions./iblobmanagementoptions können Sie verschiedene Verhaltensaspekte bezüglich der Handhabung von BLOBs für die Lebensdauer der IPresentation./ipresentation Instanz ändern.
type: docs
weight: 5170
url: /de/aspose.slides/iblobmanagementoptions/
---

## IBlobManagementOptions Schnittstelle

Ein Binary Large Object (BLOB) ist eine binäre Daten, die als eine einzige Einheit gespeichert ist – d.h. BLOB kann ein Audio-, Video- oder die Präsentation selbst sein. Eine Reihe von Techniken wird verwendet, um den Speicherverbrauch beim Arbeiten mit BLOBs zu optimieren – die bereits in der Präsentation gespeichert wurden oder später programmgesteuert hinzugefügt werden können. Mit [`IBlobManagementOptions`](../iblobmanagementoptions) können Sie verschiedene Verhaltensaspekte bezüglich der Handhabung von BLOBs für die Lebensdauer der [`IPresentation`](../ipresentation) Instanz ändern.

```csharp
public interface IBlobManagementOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsTemporaryFilesAllowed](../../aspose.slides/iblobmanagementoptions/istemporaryfilesallowed) { get; set; } | Diese Eigenschaft definiert, ob temporäre Dateien erstellt werden dürfen, während mit BLOBs gearbeitet wird, was den Speicherverbrauch erheblich verringert, aber Berechtigungen zum Erstellen von Dateien erfordert. Alle Dateien werden gelöscht, nachdem die Arbeit mit der Präsentation beendet ist. |
| [MaxBlobsBytesInMemory](../../aspose.slides/iblobmanagementoptions/maxblobsbytesinmemory) { get; set; } | Definiert die maximale Menge (in Bytes), die alle BLOBs insgesamt im Speicher belegen dürfen. Zunächst werden alle BLOBs standardmäßig in den Speicher geladen, und erst wenn das von dieser Eigenschaft definierte Limit erreicht ist, können andere Mechanismen (wie temporäre Dateien) einbezogen werden. In Bezug auf die Leistung ist die effizienteste Methode, BLOBs im Speicher zu speichern, aber andererseits führt dies zu einem hohen Speicherverbrauch, was unerwünscht sein kann. Mit dieser Eigenschaft können Sie das optimale Verhalten für Ihre Umgebung oder andere Anforderungen festlegen. Diese Eigenschaft wird ignoriert, wenn [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) auf false gesetzt ist. Es macht keinen Sinn, die maximalen BLOBs im Speicher zu begrenzen, da, wenn [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) auf false gesetzt ist, der Speicher der einzige Ort ist, an dem BLOBs gespeichert werden können. Der Standardwert beträgt 629.145.600 Bytes (600 MB). |
| [PresentationLockingBehavior](../../aspose.slides/iblobmanagementoptions/presentationlockingbehavior) { get; set; } | Diese Eigenschaft definiert, ob eine Instanz der Präsentationsklasse Eigentümer der Quelle - Datei oder Stream während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer der Präsentationsinstanz nicht geändert werden. Dies ist ein Beispiel: |
| [TempFilesRootPath](../../aspose.slides/iblobmanagementoptions/tempfilesrootpath) { get; set; } | Der Stammordner, in dem temporäre Dateien erstellt werden. Das vorübergehende Systemverzeichnis wird standardmäßig verwendet. Der Hosting-Prozess sollte die Berechtigungen haben, dort Dateien und Ordner zu erstellen. |

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->