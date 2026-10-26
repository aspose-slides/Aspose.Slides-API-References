---
title: IBiLevelEffectiveData
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα διεπίπεδο μαύρο/άσπρο εφέ.
type: docs
url: /el/com.aspose.slides/ibileveleffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Αμετάβλητο αντικείμενο που αντιπροσωπεύει ένα δι-επίπεδο (μαύρο/άσπρο) εφέ. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μικρότερη από την καθορισμένη τιμή κατωφλίου μετατρέπονται σε μαύρο. Τα χρώματα εισόδου των οποίων η φωτεινότητα είναι μεγαλύτερη ή ίση με την καθορισμένη τιμή τίθενται σε άσπρο. Οι τιμές του αλφα εφέ δεν επηρεάζονται από αυτό το εφέ.
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