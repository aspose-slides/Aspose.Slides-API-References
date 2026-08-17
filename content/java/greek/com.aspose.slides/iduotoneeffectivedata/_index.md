---
title: IDuotoneEffectiveData
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Duotone.
type: docs
url: /el/com.aspose.slides/iduotoneeffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα εφέ Duotone. Για κάθε pixel, συνδυάζει τα clr1 και clr2 μέσω γραμμικής παρεμβολής για να καθορίσει το νέο χρώμα για εκείνο το pixel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor1()](#getColor1--) | Επιστρέφει τη μορφή χρώματος-στόχο για σκοτεινά pixel. |
| [getColor2()](#getColor2--) | Επιστρέφει τη μορφή χρώματος-στόχο για ανοιχτά pixel. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Επιστρέφει τη μορφή χρώματος-στόχο για σκοτεινά pixel. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Επιστρέφει τη μορφή χρώματος-στόχο για ανοιχτά pixel. Μόνο για ανάγνωση java.awt.Color.

**Επιστρέφει:**
java.awt.Color