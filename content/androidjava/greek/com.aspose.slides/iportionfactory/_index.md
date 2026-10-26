---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Επιτρέπει τη δημιουργία δοκιμαστικών τμημάτων
type: docs
url: /el/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Επιτρέπει τη δημιουργία δοκιμαστικών τμημάτων

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createPortion()](#createPortion--) | Δημιουργεί ένα κενό τμήμα κειμένου. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Δημιουργεί ένα τμήμα κειμένου από καθορισμένη συμβολοσειρά. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Δημιουργεί ένα τμήμα χρησιμοποιώντας τα δεδομένα ενός καθορισμένου τμήματος. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Δημιουργεί ένα κενό τμήμα κειμένου.

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Δημιουργεί ένα τμήμα κειμένου από καθορισμένη συμβολοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | java.lang.String | String. |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Δημιουργεί ένα τμήμα χρησιμοποιώντας τα δεδομένα ενός καθορισμένου τμήματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Ένα τμήμα προς χρήση. |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.