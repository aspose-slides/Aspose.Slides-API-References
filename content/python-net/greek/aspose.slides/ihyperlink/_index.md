---
title: IHyperlink class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ihyperlink/
---
## IHyperlink κλάση

Αντιπροσωπεύει έναν υπερσύνδεσμο.

Ο τύπος IHyperlink εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/el/aspose.slides/ihyperlink/action_type/) | Επιστρέφει τον τύπο της ενέργειας του HyperLinkEx.<br/>            Μόνο ανάγνωση [`HyperlinkActionType`](/slides/python-net/el/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/el/aspose.slides/ihyperlink/external_url/) | Καθορίζει το εξωτερικό URL<br/>            Εάν αυτή η ιδιότητα γίνει μη None, τότε η ιδιότητα TargetSlide γίνεται None.<br/>            Μόνο ανάγνωση **str**. |
| [`external_url_original`](/slides/python-net/el/aspose.slides/ihyperlink/external_url_original/) | Αντιπροσωπεύει έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος.<br/>            <br/>            Το PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή ενός έγκυρου URL, διαφορετικού από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το τμήμα κειμένου. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου. |
| [`target_slide`](/slides/python-net/el/aspose.slides/ihyperlink/target_slide/) | Εάν το HyperlinkEx στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια.<br/>            Εάν η ιδιότητα γίνει μη None, τότε η ιδιότητα ExternalUrl γίνεται None.<br/>            Μόνο ανάγνωση [`ISlide`](/slides/python-net/el/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/el/aspose.slides/ihyperlink/target_frame/) | Επιστρέφει το πλαίσιο μέσα στο γονικό σύνολο πλαισίων HTML για τον στόχο<br/>            του γονικού υπερσυνδέσμου όταν υπάρχει.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`tooltip`](/slides/python-net/el/aspose.slides/ihyperlink/tooltip/) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη<br/>            ως συσχετισμένη με το γονικό υπερσύνδεσμο.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`history`](/slides/python-net/el/aspose.slides/ihyperlink/history/) | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί<br/>            σε λίστα προβληθέντων υπερσυνδέσμων όταν κληθεί.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`highlight_click`](/slides/python-net/el/aspose.slides/ihyperlink/highlight_click/) | Καθορίζει εάν ο υπερσύνδεσμος θα επισημαίνεται κατά το κλικ.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`stop_sound_on_click`](/slides/python-net/el/aspose.slides/ihyperlink/stop_sound_on_click/) | Καθορίζει εάν ο ήχος θα διακοπεί κατά το κλικ στον υπερσύνδεσμο.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`sound`](/slides/python-net/el/aspose.slides/ihyperlink/sound/) | Αντιπροσωπεύει τον ήχο που παίζει του υπερσυνδέσμου.<br/>            Ανάγνωση/Εγγραφή [`IAudio`](/slides/python-net/el/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/el/aspose.slides/ihyperlink/color_source/) | Αντιπροσωπεύει την προέλευση του χρώματος του υπερσυνδέσμου - είτε στυλ είτε μορφή τμήματος.<br/>            Ανάγνωση/Εγγραφή [`HyperlinkColorSource`](/slides/python-net/el/aspose.slides/hyperlinkcolorsource). |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/el/aspose.slides/ihyperlink/equals/#ihyperlink) | Καθορίζει εάν οι δύο παρουσίες Hyperlink είναι ίσες. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)