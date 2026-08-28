---
title: FontFallBackRule
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/fontfallbackrule/
---
## FontFallBackRule κλάση

 Αντιπροσωπεύει τον κανόνα εναλλακτικής γραμματοσειράς
 
### FontFallBackRule {#FontFallBackRule}

| Όνομα | Περιγραφή |
| --- | --- |
| FontFallBackRule(long, long, String) | Δημιουργεί νέα实例. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικό δείκτη του εύρους Unicode |
| endIndex | long | Τελικός δείκτης του εύρους Unicode |
| fontNames | String | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για το FallBack |

 **Επιστρέφει:**
FontFallBackRule


---


### FontFallBackRule {#FontFallBackRule}

| Όνομα | Περιγραφή |
| --- | --- |
| FontFallBackRule(long, long, java.lang.String[]) | Δημιουργεί νέα实例. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικό δείκτη του εύρους Unicode |
| endIndex | long | Τελικός δείκτης του εύρους Unicode |
| fontNames | java.lang.String[] | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για το FallBack |

 **Επιστρέφει:**
FontFallBackRule


---


### addFallBackFonts {#addFallBackFonts}

| Όνομα | Περιγραφή |
| --- | --- |
| addFallBackFonts (String) | Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για το FallBack |

 **Επιστρέφει:**
void


---


### addFallBackFonts {#addFallBackFonts}

| Όνομα | Περιγραφή |
| --- | --- |
| addFallBackFonts (java.lang.String[]) | Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | java.lang.String[] | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για το FallBack |

 **Επιστρέφει:**
void


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλες τις γραμματοσειρές από τη λίστα. |

 **Επιστρέφει:**
void


---


### getCount {#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount () | Λαμβάνει τον αριθμό των γραμματοσειρών που έχουν οριστεί για το εύρος. int μόνο για ανάγνωση. |

 **Επιστρέφει:**
int


---


### getRangeEndIndex {#getRangeEndIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| getRangeEndIndex () | Επιστρέφει τον τελευταίο δείκτη του συνεχούς εύρους Unicode. |

 **Επιστρέφει:**
long


---


### getRangeStartIndex {#getRangeStartIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| getRangeStartIndex () | Επιστρέφει τον πρώτο δείκτη του συνεχούς εύρους Unicode. |

 **Επιστρέφει:**
long


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Λαμβάνει το όνομα της γραμματοσειράς στη συγκεκριμένη θέση. IFontFallBackRule μόνο για ανάγνωση. |

 **Επιστρέφει:**
String


---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf (String) | Επιστρέφει έναν δείκτη του συγκεκριμένου κανόνα στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα γραμματοσειράς προς εύρεση. |

 **Επιστρέφει:**
int


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove (String) | Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Το όνομα της γραμματοσειράς προς αφαίρεση από τη λίστα. |

 **Επιστρέφει:**
void


---


### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί τη γραμματοσειρά FallBack στη συγκεκριμένη θέση της λίστας. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης της γραμματοσειράς προς αφαίρεση. |

 **Επιστρέφει:**
void


---


### setRangeEndIndex {#setRangeEndIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| setRangeEndIndex (long) | Ορίζει τον τελευταίο δείκτη του συνεχούς εύρους Unicode. |

 **Επιστρέφει:**
void


---


### setRangeStartIndex {#setRangeStartIndex}

| Όνομα | Περιγραφή |
| --- | --- |
| setRangeStartIndex (long) | Ορίζει τον πρώτο δείκτη του συνεχούς εύρους Unicode. |

 **Επιστρέφει:**
void


---


### toArray {#toArray}

| Όνομα | Περιγραφή |
| --- | --- |
| toArray () | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα. |

 **Επιστρέφει:**
String


---


### toArray {#toArray}

| Όνομα | Περιγραφή |
| --- | --- |
| toArray (int, int) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από το καθορισμένο εύρος στη λίστα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης γραμματοσειράς που θα προστεθεί. |
| count | int | Αριθμός γραμματοσειρών που θα προστεθούν. |

 **Επιστρέφει:**
String


---