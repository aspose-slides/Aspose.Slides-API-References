---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior Aufzählung

Das **io.RawIOBase**, das an eine Methode übergeben wird, wird als Binary Large Object (BLOB) betrachtet (siehe [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions) Beschreibung). Die Werte dieser Aufzählung geben an, wie das **io.RawIOBase** behandelt werden soll, wenn es an die Methode übergeben wird. Abhängig von den Anforderungen können unterschiedliche Entscheidungen getroffen werden, um das effizienteste Verhalten zu gewährleisten.

Der Typ LoadingStreamBehavior stellt die folgenden Mitglieder bereit:

## Felder

| Feld | Beschreibung |
| :- | :- |
| READ_STREAM_AND_RELEASE | Der Stream wird bis zum Ende gelesen und dann freigegeben – d. h. es wird garantiert, dass dieser Stream <br/>            von keiner [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Instanz in Zukunft verwendet wird. Er kann vom Client-Code <br/>            geschlossen oder auf andere Weise verwendet werden. |
| KEEP_LOCKED | Der Stream wird innerhalb des [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Objekts gesperrt, d. h. das Eigentum am <br/>            Stream wird übertragen. Das [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)-Objekt ist dafür verantwortlich, <br/>            den Stream korrekt zu entsorgen, wenn dieses Objekt selbst entsorgt wird. <br/>            Dieses Verhalten ist äußerst nützlich, wenn Sie eine große BLOB-Datei serialisieren müssen (wie z. B. ein großes <br/>            Video- oder Audio-Datei – siehe [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions) Beschreibung) und das Laden <br/>            dieser Datei in den Speicher oder andere Leistungsprobleme verhindern wollen. Sie können einfach den **System.IO.FileStream** <br/>            für diese Datei öffnen und an eine Methode übergeben, wobei Sie [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/de/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior wählen. |

### Siehe auch
* Klasse [`IBlobManagementOptions`](/slides/python-net/de/aspose.slides/iblobmanagementoptions)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)