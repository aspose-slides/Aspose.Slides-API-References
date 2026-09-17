---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection κλάση

Αντιπροσωπεύει μια συλλογή όλων των διαφανειών διάταξης του ορισμένου κύριου διαφάνειας.
            Επεκτείνει την κλάση LayoutSlideCollection με μεθόδους για προσθήκη/εισαγωγή/αφαίρεση/κλωνοποίηση/αναδιάταξη
            διαφανειών διάταξης στο πλαίσιο των μεμονωμένων συλλογών των διαφανειών διάταξης του κύριου.

**Κληρονομικότητα:**[`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/el/aspose.slides/layoutslidecollection)

The MasterLayoutSlideCollection type exposes the following members:

## Δεικτής

| Όνομα | Περιγραφή |
| :- | :- |
| [`[index]`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Επιστρέφει την πρώτη διαφάνεια διάταξης του συγκεκριμένου τύπου.<br/>            Ένας τύπος διαφάνειας διάταξης για εύρεση.[`LayoutSlide`](/slides/python-net/el/aspose.slides/layoutslide) με συγκεκριμένο τύπο ή None εάν δεν βρεθούν διαφάνειες. |
| [`remove(self, value)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Αφαιρεί μια διαφάνεια διάταξης από τη συλλογή. |
| [`remove_unused(self)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης (layout slides των οποίων το HasDependingSlides είναι false). |
| [`add_clone(self, source_layout)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στο τέλος της συλλογής. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Προσθέτει μια νέα διαφάνεια διάταξης στο τέλος της συλλογής. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Εισάγει μια νέα διαφάνεια διάταξης στη συγκεκριμένη θέση της συλλογής. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Αφαιρεί το στοιχείο στη συγκεκριμένη θέση της συλλογής. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Μετακινεί τη διαφάνεια διάταξης από τη συλλογή στη συγκεκριμένη θέση. |

### Δείτε επίσης
* κλάση [`LayoutSlideCollection`](/slides/python-net/el/aspose.slides/layoutslidecollection)
* κλάση [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)