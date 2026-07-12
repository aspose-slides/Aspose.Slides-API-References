---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Referansı
description: Not slaytı yöneticisi.
type: docs
url: /tr/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Not slaytı yöneticisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Geçerli slayt için not slaytını döndürür. Slaytın not slaytı yoksa null döndürür. Yalnızca okuma [INotesSlide](../../com.aspose.slides/inotesslide).

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Geçerli slayt için not slaytını döndürür, yoksa oluşturur.

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) bu slayt için.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Geçerli slaytın not slaytını kaldırır.