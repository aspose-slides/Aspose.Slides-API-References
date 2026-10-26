---
title: GetObjectStoringLocation()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου. Δεν υπάρχει εγγύηση ότι δεν θα υπάρξουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά με διαφορετικό αναγνωριστικό.
type: docs
weight: 1
url: /el/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) method


Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου. Δεν υπάρχει εγγύηση ότι δεν θα υπάρξουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά με διαφορετικό αναγνωριστικό.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό σε όλη τη λειτουργία αποθήκευσης. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Δυαδικά δεδομένα του αντικειμένου. Αυτή η παράμετρος μπορεί να είναι null, αν τα δυαδικά δεδομένα του αντικειμένου δεν έχουν δημιουργηθεί ακόμη. |
| semanticName | [System::String](../../../system/string/) | Κάποιο σύντομο κείμενο που περιγράφει το νόημα του αντικειμένου. Ο ελεγκτής μπορεί να το χρησιμοποιήσει ως μέρος του εξωτερικού ονόματος του αντικειμένου, αλλά είναι στην ευθύνη του διαχειριστή να διασφαλίσει ότι τα ονόματα θα είναι μοναδικά και θα περιέχουν μόνο επιτρεπόμενους χαρακτήρες. |
| contentType | [System::String](../../../system/string/) | Τύπος MIME του αντικειμένου. |
| recomendedExtension | [System::String](../../../system/string/) | Επέκταση ονόματος αρχείου, προτεινόμενη για αυτόν τον τύπο MIME. |

### Τιμή επιστροφής

Απόφαση

## Δείτε επίσης

* Απαρίθμηση [LinkEmbedDecision](../../linkembeddecision/)
* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ILinkEmbedController](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)