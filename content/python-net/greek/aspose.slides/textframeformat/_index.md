---
title: TextFrameFormat class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/textframeformat/
---
## TextFrameFormat κλάση

Περιέχει τις ιδιότητες formatTextFrameFormatting του TextFrame.

**Κληρονομικότητα:**[`TextFrameFormat`](/slides/python-net/el/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)

Ο τύπος TextFrameFormat εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/textframeformat/__init__/#) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextFrameFormat`](/slides/python-net/el/aspose.slides/textframeformat). |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`three_d_format`](/slides/python-net/el/aspose.slides/textframeformat/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες του 3d εφέ για κείμενο.<br/>            Μόνο-ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/el/aspose.slides/textframeformat/margin_left/) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (σημεία) σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_right`](/slides/python-net/el/aspose.slides/textframeformat/margin_right/) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (σημεία) σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_top`](/slides/python-net/el/aspose.slides/textframeformat/margin_top/) | Επιστρέφει ή ορίζει το επάνω περιθώριο (σημεία) σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_bottom`](/slides/python-net/el/aspose.slides/textframeformat/margin_bottom/) | Επιστρέφει ή ορίζει το κάτω περιθώριο (σημεία) σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`wrap_text`](/slides/python-net/el/aspose.slides/textframeformat/wrap_text/) | **True** εάν το κείμενο αναδίπλωται στα περιθώρια του TextFrame.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/el/aspose.slides/textframeformat/anchoring_type/) | Επιστρέφει ή ορίζει το κάθετο άγκυρο κείμενο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή [`TextAnchorType`](/slides/python-net/el/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/el/aspose.slides/textframeformat/center_text/) | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο πλαίσιο.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/el/aspose.slides/textframeformat/text_vertical_type/) | Καθορίζει τον προσανατολισμό του κειμένου.<br/>            Η προκύπτουσα τιμή οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία<br/>            στην ιδιότητα RotationAngle.<br/>            Ανάγνωση/εγγραφή [`TextVerticalType`](/slides/python-net/el/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/el/aspose.slides/textframeformat/autofit_type/) | Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextAutofitType`](/slides/python-net/el/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/el/aspose.slides/textframeformat/column_count/) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου.<br/>            Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. <br/>            Η τιμή 0 σημαίνει ακαθόριστη τιμή.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`column_spacing`](/slides/python-net/el/aspose.slides/textframeformat/column_spacing/) | Επιστρέφει ή ορίζει το κενό μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό πρέπει να ισχύει μόνο <br/>            όταν υπάρχει περισσότερη από 1 στήλη.<br/>            Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. <br/>            Ανάγνωση/εγγραφή **float**. |
| [`rotation_angle`](/slides/python-net/el/aspose.slides/textframeformat/rotation_angle/) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. Εάν δεν<br/>            καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, τότε αυτή<br/>            εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει μια περιστροφή ενώ το κείμενο<br/>            μπορεί επίσης να έχει εφαρμοσμένη περιστροφή.<br/>            Η προκύπτουσα τιμή οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και το προεπιλεγμένο<br/>            κάθετο τύπο στην ιδιότητα TextVerticalType.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`transform`](/slides/python-net/el/aspose.slides/textframeformat/transform/) | Επιστρέφει ή ορίζει το σχήμα αναδίπλωσης κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextShapeType`](/slides/python-net/el/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/el/aspose.slides/textframeformat/keep_text_flat/) | Επιστρέφει ή ορίζει τη διατήρηση του κειμένου επίπεδου ακόμη και αν έχει εφαρμοστεί εφέ 3-D Περιστροφής.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`slide`](/slides/python-net/el/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/el/aspose.slides/textframeformat/text_style/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/el/aspose.slides/textframeformat/get_effective/#) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με εφαρμοσμένη κληρονομικότητα. |

### Δείτε επίσης
* κλάση [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)
* κλάση [`TextFrameFormat`](/slides/python-net/el/aspose.slides/textframeformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)