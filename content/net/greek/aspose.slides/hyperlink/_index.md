---
title: Hyperlink
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά έναν υπερσύνδεσμο.
type: docs
weight: 5140
url: /el/aspose.slides/hyperlink/
---
## Κλάση Hyperlink

Αναπαριστά έναν υπερσύνδεσμο.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Creates an instance of a hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Επιστρέφει έναν υπερσύνδεσμο που τερματίζει την παρουσίαση. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο «αναπαραγωγή αρχείου πολυμέσων». Χρησιμοποιείται σε AudioFrame και VideoFrame. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Επιστρέφει έναν ειδικό υπερσύνδεσμο «μην κάνετε τίποτα». Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. Μόνο για ανάγνωση [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Επιστρέφει τον τύπο ενέργειας του Hyperlink. Μόνο για ανάγνωση [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την πρόσβαση στη βασική διεπαφή IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Αντιπροσωπεύει την πηγή του χρώματος του υπερσυνδέσμου – είτε στυλ είτε μορφή τμήματος. Αναγγραφή/εγγραφή [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Καθορίζει το εξωτερικό URL. Μόνο για ανάγνωση String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Αντιπροσωπεύει έναν υπερσύνδεσμο που ορίζεται για αυτό το τμήμα χωρίς να λαμβάνεται υπόψη το πραγματικό περιεχόμενο του τμήματος. Το PowerPoint συμπεριφέρεται ειδικά για συνδέσμους και το αντίστοιχο κείμενο σε ένα τμήμα. Επιτρέπει την δημιουργία κειμένου για τον υπερσύνδεσμο σε μορφή έγκυρου URL, διαφορετικού από τη πραγματική διεύθυνση του συνδέσμου. Σε αυτήν την περίπτωση, όταν προβάλετε το σύνδεσμο στο παράθυρο επεξεργασίας, θα αλλάξει ώστε να ταιριάζει με το κείμενο του τμήματος. Αυτή η ιδιότητα αντιπροσωπεύει την αρχική τιμή του υπερσυνδέσμου. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Καθορίζει αν ο υπερσύνδεσμος θα επισημαίνεται με κλικ. Αναγγραφή/εγγραφή Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Καθορίζει αν ο στόχος του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβεβλημένων υπερσυνδέσμων όταν κληθεί. Αναγγραφή/εγγραφή Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Αντιπροσωπεύει τον ήχο που παίζει του υπερσυνδέσμου. Αναγγραφή/εγγραφή [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Καθορίζει αν ο ήχος θα σταματήσει στο κλικ του υπερσυνδέσμου. Αναγγραφή/εγγραφή Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον στόχο του γονικού υπερσυνδέσμου όταν υπάρχει. Αναγγραφή/εγγραφή String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Αν ο Hyperlink απευθύνεται σε συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Μόνο για ανάγνωση [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συσχετισμένη με τον γονικό υπερσύνδεσμο. Αναγγραφή/εγγραφή String. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Καθορίζει αν οι δύο实例 Hyperlink είναι ίσες. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Καθορίζει αν οι δύο实例 Hyperlink είναι ίσες. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Εξυπηρετεί ως συνάρτηση hash για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Ελέγχει δύο υπερσυνδέσμους για ισότητα. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Ελέγχει δύο υπερσυνδέσμους για ανισότητα. |

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διεπαφή [IHyperlink](../ihyperlink)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->