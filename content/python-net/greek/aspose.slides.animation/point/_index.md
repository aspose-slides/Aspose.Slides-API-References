---
title: Point class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.animation/point/
---
## Τάξη Point

Παριστάνει σημείο animation.

Ο τύπος Point εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.animation/point/__init__/#) | Προεπιλεγμένος κατασκευαστής. |
| [`__init__(self, time, value, formula)`](/slides/python-net/el/aspose.slides.animation/point/__init__/#float-any-str) | Δημιουργεί σημείο animation με χρόνο, τιμή και τύπο. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`time`](/slides/python-net/el/aspose.slides.animation/point/time/) | Αντιπροσωπεύει την τιμή χρόνου.<br/>            Read/write **float**. |
| [`value`](/slides/python-net/el/aspose.slides.animation/point/value/) | Αντιπροσωπεύει την τιμή του σημείου.<br/>            Only: bool, ColorFormat, float, int, string.<br/>            Read/write **any**. |
| [`formula`](/slides/python-net/el/aspose.slides.animation/point/formula/) | Τύποι μέσα στις τιμές, τα χαρακτηριστικά from, to, by μπορούν να αποτελούνται από τα εξής:<br/>            Τυπικοί αριθμητικοί τελεστές: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Σταθερές: ‘pi’ ‘e’<br/>            Συνθήκες: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Τελεστές σύγκρισης: '==', '>=', '', '!=', '!'<br/>            Τριγωνομετρικοί τελεστές: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Φυσικός λογάριθμος ‘ln()’<br/>            Αναφορές ιδιοτήτων (ιδιότητες που υποστηρίζονται από τον κεντρικό)<br/>            <br/>            για παράδειγμα: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Read/write **str**. |

### Δείτε επίσης
* μονάδα [`aspose.slides.animation`](/slides/python-net/el/aspose.slides.animation)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)