---
title: Hyperlink
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει έναν υπερσύνδεσμο.
type: docs
weight: 5120
url: /el/aspose.slides/hyperlink/
---
## Hyperlink κλάση

Αντιπροσωπεύει έναν υπερσύνδεσμο.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Δημιουργεί ένα στιγμιότυπο ενός υπερσυνδέσμου που οδηγεί σε συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να αντιστοιχιστεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, διαφορετικά ο σύνδεσμος θα αποθηκευτεί ως NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Δημιουργεί ένα στιγμιότυπο ενός υπερσυνδέσμου. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Δημιουργεί ένα στιγμιότυπο ενός υπερσυνδέσμου χρησιμοποιώντας άλλο υπερσύνδεσμο ως πηγή, παρακάμπτοντας τις δευτερεύουσες ιδιότητες. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβεβλημένη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο "play mediafile". Χρησιμοποιείται στα AudioFrame και VideoFrame. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο "do nothing". Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Επιστρέφει τον τύπο της δράσης του Hyperlink. Μόνο για ανάγνωση [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την ανάκτηση της βασικής διασύνδεσης IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Αντιπροσωπεύει την πηγή του χρώματος του υπερσυνδέσμου - είτε στυλ είτε μορφή τμήματος. Ανάγνωση/εγγραφή [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Καθορίζει το εξωτερικό URL. Μόνο για ανάγνωση String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Αντιπροσωπεύει έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος.  Το PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενό τους σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή έγκυρης URL, διαφορετική από την πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει για να ταιριάζει με το τμήμα κειμένου. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Καθορίζει εάν ο υπερσύνδεσμος θα επισημαίνεται κατά το κλικ. Ανάγνωση/εγγραφή Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Καθορίζει εάν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγνωση/εγγραφή Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Αντιπροσωπεύει τον ήχο αναπαραγωγής του υπερσυνδέσμου. Ανάγνωση/εγγραφή [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Καθορίζει εάν ο ήχος θα σταματήσει με το κλικ στον υπερσύνδεσμο. Ανάγνωση/εγγραφή Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. Ανάγνωση/εγγραφή String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Εάν ο Hyperlink στοχεύει συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Μόνο για ανάγνωση [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. Ανάγνωση/εγγραφή String. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Καθορίζει εάν οι δύο παρουσίες του Hyperlink είναι ίσες. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Καθορίζει εάν οι δύο παρουσίες του Hyperlink είναι ίσες. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Δοκιμάζει δύο υπερσυνδέσμους για ισότητα. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Δοκιμάζει δύο υπερσυνδέσμους για ανισότητα. |

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διασύνδεση [IHyperlink](../ihyperlink)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* σύγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->