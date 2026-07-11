---
title: IBiLevelEffectiveData
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα δυο-επίπεδο μαύρο/λευκό εφέ.
type: docs
url: /el/com.aspose.slides/ibileveleffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα Δι-επίπεδο (μαύρο/λευκό) εφέ. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μικρότερη από την καθορισμένη τιμή κατωφλίου μετατρέπονται σε μαύρο. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μεγαλύτερη ή ίση με την καθορισμένη τιμή ορίζονται σε λευκό. Οι τιμές του alpha effect δεν επηρεάζονται από αυτό το εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getThreshold()](#getThreshold--) | Επιστρέφει την τιμή του κατωφλίου. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Επιστρέφει την τιμή του κατωφλίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float