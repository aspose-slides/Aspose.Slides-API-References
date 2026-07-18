---
title: WriteShapeEnd()
second_title: Aspose.Slides για C++ αναφορά API
description: Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στον generator, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, θα προστεθεί το απόσπασμα HTML και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.
type: docs
weight: 66
url: /el/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) μέθοδος


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει οτιδήποτε στον generator, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, θα εισαχθεί το προστιθέμενο απόσπασμα HTML και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Αντικείμενο εξόδου. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) που αποδίδεται τελευταίο. |

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHtmlGenerator](../../ihtmlgenerator/)
* Κλάση [IShape](../../../aspose.slides/ishape/)
* Κλάση [IHtmlFormattingController](../)
* Χώρος ονόματος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)