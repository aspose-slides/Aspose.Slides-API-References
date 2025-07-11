---
title: MaxBlobsBytesInMemory
second_title: Aspose.Slides für .NET API Referenz
description: Definiert die maximale Menge in Bytes, die alle BLOBs insgesamt im Speicher占占占占占占占. Zuerst werden alle BLOBs standardmäßig in den Speicher geladen, und erst wenn das festgelegte Limit dieser Eigenschaft erreicht wird, können andere Mechanismen wie temporäre Dateien einbezogen werden. In Bezug auf die Leistung ist die effizienteste Methode das Speichern von BLOBs im Speicher, aber auf der anderen Seite führt dies zu einem hohen Speicherverbrauch, was unerwünscht sein kann. Mit dieser Eigenschaft können Sie das optimale Verhalten für Ihre Umgebung oder andere Anforderungen festlegen. Diese Eigenschaft wird ignoriert, wenn IsTemporaryFilesAllowed../istemporaryfilesallowed auf false gesetzt ist. Es macht keinen Sinn, die maximalen BLOBs im Speicher zu begrenzen, da der Speicher der einzige Ort ist, an dem BLOBs gespeichert werden können, wenn IsTemporaryFilesAllowed../istemporaryfilesallowed auf false gesetzt ist. Der Standardwert beträgt 629.145.600 Bytes 600 MB.
type: docs
weight: 30
url: /de/aspose.slides/blobmanagementoptions/maxblobsbytesinmemory/
---

## BlobManagementOptions.MaxBlobsBytesInMemory-Eigenschaft

Definiert die maximale Menge (in Bytes), die alle BLOBs insgesamt im Speicher占占占占占占占. Zuerst werden alle BLOBs standardmäßig in den Speicher geladen, und erst wenn das festgelegte Limit dieser Eigenschaft erreicht wird, können andere Mechanismen (wie temporäre Dateien) einbezogen werden. In Bezug auf die Leistung ist die effizienteste Methode das Speichern von BLOBs im Speicher, aber auf der anderen Seite führt dies zu einem hohen Speicherverbrauch, was unerwünscht sein kann. Mit dieser Eigenschaft können Sie das optimale Verhalten für Ihre Umgebung oder andere Anforderungen festlegen. Diese Eigenschaft wird ignoriert, wenn [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) auf false gesetzt ist. Es macht keinen Sinn, die maximalen BLOBs im Speicher zu begrenzen, da der Speicher der einzige Ort ist, an dem BLOBs gespeichert werden können, wenn [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) auf false gesetzt ist. Der Standardwert beträgt 629.145.600 Bytes (600 MB).

```csharp
public ulong MaxBlobsBytesInMemory { get; set; }
```

### Siehe Auch

* Klasse [BlobManagementOptions](../../blobmanagementoptions)
* Namensraum [Aspose.Slides](../../blobmanagementoptions)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->