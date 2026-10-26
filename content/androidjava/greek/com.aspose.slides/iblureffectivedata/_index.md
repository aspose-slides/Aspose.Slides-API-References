---
title: IBlurEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος.
type: docs
url: /el/com.aspose.slides/iblureffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Θολώματος που εφαρμόζεται σε ολόκληρο το σχήμα, συμπεριλαμβανομένου του γεμίσματος. Όλα τα κανάλια χρώματος, συμπεριλαμβανομένου του άλφα, επηρεάζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRadius()](#getRadius--) | Επιστρέφει ή ορίζει την ακτίνα θολώματος. |
| [getGrow()](#getGrow--) | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Επιστρέφει ή ορίζει την ακτίνα θολώματος. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Καθορίζει εάν τα όρια του αντικειμένου πρέπει να αυξηθούν ως αποτέλεσμα της θόλωσης. Η True υποδεικνύει ότι τα όρια αυξάνονται, ενώ η false υποδεικνύει ότι δεν αυξάνονται. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean