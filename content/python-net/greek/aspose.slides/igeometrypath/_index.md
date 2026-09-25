---
title: IGeometryPath class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/igeometrypath/
---
## IGeometryPath κλάση

Αναπαριστά το γεωμετρικό μονοπάτι του GeometryShape

Ο τύπος IGeometryPath περιέχει τα παρακάτω μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/el/aspose.slides/igeometrypath/path_data/) | Επιστρέφει το γεωμετρικό μονοπάτι του GeometryShape ως έναν πίνακα τμημάτων μονοπατιού. |
| [`fill_mode`](/slides/python-net/el/aspose.slides/igeometrypath/fill_mode/) | Ορίζει τη λειτουργία γεμίσματος |
| [`stroke`](/slides/python-net/el/aspose.slides/igeometrypath/stroke/) | Ορίζει την εμφάνιση του περιγράμματος |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/el/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Προσθέτει γραμμή στο τέλος του μονοπατιού |
| [`line_to(self, x, y)`](/slides/python-net/el/aspose.slides/igeometrypath/line_to/#float-float) | Προσθέτει γραμμή στο τέλος του μονοπατιού |
| [`line_to(self, point, index)`](/slides/python-net/el/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού |
| [`line_to(self, x, y, index)`](/slides/python-net/el/aspose.slides/igeometrypath/line_to/#float-float-int) | Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/el/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Προσθέτει κυρτή καμπύλη Bezier στο τέλος του μονοπατιού |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/el/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Προσθέτει κυρτή καμπύλη Bezier στο τέλος του μονοπατιού |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/el/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Προσθέτει κυρτή καμπύλη Bezier στη συγκεκριμένη θέση του μονοπατιού |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/el/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Προσθέτει κυρτή καμπύλη Bezier στη συγκεκριμένη θέση του μονοπατιού |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/el/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος του μονοπατιού |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/el/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος του μονοπατιού |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/el/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Προσθέτει τετραγωνική καμπύλη Bezier στη συγκεκριμένη θέση του μονοπατιού |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/el/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Προσθέτει τετραγωνική καμπύλη Bezier στη συγκεκριμένη θέση του μονοπατιού |
| [`move_to(self, point)`](/slides/python-net/el/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Ορίζει τη θέση του επόμενου σημείου. |
| [`move_to(self, x, y)`](/slides/python-net/el/aspose.slides/igeometrypath/move_to/#float-float) | Ορίζει τη θέση του επόμενου σημείου. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/igeometrypath/remove_at/#int) | Αφαιρεί το τμήμα στο καθορισμένο δείκτη του γεωμετρικού μονοπατιού. |
| [`close_figure(self)`](/slides/python-net/el/aspose.slides/igeometrypath/close_figure/#) | Κλείνει το τρέχον σχήμα αυτού του μονοπατιού |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/el/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Προσθέτει το καθορισμένο τόξο στο μονοπάτι. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)