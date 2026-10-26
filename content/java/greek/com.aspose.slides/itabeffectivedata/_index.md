---
title: ITabEffectiveData
second_title: Αναφορά API Aspose.Slides για Java
description: Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες διακοπής στηλοθέτη του αποτελεσματικού κειμένου.
type: docs
url: /el/com.aspose.slides/itabeffectivedata/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες διακοπής στηλοθέτη του αποτελεσματικού κειμένου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Επιστρέφει τη θέση μιας στηλοθέτη. |
| [getAlignment()](#getAlignment--) | Επιστρέφει το στυλ στοίχισης μιας στηλοθέτη. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Επιστρέφει τη θέση μιας στηλοθέτη. Η ανάθεση αυτής της ιδιότητας μπορεί να αλλάξει το ευρετήριο της στηλοθέτη στη συλλογή και να ακυρώσει τον Enumerator. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Επιστρέφει το στυλ στοίχισης μιας στηλοθέτη. Μόνο για ανάγνωση [TabAlignment](../../com.aspose.slides/tabalignment).

**Επιστρέφει:**
int