---
title: SmartArtNode
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs
url: /el/aspose.slides/smartartnode/
---
## SmartArtNode κλάση

 Αντιπροσωπεύει κόμβο ενός αντικειμένου SmartArt
 
### getBulletFillFormat {#getBulletFillFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getBulletFillFormat () | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα bullet κόμβου. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους διάταξης SmartArt που δεν παρέχουν bullets για κόμβους. Μόνο ανάγνωση IFillFormat. |

 **Επιστρέφει:**
[FillFormat](../fillformat)


---


### getChildNodes {#getChildNodes}

| Όνομα | Περιγραφή |
| --- | --- |
| getChildNodes () | Επιστρέφει συλλογές όλων των θυγατρικών κόμβων του τρέχοντος κόμβου. Μόνο ανάγνωση ISmartArtNodeCollection. |

 **Επιστρέφει:**
[SmartArtNodeCollection](../smartartnodecollection)


---


### getLevel {#getLevel}

| Όνομα | Περιγραφή |
| --- | --- |
| getLevel () | Επιστρέφει το επίπεδο εμφώλευσης του κόμβου. Μόνο ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getOrganizationChartLayout {#getOrganizationChartLayout}

| Όνομα | Περιγραφή |
| --- | --- |
| getOrganizationChartLayout () | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή OrganizationChartLayoutType. |

 **Επιστρέφει:**
int


---


### getPosition {#getPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| getPosition () | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδελφών κόμβων. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
int

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentOutOfRangeException | η τιμή είναι μικρότερη του 0. -or- η τιμή είναι ίση ή μεγαλύτερη από τον αριθμό των αδερφών |


---


### getShapes {#getShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapes () | Επιστρέφει συλλογές όλων των σχημάτων που σχετίζονται με τον κόμβο. Μόνο ανάγνωση ISmartArtShapeCollection. |

 **Επιστρέφει:**
[SmartArtShapeCollection](../smartartshapecollection)


---


### getTextFrame {#getTextFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFrame () | Επιστρέφει το πλαίσιο κειμένου του κόμβου. Μόνο ανάγνωση ITextFrame. |

 **Επιστρέφει:**
[TextFrame](../textframe)


---


### isAssistant {#isAssistant}

| Όνομα | Περιγραφή |
| --- | --- |
| isAssistant () | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isHidden {#isHidden}

| Όνομα | Περιγραφή |
| --- | --- |
| isHidden () | Επιστρέφει true εάν αυτός ο κόμβος είναι κρυφός στο μοντέλο δεδομένων. Μόνο ανάγνωση boolean. |

 **Επιστρέφει:**
boolean


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Αφαιρεί τον τρέχοντα κόμβο. |

 **Επιστρέφει:**
boolean


---


### setAssistant {#setAssistant}

| Όνομα | Περιγραφή |
| --- | --- |
| setAssistant (boolean) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setOrganizationChartLayout {#setOrganizationChartLayout}

| Όνομα | Περιγραφή |
| --- | --- |
| setOrganizationChartLayout (int) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή OrganizationChartLayoutType. |

 **Επιστρέφει:**
void


---


### setPosition {#setPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| setPosition (int) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδελφών κόμβων. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentOutOfRangeException | η τιμή είναι μικρότερη του 0. -or- η τιμή είναι ίση ή μεγαλύτερη από τον αριθμό των αδερφών |


---