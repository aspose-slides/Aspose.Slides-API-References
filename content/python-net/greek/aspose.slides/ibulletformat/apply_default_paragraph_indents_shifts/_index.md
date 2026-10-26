---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Ορίζει προεπιλεγμένες μη μηδενικές μετατοπίσεις για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν είναι ενεργά τα bullets (όπως κάνει το PowerPoint εάν ενεργοποιηθούν τα bullets/αρίθμηση παραγράφων). Εάν τα bullets είναι απενεργοποιημένα, επαναφέρει απλώς το Indent και το MarginLeft της παραγράφου (όπως κάνει το PowerPoint εάν απενεργοποιηθούν τα bullets/αρίθμηση). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο bullet – IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετατοπίσεις εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (για να γίνουν οι τιμές τοπικές).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Η κλήση αυτής της μεθόδου δεν έχει σημασία και πετάει **System.InvalidOperationException** στις ακόλουθες περιπτώσεις:<br/>            εάν το γονικό μορφοποιημένο αντικείμενο δεν είναι παράγραφος (για παράδειγμα η κλήση ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() θα πετάξει εξαίρεση);<br/>            ή εάν η παράγραφος δεν έχει προστεθεί σε καμία συλλογή ITextFrame.Paragraphs (προσθέστε την πρώτα); |

### Δείτε επίσης
* κλάση [`IBulletFormat`](/slides/python-net/el/aspose.slides/ibulletformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)