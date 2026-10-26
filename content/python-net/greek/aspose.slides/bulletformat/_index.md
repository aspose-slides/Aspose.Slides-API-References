---
title: BulletFormat class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/bulletformat/
---
## BulletFormat κλάση

Αντιπροσωπεύει τις ιδιότητες μορφοποίησης σφαίρας παραγράφου.

**Κληρονομικότητα:**[`BulletFormat`](/slides/python-net/el/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)

Ο τύπος BulletFormat εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`type`](/slides/python-net/el/aspose.slides/bulletformat/type/) | Επιστρέφει ή ορίζει τον τύπο σφαίρας μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`BulletType`](/slides/python-net/el/aspose.slides/bullettype). |
| [`char`](/slides/python-net/el/aspose.slides/bulletformat/char/) | Επιστρέφει ή ορίζει το χαρακτήρα σφαίρας μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή **System.Char**. |
| [`font`](/slides/python-net/el/aspose.slides/bulletformat/font/) | Επιστρέφει ή ορίζει τη γραμματοσειρά σφαίρας μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`IFontData`](/slides/python-net/el/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/el/aspose.slides/bulletformat/height/) | Επιστρέφει ή ορίζει το ύψος σφαίρας μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Η τιμή float.NaN καθορίζει ότι η σφαίρα κληρονομεί ύψος από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`color`](/slides/python-net/el/aspose.slides/bulletformat/color/) | Επιστρέφει τη μορφή χρώματος μιας σφαίρας μιας παραγράφου χωρίς κληρονομικότητα.<br/>            Μόνο ανάγνωση [`IColorFormat`](/slides/python-net/el/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/el/aspose.slides/bulletformat/numbered_bullet_start_with/) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για την ομάδα αριθμημένων σφαίρων χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`numbered_bullet_style`](/slides/python-net/el/aspose.slides/bulletformat/numbered_bullet_style/) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης σφαίρας χωρίς κληρονομικότητα.<br/>            Ανάγνωση/εγγραφή [`NumberedBulletStyle`](/slides/python-net/el/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/el/aspose.slides/bulletformat/is_bullet_hard_color/) | Καθορίζει εάν η σφαίρα έχει δικό της χρώμα ή κληρονομεί το χρώμα από το πρώτο τμήμα στην παράγραφο.<br/>            **NullableBool.True**  αν η σφαίρα έχει δικό της χρώμα και **NullableBool.False**  αν η σφαίρα<br/>            κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/el/aspose.slides/bulletformat/is_bullet_hard_font/) | Καθορίζει εάν η σφαίρα έχει δική της γραμματοσειρά ή κληρονομεί τη γραμματοσειρά από το πρώτο τμήμα στην παράγραφο.<br/>            **NullableBool.True**  αν η σφαίρα έχει δική της γραμματοσειρά και **NullableBool.False**  αν η σφαίρα<br/>            κληρονομεί γραμματοσειρά από το πρώτο τμήμα στην παράγραφο.<br/>            Ανάγνωση/εγγραφή [`NullableBool`](/slides/python-net/el/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/el/aspose.slides/bulletformat/picture/) | Επιστρέφει την εικόνα που χρησιμοποιείται ως σφαίρα σε μια παράγραφο χωρίς κληρονομικότητα.<br/>            Μόνο ανάγνωση [`ISlidesPicture`](/slides/python-net/el/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/el/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/bulletformat/presentation/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/el/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Ορίζει τις προεπιλεγμένες μη-μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν οι σφαίρες είναι ενεργοποιημένες (όπως κάνει το PowerPoint εάν ενεργοποιηθεί η σφαίρα/αρίθμηση παραγράφου). Εάν οι σφαίρες είναι απενεργοποιημένες, επαναφέρει μόνο το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint εάν απενεργοποιηθεί η σφαίρα/αρίθμηση παραγράφου). Οι μετατοπίσεις εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο σφαίρας - IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη-μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (για να γίνουν οι τιμές τοπικές). |
| [`get_effective(self)`](/slides/python-net/el/aspose.slides/bulletformat/get_effective/#) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης σφαίρας με την εφαρμοσμένη κληρονομικότητα. |

### Δείτε επίσης
* κλάση [`BulletFormat`](/slides/python-net/el/aspose.slides/bulletformat)
* κλάση [`PVIObject`](/slides/python-net/el/aspose.slides/pviobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)