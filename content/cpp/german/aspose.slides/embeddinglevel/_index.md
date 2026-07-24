---
title: EmbeddingLevel
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Lizenzrechte für das Einbetten der Schriftart dar.
type: docs
weight: 5786
url: /de/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum


Represents the licensing rights for embedding the font.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) mit dieser Einstellung zeigen an, dass sie eingebettet und dauerhaft auf dem entfernten System von einer Anwendung installiert werden dürfen. Der Benutzer des entfernten Systems erwirbt dieselben Rechte, Pflichten und Lizenzen für diese Schriftart wie der ursprüngliche Käufer der Schriftart und unterliegt derselben Endbenutzer-Lizenzvereinbarung, Urheberrecht, Designpatent und/oder Markenrecht wie der ursprüngliche Käufer. |
| Restricted | 2 | [Fonts](../fonts/), bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder in irgendeiner Weise ausgetauscht werden, ohne vorher die Erlaubnis des rechtlichen Eigentümers einzuholen. |
| PreviewPrint | 4 | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und vorübergehend auf dem entfernten System geladen werden. Dokumente, die Preview-&-Print-Schriftarten enthalten, müssen im Modus \"read-only\" geöffnet werden; es können keine Änderungen am Dokument vorgenommen werden. |
| Editable | 8 | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, darf jedoch nur vorübergehend auf anderen Systemen installiert werden. Im Gegensatz zu Preview-&-Print-Schriftarten dürfen Dokumente, die Editable-Schriftarten enthalten, zum Lesen geöffnet werden, das Bearbeiten ist erlaubt und Änderungen können gespeichert werden. |
| NoSubsetting | 256 | Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht teilunterteilt werden. Andere Einbettungsbeschränkungen, die in den Bits 0-3 und 9 angegeben sind, gelten ebenfalls. |
| BitmapOnly | 512 | Wenn dieses Bit gesetzt ist, dürfen nur im Font enthaltene Bitmaps eingebettet werden. Konturdaten dürfen nicht eingebettet werden. Wenn im Font keine Bitmaps verfügbar sind, wird der Font als nicht einbettbar betrachtet und die Einbettungsdienste schlagen fehl. |

## Siehe auch

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)