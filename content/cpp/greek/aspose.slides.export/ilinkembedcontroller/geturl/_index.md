---
title: GetUrl()
second_title: Αναφορά API Aspose.Slides για C++
description: "Επιστρέφει ένα URL σε ένα εξωτερικό αντικείμενο. Αυτή η μέθοδος καλείται πάντα εάν ILinkEmbedController::GetObjectStoringLocation επέστρεψε LinkEmbedDecision::Link και μπορεί να κληθεί εάν ILinkEmbedController::GetObjectStoringLocation επέστρεψε LinkEmbedDecision::Embed, αλλά η ενσωμάτωση είναι αδύνατη. Μπορεί να κληθεί πολλές φορές για το ίδιο αναγνωριστικό αντικειμένου."
type: docs
weight: 14
url: /el/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) μέθοδος

Επιστρέφει ένα URL σε ένα εξωτερικό αντικείμενο. Αυτή η μέθοδος καλείται πάντα εάν [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) επέστρεψε [LinkEmbedDecision::Link](../../linkembeddecision/) και μπορεί να κληθεί εάν [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) επέστρεψε [LinkEmbedDecision::Embed](../../linkembeddecision/) αλλά η ενσωμάτωση είναι αδύνατη. Μπορεί να κληθεί πολλές φορές για το ίδιο αναγνωριστικό αντικειμένου.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | **int32_t** | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό σε όλη τη λειτουργία αποθήκευσης. |
| referrer | **int32_t** | Αναγνωριστικό του αντικειμένου που κάνει παραπομπή ή 0, εάν το αντικείμενο παραπέμπεται από το ριζικό έγγραφο. Μπορεί να χρησιμοποιηθεί για τη δημιουργία σχετικού συνδέσμου. |

### Τιμή Επιστροφής

Διεύθυνση URL εξωτερικού αντικειμένου ή null εάν αυτό το αντικείμενο πρέπει να αγνοηθεί.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ILinkEmbedController](../)
* Ονομαχώρος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)