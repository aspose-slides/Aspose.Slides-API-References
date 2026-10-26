---
title: Sequence class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.animation/sequence/
---
## Sequence κλάση

Αντιπροσωπεύει τη σειρά (συλλογή εφέ).

Ο τύπος Sequence εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`count`](/slides/python-net/el/aspose.slides.animation/sequence/count/) | Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία.<br/>            Μόνο για ανάγνωση **int**. |
| [`trigger_shape`](/slides/python-net/el/aspose.slides.animation/sequence/trigger_shape/) | Επιστρέφει ή ορίζει το στόχο σχήματος για την INTERACTIVE ακολουθία.<br/>            Αν η ακολουθία δεν είναι interactive τότε επιστρέφει None.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |

Επιστρέφει ένα εφέ στον καθορισμένο δείκτη.

## Δείκτης

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides.animation/sequence/__getitem__/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Προσθέτει νέο εφέ στο τέλος της ακολουθίας. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Προσθέτει το νέο εφέ κίνησης γραφήματος για την κατηγορία ή τη σειρά στο τέλος της ακολουθίας. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/el/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Προσθέτει το νέο εφέ κίνησης γραφήματος για στοιχεία στην κατηγορία ή τη σειρά στο τέλος της ακολουθίας. |
| [`remove(self, item)`](/slides/python-net/el/aspose.slides.animation/sequence/remove/#ieffect) | Αφαιρεί το καθορισμένο εφέ από μια συλλογή. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides.animation/sequence/remove_at/#int) | Αφαιρεί ένα εφέ από μια συλλογή. |
| [`clear(self)`](/slides/python-net/el/aspose.slides.animation/sequence/clear/#) | Αφαιρεί όλα τα εφέ από μια συλλογή. |
| [`remove_by_shape(self, shape)`](/slides/python-net/el/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Αφαιρεί το εφέ για το καθορισμένο σχήμα. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/el/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Επιστρέφει έναν πίνακα εφέ για το καθορισμένο σχήμα. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/el/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Επιστρέφει έναν πίνακα εφέ για την καθορισμένη παράγραφο. |
| [`get_count(self, shape)`](/slides/python-net/el/aspose.slides.animation/sequence/get_count/#ishape) | Επιστρέφει τον αριθμό εφέ για το καθορισμένο σχήμα. |


### Δείτε επίσης
* μονάδα [`aspose.slides.animation`](/slides/python-net/el/aspose.slides.animation)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)