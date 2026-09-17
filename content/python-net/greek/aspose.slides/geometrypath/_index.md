---
title: GeometryPath class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/geometrypath/
---
## GeometryPath κλάση

Αναπαριστά την γεωμετρική διαδρομή του GeometryShape

Ο τύπος GeometryPath εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/geometrypath/__init__/#) | Δημιουργεί μια παρουσία του GeometryPath |

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/el/aspose.slides/geometrypath/path_data/) | Επιστρέφει τη γεωμετρική διαδρομή του GeometryShape ως πίνακα τμημάτων διαδρομής. |
| [`fill_mode`](/slides/python-net/el/aspose.slides/geometrypath/fill_mode/) | Ορίζει τη λειτουργία γεμίσματος |
| [`stroke`](/slides/python-net/el/aspose.slides/geometrypath/stroke/) | Ορίζει την εμφάνιση του περιγράμματος |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Προσθέτει γραμμή στο τέλος της διαδρομής |
| [`line_to(self, x, y)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#float-float) | Προσθέτει γραμμή στο τέλος της διαδρομής |
| [`line_to(self, point, index)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής |
| [`line_to(self, x, y, index)`](/slides/python-net/el/aspose.slides/geometrypath/line_to/#float-float-int) | Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Προσθέτει κυβική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/el/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Προσθέτει κυβική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/el/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής |
| [`move_to(self, point)`](/slides/python-net/el/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Ορίζει τη θέση του επόμενου σημείου. |
| [`move_to(self, x, y)`](/slides/python-net/el/aspose.slides/geometrypath/move_to/#float-float) | Ορίζει τη θέση του επόμενου σημείου. |
| [`remove_at(self, index)`](/slides/python-net/el/aspose.slides/geometrypath/remove_at/#int) | Αφαιρεί το τμήμα στον καθορισμένο δείκτη της γεωμετρικής διαδρομής. |
| [`close_figure(self)`](/slides/python-net/el/aspose.slides/geometrypath/close_figure/#) | Κλείνει το τρέχον σχήμα αυτής της διαδρομής |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/el/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Προσθέτει το καθορισμένο τόξο στη διαδρομή. |


### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)