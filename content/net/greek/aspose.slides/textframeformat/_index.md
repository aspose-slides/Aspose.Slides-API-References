---
title: TextFrameFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Περιέχει τις ιδιότητες formatTextFrameFormatting των TextFrames.
type: docs
weight: 10960
url: /el/aspose.slides/textframeformat/
---
## TextFrameFormat κλάση

Περιέχει τις ιδιότητες formatTextFrameFormatting του TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`TextFrameFormat`](../textframeformat). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Επιστρέφει ή ορίζει το κείμενο κατακόρυφου άγκυρας σε ένα TextFrame. Ανάγνωση/εγγραφή [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την λήψη της βασικής διεπαφής IPresentationComponent. Μόνο ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. Ανάγνωση/εγγραφή [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Εάν NullableBool.True, τότε το κείμενο πρέπει να κεντράρει οριζόντια στο πλαίσιο. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Η τιμή 0 σημαίνει απροσδιόριστη τιμή. Ανάγνωση/εγγραφή Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Ανάγνωση/εγγραφή Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδο ακόμα και αν έχει εφαρμοστεί εφέ 3-Δ περιστροφής. Ανάγνωση/εγγραφή Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Επιστρέφει ή ορίζει το κάτω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξί περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Επιστρέφει ή ορίζει το άνω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο πλαίσιο. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, τότε εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει περιστροφή εκτός από την περιστροφή που εφαρμόζεται στο ίδιο το κείμενο. Η προκύπτουσα τιμή της οπτικής περιστροφής κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προρυθμισμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής κειμένου συνοψίζεται από αυτήν την ιδιότητα και το προσαρμοσμένο γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες εφέ 3Δ για ένα κείμενο. Μόνο ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. Ανάγνωση/εγγραφή [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με την εφαρμοσμένη κληρονομικότητα. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κώδικα hash. |

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διεπαφή [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* διεπαφή [ITextFrameFormat](../itextframeformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->