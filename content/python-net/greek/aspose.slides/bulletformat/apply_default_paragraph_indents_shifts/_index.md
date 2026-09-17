---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Ορίζει τις προεπιλεγμένες μετατοπίσεις μη μηδενικές για το αποτελεσματικό Indent και MarginLeft της παραγράφου όταν είναι ενεργοποιημένα τα bullets (όπως κάνει το PowerPoint όταν ενεργοποιεί την σήμανση/αρίθμηση παραγράφων). Εάν τα bullets είναι απενεργοποιημένα, απλώς επαναφέρει το Indent και MarginLeft της παραγράφου (όπως κάνει το PowerPoint όταν απενεργοποιεί τη σήμανση/αρίθμηση παραγράφων). Οι μετατοπίσεις των εσοχών εφαρμόζονται σε σχέση με το τρέχον πλαίσιο bullet - IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου μέρους. Οι μη μηδενικές μετατοπίσεις των εσοχών εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (κάνει τις τιμές αποτέλεσμα τοπικές).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Η κλήση αυτής της μεθόδου δεν έχει νόημα και προκαλεί **System.InvalidOperationException** στις ακόλουθες περιπτώσεις:<br/>            αν το γονικό μορφοποιημένο αντικείμενο δεν είναι παράγραφος (για παράδειγμα η κλήση ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() θα προκαλέσει εξαίρεση);<br/>            ή αν η παράγραφος δεν προστέθηκε σε καμία συλλογή ITextFrame.Paragraphs (προσθέστε την πρώτα); |



### Δείτε επίσης
* κλάση [`BulletFormat`](/slides/python-net/el/aspose.slides/bulletformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)