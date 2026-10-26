---
title: PortionFactory
second_title: Aspose.Slides για την Αναφορά API της Java
description: Επιτρέπει τη δημιουργία δοκιμαστικών τμημάτων
type: docs
url: /el/com.aspose.slides/portionfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Επιτρέπει τη δημιουργία δοκιμαστικών τμημάτων

--------------------

Για συμβατότητα με COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Δημιουργεί ένα κενό τμήμα κειμένου.

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Δημιουργεί ένα τμήμα κειμένου από την καθορισμένη συμβολοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | java.lang.String | String. |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Δημιουργεί ένα τμήμα χρησιμοποιώντας τα δεδομένα ενός καθορισμένου τμήματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Ένα τμήμα προς χρήση. |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.