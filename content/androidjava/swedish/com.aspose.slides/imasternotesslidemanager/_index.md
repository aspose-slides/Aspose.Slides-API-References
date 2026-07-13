---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Hanterare för master-notssidor.
type: docs
url: /sv/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

Master notes slide manager.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | Returns a master for all notes slides of this presentation if there is one, otherwise returns null. |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | Sets defalut master notes slide for related notes slide. |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | Removes master notes slide. |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```

Returnerar en master för alla notssidor i denna presentation om en sådan finns, annars returneras null. Endast läsning [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide).

**Returnerar:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```

Ställer in standard-master-notssida för relaterad notssida.

**Returnerar:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - Standard-master-notssida [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```

Tar bort master-notssida.