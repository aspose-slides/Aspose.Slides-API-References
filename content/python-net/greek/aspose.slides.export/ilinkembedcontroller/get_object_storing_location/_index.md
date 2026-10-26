---
title: get_object_storing_location method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο.
            Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου.
            Δεν είναι εγγυημένο ότι δεν θα υπάρξουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά με διαφορετικό αναγνωριστικό.

### Επιστρέφει

Απόφαση



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **int** | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό σε όλη τη λειτουργία αποθήκευσης. |
| entity_data | **bytes** | Δυαδικά δεδομένα αντικειμένου. Αυτό το παράμετρος μπορεί να είναι None, εάν τα δυαδικά δεδομένα του αντικειμένου δεν έχουν δημιουργηθεί ακόμη. |
| semantic_name | **str** | Κάποιο σύντομο κείμενο που περιγράφει το νόημα του αντικειμένου. Ο ελεγκτής μπορεί να το χρησιμοποιήσει ως μέρος του εξωτερικού ονόματος του αντικειμένου, αλλά εξαρτάται από τον διαχειριστή να εξασφαλίσει ότι τα ονόματα θα είναι μοναδικά και θα περιέχουν μόνο τους επιτρεπόμενους χαρακτήρες. |
| content_type | **str** | Τύπος MIME του αντικειμένου. |
| recomended_extension | **str** | Επέκταση ονόματος αρχείου, συνιστώμενη για αυτόν τον τύπο MIME. |



### Δείτε επίσης
* κλάση [`ILinkEmbedController`](/slides/python-net/el/aspose.slides.export/ilinkembedcontroller)
* απαρίθμηση [`LinkEmbedDecision`](/slides/python-net/el/aspose.slides.export/linkembeddecision)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)