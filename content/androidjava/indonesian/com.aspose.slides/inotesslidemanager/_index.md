---
title: INotesSlideManager
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Manajer slide catatan.
type: docs
url: /id/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Manajer slide catatan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini. |
| [addNotesSlide()](#addNotesSlide--) | Mengembalikan slide catatan untuk slide saat ini, membuat satu jika tidak ada. |
| [removeNotesSlide()](#removeNotesSlide--) | Menghapus slide catatan dari slide saat ini. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Mengembalikan slide catatan untuk slide saat ini. Mengembalikan null jika slide tidak memiliki slide catatan. Hanya-baca [INotesSlide](../../com.aspose.slides/inotesslide).

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Mengembalikan slide catatan untuk slide saat ini, membuat satu jika tidak ada.

**Mengembalikan:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) untuk slide ini.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Menghapus slide catatan dari slide saat ini.