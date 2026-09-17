---
title: IConnector class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iconnector/
---
## IConnector κλάση

Απεικονίζει έναν connector.

Ο τύπος IConnector εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`shape_lock`](/slides/python-net/el/aspose.slides/iconnector/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο-ανάγνωση [`IConnectorLock`](/slides/python-net/el/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/el/aspose.slides/iconnector/connector_lock/) | Επιστρέφει τις κλειδώσεις του Connector.<br/>            Μόνο-ανάγνωση [`IConnectorLock`](/slides/python-net/el/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/el/aspose.slides/iconnector/start_shape_connected_to/) | Επιστρέφει ή ορίζει το σχήμα για τη σύνδεση της αρχής του connector.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/el/aspose.slides/iconnector/end_shape_connected_to/) | Επιστρέφει ή ορίζει το σχήμα για τη σύνδεση του τέλους του connector.<br/>            Ανάγνωση/εγγραφή [`IShape`](/slides/python-net/el/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/el/aspose.slides/iconnector/start_shape_connection_site_index/) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/el/aspose.slides/iconnector/end_shape_connection_site_index/) | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`shape_style`](/slides/python-net/el/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/el/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/el/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/el/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/el/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/el/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/el/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/el/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/el/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/el/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/el/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/el/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/el/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/el/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/el/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/el/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/el/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/el/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/el/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/el/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/el/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/el/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/el/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/iconnector/hyperlink_manager/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/el/aspose.slides/iconnector/reroute/#) | Αναδρομολογεί το connector ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των σχημάτων που συνδέει. |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/iconnector/get_base_placeholder/#) |  |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)