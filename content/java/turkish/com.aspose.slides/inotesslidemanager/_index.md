---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
url: /tr/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Not slaytı yöneticisi.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Geçerli slayt için not slaytını döndürür. |
| [addNotesSlide()](#addNotesSlide--) | Geçerli slayt için not slaytını döndürür, mevcut değilse oluşturur. |
| [removeNotesSlide()](#removeNotesSlide--) | Geçerli slaytın not slaytını kaldırır. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Geçerli slayt için not slaytını döndürür. Slaytta not slaytı yoksa null döndürür. Salt okunur [INotesSlide](../../com.aspose.slides/inotesslide).

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Geçerli slayt için not slaytını döndürür, mevcut değilse oluşturur.

**Döndürür:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) bu slayt için.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Geçerli slaytın not slaytını kaldırır.