---
title: ITextFrameFormat class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/itextframeformat/
---
## ITextFrameFormat κλάση

Περιέχει τις ιδιότητες μορφοποίησης του TextFrame.

Ο τύπος ITextFrameFormat εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`text_style`](/slides/python-net/el/aspose.slides/itextframeformat/text_style/) | Επιστρέφει το στυλ του κειμένου.<br/>            Μόνο για ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/el/aspose.slides/itextframeformat/margin_left/) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`margin_right`](/slides/python-net/el/aspose.slides/itextframeformat/margin_right/) | Επιστρέφει ή ορίζει το δεξί περιθώριο (points) σε ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`margin_top`](/slides/python-net/el/aspose.slides/itextframeformat/margin_top/) | Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`margin_bottom`](/slides/python-net/el/aspose.slides/itextframeformat/margin_bottom/) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`wrap_text`](/slides/python-net/el/aspose.slides/itextframeformat/wrap_text/) | **True**  εάν το κείμενο περιτυλίγεται στα περιθώρια του TextFrame.<br/>            Ανάγνωση/Εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/el/aspose.slides/itextframeformat/anchoring_type/) | Επιστρέφει ή ορίζει το κατακόρυφο άγκυρο κειμένου σε ένα TextFrame.<br/>            Ανάγνωση/Εγγραφή [`TextAnchorType`](/slides/python-net/el/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/el/aspose.slides/itextframeformat/center_text/) | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο.<br/>            Ανάγνωση/Εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/el/aspose.slides/itextframeformat/text_vertical_type/) | Καθορίζει τον προσανατολισμό του κειμένου.<br/>            Η τελική τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία<br/>            στην ιδιότητα RotationAngle.<br/>            Ανάγνωση/Εγγραφή [`TextVerticalType`](/slides/python-net/el/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/el/aspose.slides/itextframeformat/autofit_type/) | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου.<br/>            Ανάγνωση/Εγγραφή [`TextAutofitType`](/slides/python-net/el/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/el/aspose.slides/itextframeformat/column_count/) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου.<br/>            Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν.<br/>            Η τιμή 0 σημαίνει αόριστη τιμή.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`column_spacing`](/slides/python-net/el/aspose.slides/itextframeformat/column_spacing/) | Επιστρέφει ή ορίζει το κενό μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). Αυτό εφαρμόζεται μόνο<br/>            όταν υπάρχει περισσότερη από 1 στήλη.<br/>            Η τιμή αυτή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`three_d_format`](/slides/python-net/el/aspose.slides/itextframeformat/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες του 3D εφέ για κείμενο.<br/>            Μόνο για ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/el/aspose.slides/itextframeformat/keep_text_flat/) | Επιστρέφει ή ορίζει την εξαίρεση του κειμένου από τη 3D σκηνή εντελώς.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`rotation_angle`](/slides/python-net/el/aspose.slides/itextframeformat/rotation_angle/) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο πλαίσιο. Εάν δεν<br/>            καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, τότε αυτή εφαρμόζεται<br/>            ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου.<br/>            Η τελική τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προ-ορισμένο<br/>            κάθετο τύπο στην ιδιότητα TextVerticalType.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`transform`](/slides/python-net/el/aspose.slides/itextframeformat/transform/) | Λαμβάνει ή ορίζει το σχήμα περιτύλιξης κειμένου.<br/>            Ανάγνωση/Εγγραφή [`TextShapeType`](/slides/python-net/el/aspose.slides/textshapetype). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/el/aspose.slides/itextframeformat/get_effective/#) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με την κληρονόμηση εφαρμοσμένη. |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)