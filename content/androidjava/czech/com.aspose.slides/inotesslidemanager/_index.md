---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Správce poznámkových snímků.
type: docs
url: /cs/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Správce poznámkových snímků.
## Metody

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Vrací poznámkový snímek pro aktuální snímek. |
| [addNotesSlide()](#addNotesSlide--) | Vrací poznámkový snímek pro aktuální snímek, vytvoří jej, pokud neexistuje. |
| [removeNotesSlide()](#removeNotesSlide--) | Odstraňuje poznámkový snímek aktuálního snímku. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Vrací poznámkový snímek pro aktuální snímek. Vrací null, pokud snímek nemá poznámkový snímek. Pouze pro čtení [INotesSlide](../../com.aspose.slides/inotesslide).

**Vrací:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Vrací poznámkový snímek pro aktuální snímek, vytvoří jej, pokud neexistuje.

**Vrací:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) pro tento snímek.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Odstraňuje poznámkový snímek aktuálního snímku.