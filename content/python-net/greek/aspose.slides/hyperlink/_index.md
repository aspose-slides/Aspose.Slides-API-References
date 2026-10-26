---
title: Hyperlink class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/hyperlink/
---
## Hyperlink κλάση

Αντιπροσωπεύει έναν υπερσύνδεσμο.

**Inheritance:**[`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)

Ο τύπος Hyperlink εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/el/aspose.slides/hyperlink/__init__/#str) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου. |
| [`__init__(self, slide)`](/slides/python-net/el/aspose.slides/hyperlink/__init__/#islide) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου που δείχνει σε συγκεκριμένη διαφάνεια.<br/>            Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να ανατεθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, διαφορετικά ο σύνδεσμος θα αποθηκευτεί ως NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/el/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, υπερισχύοντας των δευτερινών ιδιοτήτων. |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`no_action`](/slides/python-net/el/aspose.slides/hyperlink/no_action/) | Επιστρέφει έναν ειδικό "do nothing" υπερσύνδεσμο.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/el/aspose.slides/hyperlink/media/) | Επιστρέφει έναν ειδικό "play mediafile" υπερσύνδεσμο. Χρησιμοποιείται στα AudioFrame και VideoFrame.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/el/aspose.slides/hyperlink/next_slide/) | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/el/aspose.slides/hyperlink/previous_slide/) | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/el/aspose.slides/hyperlink/first_slide/) | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/el/aspose.slides/hyperlink/last_slide/) | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/el/aspose.slides/hyperlink/last_vieved_slide/) | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/el/aspose.slides/hyperlink/end_show/) | Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση.<br/>            Μόνο για ανάγνωση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/el/aspose.slides/hyperlink/action_type/) | Επιστρέφει τον τύπο της ενέργειας του Hyperlink.<br/>            Μόνο για ανάγνωση [`HyperlinkActionType`](/slides/python-net/el/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/el/aspose.slides/hyperlink/external_url/) | Καθορίζει τη εξωτερική διεύθυνση URL.<br/>            Μόνο για ανάγνωση **str**. |
| [`target_slide`](/slides/python-net/el/aspose.slides/hyperlink/target_slide/) | Αν ο Hyperlink στοχεύει σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια.<br/>            Μόνο για ανάγνωση [`ISlide`](/slides/python-net/el/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/el/aspose.slides/hyperlink/external_url_original/) | Αντιπροσωπεύει έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος.<br/>            <br/>            Το PowerPoint συμπεριφέρεται συγκεκριμένα για τους συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή έγκυρης URL, διαφορετική από την πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλετε τον σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το κειμενικό τμήμα. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου. |
| [`target_frame`](/slides/python-net/el/aspose.slides/hyperlink/target_frame/) | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον προορισμό του γονικού υπερσυνδέσμου όταν υπάρχει.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`tooltip`](/slides/python-net/el/aspose.slides/hyperlink/tooltip/) | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`history`](/slides/python-net/el/aspose.slides/hyperlink/history/) | Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβλεπόμενων υπερσυνδέσμων όταν κληθεί.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`highlight_click`](/slides/python-net/el/aspose.slides/hyperlink/highlight_click/) | Καθορίζει εάν ο υπερσύνδεσμος θα επισημαίνεται όταν γίνει κλικ.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`stop_sound_on_click`](/slides/python-net/el/aspose.slides/hyperlink/stop_sound_on_click/) | Καθορίζει εάν ο ήχος θα σταματήσει όταν γίνει κλικ στον υπερσύνδεσμο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`sound`](/slides/python-net/el/aspose.slides/hyperlink/sound/) | Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου.<br/>            Ανάγνωση/εγγραφή [`IAudio`](/slides/python-net/el/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/el/aspose.slides/hyperlink/color_source/) | Αντιπροσωπεύει την πηγή του χρώματος του υπερσυνδέσμου - είτε στυλ είτε μορφή τμήματος.<br/>            Ανάγνωση/εγγραφή [`HyperlinkColorSource`](/slides/python-net/el/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/el/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/hyperlink/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/el/aspose.slides/hyperlink/equals/#ihyperlink) | Καθορίζει εάν τα δύο στιγμιότυπα Hyperlink είναι ίσα. |

### Δείτε επίσης
* κλάση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink)
* κλάση [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)