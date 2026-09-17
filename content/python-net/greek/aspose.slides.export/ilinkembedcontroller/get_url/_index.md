---
title: get_url method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Επιστρέφει μια διεύθυνση URL προς ένα εξωτερικό αντικείμενο.
Αυτή η μέθοδος πάντα καλείται εάν **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** επέστρεψε [`LinkEmbedDecision.LINK`](/slides/python-net/el/aspose.slides.export/linkembeddecision/LINK) και μπορεί να κληθεί εάν **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** επέστρεψε [`LinkEmbedDecision.EMBED`](/slides/python-net/el/aspose.slides.export/linkembeddecision/EMBED) αλλά η ενσωμάτωση είναι αδύνατη.
Μπορεί να κληθεί πολλές φορές για το ίδιο αναγνωριστικό αντικειμένου.

### Επιστρέφει

Διεύθυνση URL του εξωτερικού αντικειμένου ή None εάν αυτό το αντικείμενο πρέπει να αγνοηθεί.



```python
def get_url(self, id, referrer):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| id | **int** | Αναγνωριστικό αντικειμένου. Αυτό το αναγνωριστικό είναι μοναδικό σε όλη τη λειτουργία αποθήκευσης. |
| referrer | **int** | Αναγνωριστικό του αντικειμένου που αναφέρει ή 0, εάν το αντικείμενο αναφέρεται από το κύριο έγγραφο. Μπορεί να χρησιμοποιηθεί για τη δημιουργία σχετικού συνδέσμου. |



### Δείτε επίσης
* κλάση [`ILinkEmbedController`](/slides/python-net/el/aspose.slides.export/ilinkembedcontroller)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)