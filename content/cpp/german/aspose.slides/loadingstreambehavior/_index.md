---
title: LoadingStreamBehavior
second_title: Aspose.Slides für C++ API Referenz
description: "Der System::IO::Stream, der einer Methode übergeben wird, wird als Binary Large Object (BLOB) betrachtet (siehe IBlobManagementOptions Beschreibung). Die Werte dieser Aufzählung geben an, wie der System::IO::Stream behandelt werden soll, wenn er an die Methode übergeben wird. Abhängig von den Anforderungen können verschiedene Entscheidungen getroffen werden, um das effizienteste Verhalten zu erzielen."
type: docs
weight: 6735
url: /de/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior Enum

Der [System::IO::Stream](../../system.io/stream/) an eine Methode übergebene wird als Binary Large Object (BLOB) betrachtet (siehe [IBlobManagementOptions](../iblobmanagementoptions/) Beschreibung). Die Werte dieser Aufzählung geben an, wie das [System::IO::Stream](../../system.io/stream/) behandelt werden soll, wenn es an die Methode übergeben wird. Abhängig von den Anforderungen können verschiedene Entscheidungen getroffen werden, um das effizienteste Verhalten zu ermöglichen.

```cpp
enum class LoadingStreamBehavior
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Der Stream wird bis zum Ende gelesen und danach freigegeben – d.h. es wird garantiert, dass dieser Stream in Zukunft nicht mehr von einer [IPresentation](../ipresentation/)-Instanz verwendet wird. Er kann vom Client-Code geschlossen oder auf andere Weise verwendet werden. |
| KeepLocked | 1 | Der Stream wird innerhalb des [IPresentation](../ipresentation/)-Objekts gesperrt, d.h. das Eigentum am Stream wird übertragen. Das [IPresentation](../ipresentation/)-Objekt ist dafür verantwortlich, den Stream korrekt zu entsorgen, wenn dieses Objekt selbst entsorgt wird. Dieses Verhalten ist äußerst nützlich, wenn Sie eine große BLOB-Datei (wie ein großes Video oder Audio – siehe [IBlobManagementOptions](../iblobmanagementoptions/) Beschreibung) serialisieren müssen und das Laden dieser Datei in den Speicher oder andere Leistungsprobleme verhindern wollen. Sie können einfach das [System::IO::FileStream](../../system.io/filestream/) für diese Datei öffnen und an eine Methode übergeben, wobei Sie [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior wählen. |

## Siehe auch

* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)