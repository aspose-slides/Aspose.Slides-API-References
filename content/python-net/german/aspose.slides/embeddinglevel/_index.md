---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/embeddinglevel/
---
## EmbeddingLevel Aufzählung

Stellt die Lizenzrechte für das Einbetten der Schriftart dar.

Der Typ EmbeddingLevel stellt die folgenden Member bereit:

## Felder

| Feld | Beschreibung |
| :- | :- |
| INSTALLABLE | Schriftarten mit dieser Einstellung dürfen von einer Anwendung eingebettet und dauerhaft auf dem Remote-System installiert werden. <br/>            Der Benutzer des Remote-Systems erwirbt die gleichen Rechte, Pflichten und Lizenzen für diese Schriftart wie der ursprüngliche Käufer, <br/>            und unterliegt derselben Endbenutzer-Lizenzvereinbarung, dem Urheberrecht, dem Design-Patent und/oder der Marke wie der ursprüngliche Käufer. |
| RESTRICTED | Schriftarten, bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder ausgetauscht werden, ohne vorher die Erlaubnis des Rechtsinhabers einzuholen. |
| PREVIEW_PRINT | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und vorübergehend auf dem Remote-System geladen werden. Dokumente, die Vorschau-& <br/>            Druck-Schriftarten enthalten, müssen im "Nur-Lese-Modus" geöffnet werden; Änderungen dürfen nicht am Dokument vorgenommen werden. |
| EDITABLE | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, muss jedoch nur vorübergehend auf anderen Systemen installiert werden. Im Gegensatz zu Vorschau-& <br/>            Druck-Schriftarten dürfen Dokumente, die editierbare Schriftarten enthalten, zum Lesen geöffnet werden, Bearbeitungen sind zulässig und Änderungen können gespeichert werden. |
| NO_SUBSETTING | Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht unterteilt werden. Weitere Einbettungsbeschränkungen, die in den Bits 0-3 und 9 angegeben sind, gelten ebenfalls. |
| BITMAP_ONLY | Wenn dieses Bit gesetzt ist, dürfen nur Bitmaps, die in der Schriftart enthalten sind, eingebettet werden. Outline-Daten dürfen nicht eingebettet werden. Gibt es keine Bitmaps in der Schriftart, <br/>            gilt die Schriftart als nicht einbettbar und die Einbettungsdienste schlagen fehl. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)