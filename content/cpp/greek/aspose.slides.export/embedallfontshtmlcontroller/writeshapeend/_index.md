---
title: WriteShapeEnd()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει οτιδήποτε στον δημιουργό, η δημιουργία της τρέχουσας εικόνας διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα ενσωματωθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.
type: docs
weight: 79
url: /el/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει οτιδήποτε στον δημιουργό, η δημιουργία της τρέχουσας εικόνας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο τμήμα html θα ενταχθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Αντικείμενο εξόδου. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) που αποδίδεται τελευταίο. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IHtmlGenerator](../../ihtmlgenerator/)
* Κλάση [IShape](../../../aspose.slides/ishape/)
* Κλάση [EmbedAllFontsHtmlController](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)