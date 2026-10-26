---
title: Fonts
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/fonts/
---
## Fonts κλάση

 Συλλογή γραμματοσειρών.
 
### getComplexScriptFont {#getComplexScriptFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getComplexScriptFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά σύνθετου σεναρίου. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
[FontData](../fontdata)


---


### getEastAsianFont {#getEastAsianFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getEastAsianFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά Ανατολικής Ασίας. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
[FontData](../fontdata)


---


### getLatinFont {#getLatinFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getLatinFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά Λατινική. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
[FontData](../fontdata)


---


### getScriptFont {#getScriptFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getScriptFont (String) | Λαμβάνει το όνομα γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα σεναρίου από το θέμα της παρουσίασης. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | String | Ο κωδικός σεναρίου BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την ταυτοποίηση ενός συστήματος γραφής. |

 **Επιστρέφει:**
String


---


### getScriptFontMap {#getScriptFontMap}

| Όνομα | Περιγραφή |
| --- | --- |
| getScriptFontMap () | Επιστρέφει ένα λεξικό όλων των ορισμών γραμματοσειρών σεναρίου στην παρουσίαση. |

 **Επιστρέφει:**
Dictionary


---


### removeScriptFont {#removeScriptFont}

| Όνομα | Περιγραφή |
| --- | --- |
| removeScriptFont (String) | Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα σεναρίου από τη συλλογή γραμματοσειρών του θέματος. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | String | Ο κωδικός σεναρίου BCP-47 του οποίο η ρύθμιση γραμματοσειράς πρέπει να αφαιρεθεί. |

 **Επιστρέφει:**
void


---


### setComplexScriptFont {#setComplexScriptFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setComplexScriptFont ([FontData](../fontdata)) | Επιστρέφει ή ορίζει τη γραμματοσειρά σύνθετου σεναρίου. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
void


---


### setEastAsianFont {#setEastAsianFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setEastAsianFont ([FontData](../fontdata)) | Επιστρέφει ή ορίζει τη γραμματοσειρά Ανατολικής Ασίας. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
void


---


### setLatinFont {#setLatinFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setLatinFont ([FontData](../fontdata)) | Επιστρέφει ή ορίζει τη γραμματοσειρά Λατινική. Ανάγνωση/εγγραφή IFontData. |

 **Επιστρέφει:**
void


---


### setScriptFont {#setScriptFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setScriptFont (String, String) | Αντιστοιχεί ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα σεναρίου, η οποία καθορίζει πώς θα αποτυπώνεται το κείμενο εκείνου του σεναρίου στην παρουσίαση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | String | Ο κωδικός σεναρίου BCP-47 (π.χ., "Arab", "Hebr", "Hans") που ταυτοποιεί το σύστημα γραφής. |
| fontName | String | Το όνομα της γραμματοσειράς που θα αντιστοιχιστεί στην καθορισμένη ετικέτα σεναρίου. |

 **Επιστρέφει:**
void


---