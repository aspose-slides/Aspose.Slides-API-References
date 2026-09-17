---
title: enclose method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις

### Επιστρέφει

Το μαθηματικό στοιχείο τύπου [`IMathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/imathdelimiter) που περιλαμβάνει τις παρενθέσεις



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

### Επιστρέφει

Αν `beginning_character` και `ending_character` είναι None,
            οι αντίστοιχες ιδιότητες λαμβάνουν μόνο τιμές και δεν δημιουργείται νέο αντικείμενο (επιστρέφει αυτή την παρουσία).
            Διαφορετικά, επιστρέφει νέο μαθηματικό στοιχείο τύπου Delimiter που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο
            και αυτή την παρουσία του [`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter) εντός του πλαισίου.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| beginning_character | **char** | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| ending_character | **char** | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |



### Δείτε επίσης
* κλάση [`IMathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/imathdelimiter)
* κλάση [`MathDelimiter`](/slides/python-net/el/aspose.slides.mathtext/mathdelimiter)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)