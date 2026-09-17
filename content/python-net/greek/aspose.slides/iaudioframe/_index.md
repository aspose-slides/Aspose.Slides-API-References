---
title: IAudioFrame class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iaudioframe/
---
## IAudioFrame κλάση

Αντιπροσωπεύει ένα κομμάτι ήχου σε μια διαφάνεια.

Ο τύπος IAudioFrame εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`audio_cd_start_track`](/slides/python-net/el/aspose.slides/iaudioframe/audio_cd_start_track/) | Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/el/aspose.slides/iaudioframe/audio_cd_start_track_time/) | Επιστρέφει ή ορίζει χρόνο αρχικού κομματιού.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`audio_cd_end_track`](/slides/python-net/el/aspose.slides/iaudioframe/audio_cd_end_track/) | Επιστρέφει ή ορίζει έναν δείκτη τελικού κομματιού<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/el/aspose.slides/iaudioframe/audio_cd_end_track_time/) | Επιστρέφει ή ορίζει χρόνο τελικού κομματιού.<br/>            Ανάγνωση/Εγγραφή **int**. |
| [`volume`](/slides/python-net/el/aspose.slides/iaudioframe/volume/) | Επιστρέφει ή ορίζει την ένταση του ήχου.<br/>            Ανάγνωση/Εγγραφή [`AudioVolumeMode`](/slides/python-net/el/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/el/aspose.slides/iaudioframe/play_mode/) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου.<br/>            Ανάγνωση/Εγγραφή [`AudioPlayModePreset`](/slides/python-net/el/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/el/aspose.slides/iaudioframe/hide_at_showing/) | Καθορίζει αν ένα AudioFrame είναι κρυφό.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`play_loop_mode`](/slides/python-net/el/aspose.slides/iaudioframe/play_loop_mode/) | Καθορίζει αν ένα ήχο επαναλαμβάνεται σε βρόχο.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`play_across_slides`](/slides/python-net/el/aspose.slides/iaudioframe/play_across_slides/) | Καθορίζει αν ένα ήχος αναπαράγεται σε όλες τις διαφάνειες.<br/>             Ανάγνωση/Εγγραφή **bool**. |
| [`rewind_audio`](/slides/python-net/el/aspose.slides/iaudioframe/rewind_audio/) | Καθορίζει αν ένα ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή.<br/>             Ανάγνωση/Εγγραφή **bool**. |
| [`embedded`](/slides/python-net/el/aspose.slides/iaudioframe/embedded/) | Καθορίζει αν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση.<br/>            Μόνο για ανάγνωση **bool**. |
| [`link_path_long`](/slides/python-net/el/aspose.slides/iaudioframe/link_path_long/) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`embedded_audio`](/slides/python-net/el/aspose.slides/iaudioframe/embedded_audio/) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου.<br/>            Ανάγνωση/Εγγραφή [`IAudio`](/slides/python-net/el/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/el/aspose.slides/iaudioframe/fade_in_duration/) | Καθορίζει τη διάρκεια χρόνου για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου.<br/>             Ανάγνωση/Εγγραφή **float**. |
| [`fade_out_duration`](/slides/python-net/el/aspose.slides/iaudioframe/fade_out_duration/) | Καθορίζει τη διάρκεια χρόνου για την τελική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου.<br/>             Ανάγνωση/Εγγραφή **float**. |
| [`volume_value`](/slides/python-net/el/aspose.slides/iaudioframe/volume_value/) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά.<br/>             Ανάγνωση/Εγγραφή **float**. |
| [`trim_from_start`](/slides/python-net/el/aspose.slides/iaudioframe/trim_from_start/) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`trim_from_end`](/slides/python-net/el/aspose.slides/iaudioframe/trim_from_end/) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`caption_tracks`](/slides/python-net/el/aspose.slides/iaudioframe/caption_tracks/) | Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου.<br/>            Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](/slides/python-net/el/aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/iaudioframe/shape_lock/) |  |
| [`picture_frame_lock`](/slides/python-net/el/aspose.slides/iaudioframe/picture_frame_lock/) |  |
| [`picture_format`](/slides/python-net/el/aspose.slides/iaudioframe/picture_format/) |  |
| [`relative_scale_height`](/slides/python-net/el/aspose.slides/iaudioframe/relative_scale_height/) |  |
| [`relative_scale_width`](/slides/python-net/el/aspose.slides/iaudioframe/relative_scale_width/) |  |
| [`shape_style`](/slides/python-net/el/aspose.slides/iaudioframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/el/aspose.slides/iaudioframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/el/aspose.slides/iaudioframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/iaudioframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/el/aspose.slides/iaudioframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/iaudioframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/el/aspose.slides/iaudioframe/raw_frame/) |  |
| [`frame`](/slides/python-net/el/aspose.slides/iaudioframe/frame/) |  |
| [`line_format`](/slides/python-net/el/aspose.slides/iaudioframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/el/aspose.slides/iaudioframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/el/aspose.slides/iaudioframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/el/aspose.slides/iaudioframe/fill_format/) |  |
| [`hidden`](/slides/python-net/el/aspose.slides/iaudioframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/el/aspose.slides/iaudioframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/iaudioframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/el/aspose.slides/iaudioframe/rotation/) |  |
| [`x`](/slides/python-net/el/aspose.slides/iaudioframe/x/) |  |
| [`y`](/slides/python-net/el/aspose.slides/iaudioframe/y/) |  |
| [`width`](/slides/python-net/el/aspose.slides/iaudioframe/width/) |  |
| [`height`](/slides/python-net/el/aspose.slides/iaudioframe/height/) |  |
| [`alternative_text`](/slides/python-net/el/aspose.slides/iaudioframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/iaudioframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/el/aspose.slides/iaudioframe/name/) |  |
| [`is_decorative`](/slides/python-net/el/aspose.slides/iaudioframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/el/aspose.slides/iaudioframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/iaudioframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/el/aspose.slides/iaudioframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/iaudioframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/el/aspose.slides/iaudioframe/parent_group/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/iaudioframe/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/iaudioframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/iaudioframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/iaudioframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/iaudioframe/hyperlink_manager/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/iaudioframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/iaudioframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/iaudioframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/iaudioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/iaudioframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/iaudioframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/iaudioframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/iaudioframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/iaudioframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/iaudioframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/iaudioframe/get_base_placeholder/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)