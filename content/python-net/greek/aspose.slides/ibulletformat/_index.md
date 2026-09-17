---
title: IBulletFormat class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ibulletformat/
---
## IBulletFormat κλάση

Αντιπροσωπεί τις ιδιότητες μορφοποίησης στίγματος παραγράφου.

Ο τύπος IBulletFormat αποκαλύπτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides/ibulletformat/type/) | Επιστρέφει ή ορίζει τον τύπο του στίγματος μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`BulletType`](/slides/python-net/el/aspose.slides/bullettype). |
| [`char`](/slides/python-net/el/aspose.slides/ibulletformat/char/) | Επιστρέφει ή ορίζει το χαρακτήρα στίγματος μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή **System.Char**. |
| [`font`](/slides/python-net/el/aspose.slides/ibulletformat/font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά στίγματος μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`IFontData`](/slides/python-net/el/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/el/aspose.slides/ibulletformat/height/) | Επιστρέφει ή ορίζει το ύψος του στίγματος μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Η τιμή float.NaN καθορίζει ότι το στίγμα κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`color`](/slides/python-net/el/aspose.slides/ibulletformat/color/) | Επιστρέφει τη μορφή χρώματος ενός στίγματος μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Μόνο-ανάγνωση [`IColorFormat`](/slides/python-net/el/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/el/aspose.slides/ibulletformat/picture/) | Επιστρέφει την εικόνα που χρησιμοποιείται ως στίγμα σε μια παράγραφο χωρίς κληρονομικότητα.<br/>            Μόνο-ανάγνωση [`ISlidesPicture`](/slides/python-net/el/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/el/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων στίγματος χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`numbered_bullet_style`](/slides/python-net/el/aspose.slides/ibulletformat/numbered_bullet_style/) | Επιστρέφει ή ορίζει το στυλ ενός αριθμημένου στίγματος χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`IBulletFormat.numbered_bullet_style`](/slides/python-net/el/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/el/aspose.slides/ibulletformat/is_bullet_hard_color/) | Καθορίζει αν το στίγμα έχει δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο.<br/>            **NullableBool.True**  αν το στίγμα έχει δικό του χρώμα και **NullableBool.False**  αν το στίγμα<br/>            κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/el/aspose.slides/ibulletformat/is_bullet_hard_font/) | Καθορίζει αν το στίγμα έχει δική του γραμματοσειρά ή την κληρονομεί από το πρώτο τμήμα στην παράγραφο.<br/>            **NullableBool.True**  αν το στίγμα έχει δική του γραμματοσειρά και **NullableBool.False**  αν το στίγμα<br/>            κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/el/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Ορίζει τις προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν τα στίγματα είναι ενεργοποιημένα (όπως κάνει το PowerPoint όταν ενεργοποιεί στίγματα/αρίθμηση παραγράφων). Αν τα στίγματα είναι απενεργοποιημένα, επαναφέρει απλώς το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint όταν απενεργοποιεί στίγματα/αρίθμηση παραγράφων). Οι μετατοπίσεις εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο στίγματος - IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (κοιτώντας τις τιμές ως τοπικές τιμές). |
| [`get_effective(self)`](/slides/python-net/el/aspose.slides/ibulletformat/get_effective/#) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης στίγματος με την εφαρμοσμένη κληρονομικότητα. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)