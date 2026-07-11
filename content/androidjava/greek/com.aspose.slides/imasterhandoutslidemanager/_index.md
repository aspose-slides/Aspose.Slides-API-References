---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Master handout slide manager.
type: docs
url: /el/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

Διαχειριστής κύριας διαφάνειας σημειώσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | Returns a master for all notes slides of this presentation if there is one, otherwise returns null. |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | Sets default master handout slide to related handout slide. |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | Removes master handout slide. |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

Επιστρέφει ένα master για όλες τις διαφάνειες σημειώσεων αυτής της παρουσίασης αν υπάρχει, διαφορετικά επιστρέφει null. Μόνο ανάγνωση [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

**Επιστρέφει:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

Ορίζει την προεπιλεγμένη κύρια διαφάνεια χειρογράφου στην σχετική διαφάνεια χειρογράφου.

**Επιστρέφει:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - Master handout slide [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

Αφαιρεί τη κύρια διαφάνεια χειρογράφου.