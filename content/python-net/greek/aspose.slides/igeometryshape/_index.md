---
title: IGeometryShape class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/igeometryshape/
---
## IGeometryShape κλάση

Αναπαριστά την γονική κλάση για όλα τα γεωμετρικά σχήματα.

Ο τύπος IGeometryShape εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/el/aspose.slides/igeometryshape/shape_style/) | Επιστρέφει το αντικείμενο στυλ του σχήματος.<br/>            Μόνο για ανάγνωση [`IShapeStyle`](/slides/python-net/el/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/el/aspose.slides/igeometryshape/shape_type/) | Επιστρέφει ή ορίζει τον προκαθορισμένο τύπο γεωμετρίας.<br/>            Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογών θα επαναφερθούν στις προεπιλογές.<br/>            Ανάγνωση/εγγραφή [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/el/aspose.slides/igeometryshape/adjustments/) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος.<br/>            Μόνο για ανάγνωση [`IAdjustValueCollection`](/slides/python-net/el/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/el/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/el/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/el/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/el/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/el/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/el/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/el/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/el/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/el/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/el/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/el/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/el/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/el/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/el/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/el/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/el/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/el/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/el/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/el/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/el/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/el/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/el/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/el/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/el/aspose.slides/igeometryshape/get_geometry_paths/#) | Επιστρέφει το αντίγραφο του μονοπατιού του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την επάνω αριστερή γωνία του σχήματος. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/el/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             πάνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`IGeometryShape.shape_type`](/slides/python-net/el/aspose.slides/igeometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/el/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα του [`IGeometryPath`](/slides/python-net/el/aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή<br/>             πάνω γωνία του σχήματος.<br/>             Αλλάζει τον τύπο του σχήματος ([`IGeometryShape.shape_type`](/slides/python-net/el/aspose.slides/igeometryshape/shape_type)) σε [`ShapeType.CUSTOM`](/slides/python-net/el/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/el/aspose.slides/igeometryshape/create_shape_elements/#) | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)