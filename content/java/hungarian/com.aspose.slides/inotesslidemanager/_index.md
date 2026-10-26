---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
url: /hu/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Jegyzet diakezelő.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Visszaadja a jelenlegi dia jegyzet diaját. |
| [addNotesSlide()](#addNotesSlide--) | Visszaadja a jelenlegi dia jegyzet diaját, és létrehozza, ha nem létezik. |
| [removeNotesSlide()](#removeNotesSlide--) | Eltávolítja az aktuális dia jegyzet diaját. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Visszaadja a jelenlegi dia jegyzet diaját. Null értéket ad vissza, ha a diához nincs jegyzet dia. Csak olvasható [INotesSlide](../../com.aspose.slides/inotesslide).

**Visszatér:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Visszaadja a jelenlegi dia jegyzet diaját, és létrehozza, ha nem létezik.

**Visszatér:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) ehhez a diához.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Eltávolítja az aktuális dia jegyzet diaját.