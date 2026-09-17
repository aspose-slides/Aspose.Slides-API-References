---
title: ILinkEmbedController class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController κλάση

Διεπαφή callback που χρησιμοποιείται για να καθορίσει πώς πρέπει να επεξεργαστεί το αντικείμενο κατά την αποθήκευση.

Ο τύπος ILinkEmbedController εκθέτει τα παρακάτω μέλη:

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/el/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο.<br/>            Αυτή η μέθοδος καλείται μία φορά για κάθε id αντικειμένου.<br/>            Δεν είναι εγγυημένο ότι δεν θα υπάρξουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά με διαφορετικό id. |
| [`get_url(self, id, referrer)`](/slides/python-net/el/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Επιστρέφει ένα URL σε ένα εξωτερικό αντικείμενο.<br/>            Αυτή η μέθοδος καλείται πάντα εάν **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** επέστρεψε [`LinkEmbedDecision.LINK`](/slides/python-net/el/aspose.slides.export/linkembeddecision/LINK) και μπορεί να κληθεί εάν **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** επέστρεψε [`LinkEmbedDecision.EMBED`](/slides/python-net/el/aspose.slides.export/linkembeddecision/EMBED) αλλά η ενσωμάτωση είναι αδύναμη.<br/>            Μπορεί να κληθεί πολλές φορές για το ίδιο id αντικειμένου. |
| [`save_external(self, id, entity_data)`](/slides/python-net/el/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Αποθηκεύει εξωτερικό αντικείμενο. |

### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)