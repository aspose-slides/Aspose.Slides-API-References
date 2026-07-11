---
title: PortionFactory
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Επιτρέπει τη δημιουργία δοκιμαστικών Portion
type: docs
url: /el/com.aspose.slides/portionfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Επιτρέπει τη δημιουργία δοκιμαστικών Portion

--------------------

Για συμβατότητα COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createPortion()](#createPortion--) | Δημιουργεί ένα κενό text Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Δημιουργεί ένα text Portion από το καθορισμένο string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Δημιουργεί ένα Portion με τη χρήση των δεδομένων ενός καθορισμένου Portion. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Δημιουργεί ένα κενό text Portion.

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Δημιουργεί ένα text Portion από το καθορισμένο string.

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


Δημιουργεί ένα Portion με τη χρήση των δεδομένων ενός καθορισμένου Portion.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Ένα Portion για χρήση. |

**Επιστρέφει:**
[IPortion](../../com.aspose.slides/iportion) - Portion.