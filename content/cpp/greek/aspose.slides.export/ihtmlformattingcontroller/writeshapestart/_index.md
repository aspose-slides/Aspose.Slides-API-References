---
title: WriteShapeStart()
second_title: Αναφορά API Aspose.Slides για C++
description: Καλείται πριν από την απόδοση του shape. Καλείται μία φορά για κάθε shape. Εάν αυτή η λειτουργία γράψει κάτι στον generator, η δημιουργία της τρέχουσας εικόνας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο τμήμα HTML θα ενσωματωθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.
type: docs
weight: 53
url: /el/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) μέθοδος

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά ανά σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στον γεννήτορα, η δημιουργία της τρέχουσας εικόνας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο τμήμα html θα ενσωματωθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Αντικείμενο εξόδου. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) που πρόκειται να αποδοθεί. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHtmlGenerator](../../ihtmlgenerator/)
* Κλάση [IShape](../../../aspose.slides/ishape/)
* Κλάση [IHtmlFormattingController](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)