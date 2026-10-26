---
title: GeometryPath class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/geometrypath/
---
## GeometryPath κλάση

Αναπαριστά τη διαδρομή γεωμετρίας του GeometryShape

Ο τύπος GeometryPath εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/geometrypath/__init__/#) | Δημιουργεί ένα αντικείμενο GeometryPath |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`path_data`](/slides/python-net/el/aspose.slides/geometrypath/path_data/) | Επιστρέφει τη διαδρομή γεωμετρίας του GeometryShape ως έναν πίνακα τμημάτων διαδρομής. |
| [`fill_mode`](/slides/python-net/el/aspose.slides/geometrypath/fill_mode/) | Ορίζει τη λειτουργία γεμίσματος |
| [`stroke`](/slides/python-net/el/aspose.slides/geometrypath/stroke/) | Ορίζει την εμφάνιση του περιγράμματος |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Προσθέτει γραμμή στο τέλος της διαδρομής |
| [`line_to(self, x, y)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#float-float) | Προσθέτει γραμμή στο τέλος της διαδρομής |
| [`line_to(self, point, index)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Προσθέτει γραμμή στο καθορισμένο σημείο της διαδρομής |
| [`line_to(self, x, y, index)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#float-float-int) | Προσθέτει γραμμή στο καθορισμένο σημείο της διαδρομής |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Προσθέτει κυβική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Προσθέτει κυβική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Προσθέτει τετραγωνική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Προσθέτει τετραγωνική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής |
| [`move_to(self, point)`](/slides/python-net/el/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Ορίζει τη θέση του επόμενου σημείου. |
| [`move_to(self, x, y)`](/slides/python-net/el/aspose.slides/geometrypath/move_to/#float-float) | Ορίζει τη θέση του επόμενου σημείου. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/geometrypath/remove_at/#int) | Αφαιρεί τμήμα στο καθορισμένο δείκτη της διαδρομής γεωμετρίας. |
| [`close_figure(self)`](/slides/python-net/el/aspose.slides/geometrypath/close_figure/#) | Κλείνει το τρέχον σχήμα αυτής της διαδρομής |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/el/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Προσθέτει το καθορισμένο τόξο στη διαδρομή. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)