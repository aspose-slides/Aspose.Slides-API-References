---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Java API Reference
description: Master handout slide manager.
type: docs
url: /tr/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

Ana not dağıtım slaytı yöneticisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Returns a master for all notes slides of this presentation if there is one, otherwise returns null. |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | Sets default master handout slide to related handout slide. |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | Removes master handout slide. |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

Bu sunumdaki tüm not slaytları için bir ana slayt döndürür; eğer varsa, aksi takdirde null döndürür. Yalnızca okunabilir [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

**Döndürür:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

İlgili not dağıtım slaytına varsayılan ana not dağıtım slaytını ayarlar.

**Döndürür:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - Master handout slide [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

Ana not dağıtım slaytını kaldırır.