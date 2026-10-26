---
title: ISequence class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.animation/isequence/
---
## ISequence κλάση

Αντιπροσωπεύει τη σειρά (συλλογή εφέ).

Ο τύπος ISequence εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`count`](/slides/python-net/el/aspose.slides.animation/isequence/count/) | Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία.<br/>            Μόνο ανάγνωση **int**. |
| [`trigger_shape`](/slides/python-net/el/aspose.slides.animation/isequence/trigger_shape/) | Επιστρέφει ή ορίζει τον στόχο σχήματος για την INTERACTIVE ακολουθία.<br/>            Εάν η ακολουθία δεν είναι αλληλεπιδραστική τότε επιστρέφει None.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |

Επιστρέφει ένα εφέ στον καθορισμένο δείκτη.

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.animation/isequence/__getitem__/) | Δείκτης |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Προσθέτει νέο εφέ στο τέλος της ακολουθίας. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Προσθέτει το νέο εφέ κίνησης διαγράμματος για κατηγορία ή σειρά στο τέλος της ακολουθίας. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Προσθέτει το νέο εφέ κίνησης διαγράμματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας. |
| [`remove(self, item)`](/slides/python-net/el/aspose.slides.animation/isequence/remove/#ieffect) | Αφαιρεί το καθορισμένο εφέ από μια συλλογή. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides.animation/isequence/remove_at/#int) | Αφαιρεί ένα εφέ από μια συλλογή. |
| [`clear(self)`](/slides/python-net/el/aspose.slides.animation/isequence/clear/#) | Αφαιρεί όλα τα εφέ από μια συλλογή. |
| [`remove_by_shape(self, shape)`](/slides/python-net/el/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Αφαιρεί εφέ για το καθορισμένο σχήμα. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/el/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Επιστρέφει έναν πίνακα εφέ για το καθορισμένο σχήμα. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/el/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Επιστρέφει έναν πίνακα εφέ για την καθορισμένη παράγραφο. |
| [`get_count(self, shape)`](/slides/python-net/el/aspose.slides.animation/isequence/get_count/#ishape) | Επιστρέφει τον αριθμό των εφέ για το καθορισμένο σχήμα. |

### Δείτε επίσης
* μονάδα [`aspose.slides.animation`](/slides/python-net/el/aspose.slides.animation)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)