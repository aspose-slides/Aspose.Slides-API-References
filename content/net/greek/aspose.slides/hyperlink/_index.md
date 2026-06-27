---
title: Hyperlink
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά έναν υπερσύνδεσμο.
type: docs
weight: 5100
url: /el/aspose.slides/hyperlink/
---
## Hyperlink κλάση

Αναπαριστά έναν υπερσύνδεσμο.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου που δείχνει σε συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να εκχωρηθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, διαφορετικά ο σύνδεσμος θα αποθηκευτεί ως NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Δημιουργεί ένα στιγμιότυπο υπερσύνδεσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, παρακάμπτοντας τις δευτερεύουσες ιδιότητες. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβεβλημένη διαφάνεια. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο "play mediafile". Χρησιμοποιείται σε AudioFrame και VideoFrame. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο "do nothing". Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. Μόνο ανάγωση [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Επιστρέφει τον τύπο της ενέργειας του Hyperlink. Μόνο ανάγωση [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει τη λήψη της βασικής διεπαφής IPresentationComponent. Μόνο ανάγωση [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Αναπαριστά την πηγή του χρώματος του υπερσύνδεσμου - είτε στυλ είτε μορφή τμήματος. Ανάγωση/εγγραφή [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Καθορίζει το εξωτερικό URL. Μόνο ανάγωση String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Αναπαριστά έναν υπερσύνδεσμο που έχει οριστεί για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος. Το PowerPoint συμπεριφέεται ειδικά για συνδέσμους και το αντίστοιχο κείμενο σε ένα τμήμα. Επιτρέπει τη δημιουργία κειμένου για τον υπερσύνδεσμο με τη μορφή ενός έγκυρου URL, διαφορετικού από την πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το τμήμα κειμένου. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσύνδεσμου. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Καθορίζει αν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. Ανάγωση/εγγραφή Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Καθορίζει αν ο στόχος του γονικού υπερσύνδεσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν ενεργοποιηθεί. Ανάγωση/εγγραφή Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Αναπαριστά τον ήχο αναπαραγωγής του υπερσύνδεσμου. Ανάγωση/εγγραφή [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Καθορίζει αν ο ήχος πρέπει να σταματήσει με κλικ στον υπερσύνδεσμο. Ανάγωση/εγγραφή Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Επιστρέφει το πλαίσιο μέσα στη γονική HTML συλλογή πλαισίων για τον στόχο του γονικού υπερσύνδεσμου όταν υπάρχει. Ανάγτηση/εγγραφή String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Αν ο Hyperlink στοχεύει συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Μόνο ανάγωση [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συνδεδεμένη με το γονικό υπερσύνδεσμο. Ανάγωση/εγγραφή String. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Καθορίζει αν οι δύο στιγμιότυπα Hyperlink είναι ίσα. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Καθορίζει αν οι δύο στιγμιότυπα Hyperlink είναι ίσα. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Δοκιμάζει δύο υπερσυνδέσμους για ισότητα. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Δοκιμάζει δύο υπερσυνδέσμους για ανισότητα. |

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διεπαφή [IHyperlink](../ihyperlink)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* σύγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->