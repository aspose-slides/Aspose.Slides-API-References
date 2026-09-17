---
title: IMasterSlide class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/imasterslide/
---
## IMasterSlide κλάση

Αντιπροσωπεύει μια κύρια διαφάνεια σε μια παρουσίαση.

Ο τύπος IMasterSlide εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/el/aspose.slides/imasterslide/header_footer_manager/) | Returns HeaderFooter manager of the master slide.<br/>            Μόνο για ανάγνωση [`IMasterSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/el/aspose.slides/imasterslide/title_style/) | Returns the style of a title text.<br/>            Μόνο για ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/el/aspose.slides/imasterslide/body_style/) | Returns the style of a body text.<br/>            Μόνο για ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/el/aspose.slides/imasterslide/other_style/) | Returns the style of an other text.<br/>            Μόνο για ανάγνωση [`ITextStyle`](/slides/python-net/el/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/el/aspose.slides/imasterslide/layout_slides/) | Returns the collection of child layout slides for this master slide.<br/>            Μόνο για ανάγνωση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/el/aspose.slides/imasterslide/preserve/) | Καθορίζει αν η αντίστοιχη κύρια διαφάνεια διαγράφεται όταν όλες<br/>            οι διαφάνειες που ακολουθούν αυτήν την κύρια διαφάνεια διαγραφούν.<br/>            Σημείωση: Aspose.Slides will never remove any unused master by itself, <br/>            to actually remove unused masters call **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`has_depending_slides`](/slides/python-net/el/aspose.slides/imasterslide/has_depending_slides/) | Returns true if there exists at least one slide that depends on this master slide.<br/>            Μόνο για ανάγνωση **bool**. |
| [`drawing_guides`](/slides/python-net/el/aspose.slides/imasterslide/drawing_guides/) | Returns a collection of drawing guides for the master slide.<br/>            Μόνο για ανάγνωση [`IDrawingGuidesCollection`](/slides/python-net/el/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/el/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/el/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/el/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/el/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/el/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/el/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/el/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/el/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/el/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/el/aspose.slides/imasterslide/theme_manager/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/el/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Creates a new master slide based on the current one, applying an external theme to it <br/>            and applies the created master slide to all dependent slides. |
| [`get_depending_slides(self)`](/slides/python-net/el/aspose.slides/imasterslide/get_depending_slides/#) | Returns an array with all slides, which depend on this master slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/el/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/el/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/el/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/el/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)