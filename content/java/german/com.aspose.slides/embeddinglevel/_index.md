---
title: EmbeddingLevel
second_title: Aspose.Slides für Java API Referenz
description: Stellt die Lizenzrechte für das Einbetten der Schriftart dar.
type: docs
url: /de/com.aspose.slides/embeddinglevel/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Stellt die Lizenzrechte für das Einbetten der Schriftart dar.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Installable](#Installable) | Schriftarten mit dieser Einstellung zeigen an, dass sie von einer Anwendung in das entfernte System eingebettet und dort dauerhaft installiert werden können. |
| [Restricted](#Restricted) | Schriftarten, bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder ausgetauscht werden, ohne vorher die Erlaubnis des rechtmäßigen Eigentümers einzuholen. |
| [PreviewPrint](#PreviewPrint) | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und vorübergehend im entfernten System geladen werden. |
| [Editable](#Editable) | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, muss jedoch nur vorübergehend auf anderen Systemen installiert werden. |
| [NoSubsetting](#NoSubsetting) | Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht teilunterteilt werden. |
| [BitmapOnly](#BitmapOnly) | Wenn dieses Bit gesetzt ist, dürfen nur im Font enthaltene Bitmaps eingebettet werden. |
### Installable {#Installable}
```
public static final int Installable
```


Schriftarten mit dieser Einstellung zeigen an, dass sie von einer Anwendung in das entfernte System eingebettet und dort dauerhaft installiert werden können. Der Benutzer des entfernten Systems erwirbt die gleichen Rechte, Pflichten und Lizenzen für diese Schriftart wie der ursprüngliche Käufer und unterliegt derselben Endbenutzer-Lizenzvereinbarung, dem Urheberrecht, dem Designpatent und/oder der Markenkennzeichnung wie der ursprüngliche Käufer.

### Restricted {#Restricted}
```
public static final int Restricted
```


Schriftarten, bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder ausgetauscht werden, ohne vorher die Erlaubnis des rechtmäßigen Eigentümers einzuholen.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```


Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und vorübergehend im entfernten System geladen werden. Dokumente, die Preview & Print Schriftarten enthalten, müssen im \"read-only;\" Modus geöffnet werden; Änderungen am Dokument sind nicht zulässig.

### Editable {#Editable}
```
public static final int Editable
```


Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, muss jedoch nur vorübergehend auf anderen Systemen installiert werden. Im Gegensatz zu Preview & Print Schriftarten können Dokumente, die Editable Schriftarten enthalten, zum Lesen geöffnet werden, das Bearbeiten ist zulässig und Änderungen können gespeichert werden.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```


Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht teilunterteilt werden. Weitere Einbettungsbeschränkungen, die in den Bits 0-3 und 9 angegeben sind, gelten ebenfalls.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```


Wenn dieses Bit gesetzt ist, dürfen nur im Font enthaltene Bitmaps eingebettet werden. Konturdaten dürfen nicht eingebettet werden. Wenn im Font keine Bitmaps vorhanden sind, gilt die Schriftart als nicht einbettbar und die Einbettungsdienste schlagen fehl.