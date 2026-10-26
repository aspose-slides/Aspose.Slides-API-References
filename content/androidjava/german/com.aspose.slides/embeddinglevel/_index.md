---
title: EmbeddingLevel
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [Installable](#Installable) | Schriften mit dieser Einstellung zeigen an, dass sie von einer Anwendung eingebettet und dauerhaft auf dem entfernten System installiert werden können. |
| [Restricted](#Restricted) | Schriften, bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder auf irgendeine Weise ausgetauscht werden, ohne vorher die Erlaubnis des Rechteinhabers einzuholen. |
| [PreviewPrint](#PreviewPrint) | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und temporär auf dem entfernten System geladen werden. |
| [Editable](#Editable) | Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, muss jedoch nur temporär auf anderen Systemen installiert werden. |
| [NoSubsetting](#NoSubsetting) | Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht unterteilt werden. |
| [BitmapOnly](#BitmapOnly) | Wenn dieses Bit gesetzt ist, dürfen nur im Font enthaltene Bitmaps eingebettet werden. |
### Installable {#Installable}
```
public static final int Installable
```

Schriften mit dieser Einstellung zeigen an, dass sie von einer Anwendung eingebettet und dauerhaft auf dem entfernten System installiert werden können. Der Benutzer des entfernten Systems erwirbt die gleichen Rechte, Pflichten und Lizenzen für diese Schriftart wie der ursprüngliche Käufer der Schriftart und unterliegt derselben Endbenutzer-Lizenzvereinbarung, Urheberrecht, Designpatent und/oder Markenrechte wie der ursprüngliche Käufer.

### Restricted {#Restricted}
```
public static final int Restricted
```

Schriften, bei denen nur dieses Bit gesetzt ist, dürfen nicht modifiziert, eingebettet oder auf irgendeine Weise ausgetauscht werden, ohne vorher die Erlaubnis des Rechteinhabers einzuholen.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet und temporär auf dem entfernten System geladen werden. Dokumente, die Preview-&-Print-Schriften enthalten, müssen im schreibgeschützten Modus geöffnet werden; es können keine Änderungen am Dokument vorgenommen werden.

### Editable {#Editable}
```
public static final int Editable
```

Wenn dieses Bit gesetzt ist, darf die Schriftart eingebettet werden, muss jedoch nur temporär auf anderen Systemen installiert werden. Im Gegensatz zu Preview-&-Print-Schriften dürfen Dokumente, die Editable-Schriften enthalten, zum Lesen geöffnet werden, das Bearbeiten ist erlaubt und Änderungen können gespeichert werden.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Wenn dieses Bit gesetzt ist, darf die Schriftart vor dem Einbetten nicht unterteilt werden. Weitere Einbettungsbeschränkungen, die in den Bits 0-3 und 9 angegeben sind, gelten ebenfalls.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Wenn dieses Bit gesetzt ist, dürfen nur im Font enthaltene Bitmaps eingebettet werden. Konturdaten dürfen nicht eingebettet werden. Wenn im Font keine Bitmaps verfügbar sind, wird die Schriftart als nicht einbettbar betrachtet und die Einbettungsdienste schlagen fehl.