---
title: MathMatrix
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/mathmatrix/
---
## MathMatrix κλάση

 Καθορίζει το αντικείμενο Matrix, που αποτελείται από στοιχεία-παιδιά τακτοποιημένα σε μία ή περισσότερες γραμμές και στήλες. 
 Σημαντικό είναι να σημειωθεί ότι τα matrices δεν έχουν ενσωματωμένα delimiters. 
 Για να τοποθετήσετε το matrix στα αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο delimiter (IMathDelimiter). 
 Τα Null arguments μπορούν να χρησιμοποιηθούν για δημιουργία κενών στα matrices.
 
### MathMatrix {#MathMatrix}

| Όνομα | Περιγραφή |
| --- | --- |
| MathMatrix(int, int) | Δημιουργεί μια νέα εμφάνιση της κλάσης MathMatrix. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowCount | int | αριθμός γραμμών |
| columnCount | int | αριθμός στηλών |

 **Επιστρέφει:**
MathMatrix


---


### deleteColumn {#deleteColumn}

| Όνομα | Περιγραφή |
| --- | --- |
| deleteColumn (int) | Διαγράφει την καθορισμένη στήλη |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Ο δείκτης μηδενικής βάσης της στήλης που θα διαγραφεί. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentOutOfRangeException | Εάν το columnIndex είναι μικρότερο του μηδενός ή μεγαλύτερο ή ίσο με το ColumnCount |


---


### deleteRow {#deleteRow}

| Όνομα | Περιγραφή |
| --- | --- |
| deleteRow (int) | Διαγράφει την καθορισμένη γραμμή |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Ο δείκτης μηδενικής βάσης της γραμμής που θα διαγραφεί. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentOutOfRangeException | Εάν το rowIndex είναι μικρότερο του μηδενός ή μεγαλύτερο ή ίσο με το RowCount |


---


### getBaseJustification {#getBaseJustification}

| Όνομα | Περιγραφή |
| --- | --- |
| getBaseJustification () | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center |

 **Επιστρέφει:**
int


---


### getChildren {#getChildren}

| Όνομα | Περιγραφή |
| --- | --- |
| getChildren () | Λάβετε τα στοιχεία-παιδιά |

 **Επιστρέφει:**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)


---


### getColumnAlignment {#getColumnAlignment}

| Όνομα | Περιγραφή |
| --- | --- |
| getColumnAlignment (int) | Λάβετε την οριζόντια στοίχιση της καθορισμένης στήλης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Μηδενική δείκτης στήλης |

 **Επιστρέφει:**
int


---


### getColumnCount {#getColumnCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getColumnCount () | Αριθμός στηλών στο matrix |

 **Επιστρέφει:**
int


---


### getColumnGap {#getColumnGap}

| Όνομα | Περιγραφή |
| --- | --- |
| getColumnGap () | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός matrix· Εάν το ColumnGapRule είναι 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν το ColumnGapRule είναι 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em increments. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |

 **Επιστρέφει:**
long


---


### getColumnGapRule {#getColumnGapRule}

| Όνομα | Περιγραφή |
| --- | --- |
| getColumnGapRule () | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός matrix· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

 **Επιστρέφει:**
int


---


### getHidePlaceholders {#getHidePlaceholders}

| Όνομα | Περιγραφή |
| --- | --- |
| getHidePlaceholders () | Απόκρυψη των σύμβολων κράτησης για κενά στοιχεία του matrix Προεπιλογή: false |

 **Επιστρέφει:**
boolean


---


### getMinColumnWidth {#getMinColumnWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getMinColumnWidth () | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως "Column Gap" ή "Gap Width") προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |

 **Επιστρέφει:**
long


---


### getRowCount {#getRowCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getRowCount () | Αριθμός γραμμών στο matrix |

 **Επιστρέφει:**
int


---


### getRowGap {#getRowGap}

| Όνομα | Περιγραφή |
| --- | --- |
| getRowGap () | Η τιμή του κάθετου διαστήματος μεταξύ των γραμμών ενός matrix· Εάν το RowGapRule είναι 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν το RowGapRule είναι 4 ("Multiple"), η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |

 **Επιστρέφει:**
long


---


### getRowGapRule {#getRowGapRule}

| Όνομα | Περιγραφή |
| --- | --- |
| getRowGapRule () | Ο τύπος του κάθετου διαστήματος μεταξύ των γραμμών ενός matrix· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

 **Επιστρέφει:**
int


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int, int) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)


---


### insertColumnAfter {#insertColumnAfter}

| Όνομα | Περιγραφή |
| --- | --- |
| insertColumnAfter (int) | Εισάγει μια νέα στήλη μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης μετά την οποία θα εισαχθεί μια νέα |

 **Επιστρέφει:**
void


---


### insertColumnBefore {#insertColumnBefore}

| Όνομα | Περιγραφή |
| --- | --- |
| insertColumnBefore (int) | Εισάγει μια νέα στήλη πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Δείκτης της στήλης πριν την οποία θα εισαχθεί μια νέα |

 **Επιστρέφει:**
void


---


### insertRowAfter {#insertRowAfter}

| Όνομα | Περιγραφή |
| --- | --- |
| insertRowAfter (int) | Εισάγει μια νέα γραμμή μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής μετά την οποία θα εισαχθεί μια νέα |

 **Επιστρέφει:**
void


---


### insertRowBefore {#insertRowBefore}

| Όνομα | Περιγραφή |
| --- | --- |
| insertRowBefore (int) | Εισάγει μια νέα γραμμή πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | int | Δείκτης της γραμμής πριν την οποία θα εισαχθεί μια νέα |

 **Επιστρέφει:**
void


---


### setBaseJustification {#setBaseJustification}

| Όνομα | Περιγραφή |
| --- | --- |
| setBaseJustification (int) | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center |

 **Επιστρέφει:**
void


---


### setColumnAlignment {#setColumnAlignment}

| Όνομα | Περιγραφή |
| --- | --- |
| setColumnAlignment (int, int) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Μηδενική δείκτης στήλης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

 **Επιστρέφει:**
void


---


### setColumnGap {#setColumnGap}

| Όνομα | Περιγραφή |
| --- | --- |
| setColumnGap (long) | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός matrix· Εάν το ColumnGapRule είναι 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν το ColumnGapRule είναι 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em increments. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |

 **Επιστρέφει:**
void


---


### setColumnGapRule {#setColumnGapRule}

| Όνομα | Περιγραφή |
| --- | --- |
| setColumnGapRule (int) | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός matrix· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

 **Επιστρέφει:**
void


---


### setColumnsAlignment {#setColumnsAlignment}

| Όνομα | Περιγραφή |
| --- | --- |
| setColumnsAlignment (int, long, int) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | int | Μηδενική δείκτης της πρώτης στήλης για ορισμό στοίχισης |
| columnsCount | long | Ο αριθμός των στηλών για ορισμό της στοίχισης |
| val | int | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |

 **Επιστρέφει:**
void


---


### setHidePlaceholders {#setHidePlaceholders}

| Όνομα | Περιγραφή |
| --- | --- |
| setHidePlaceholders (boolean) | Απόκρυψη των σύμβολων κράτησης για κενά στοιχεία του matrix Προεπιλογή: false |

 **Επιστρέφει:**
void


---


### setMinColumnWidth {#setMinColumnWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setMinColumnWidth (long) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το διάστημα του κενών (επίσης αναφέρεται ως "Column Gap" ή "Gap Width") προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού Matrix Column Spacing (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |

 **Επιστρέφει:**
void


---


### setRowGap {#setRowGap}

| Όνομα | Περιγραφή |
| --- | --- |
| setRowGap (long) | Η τιμή του κάθετου διαστήματος μεταξύ των γραμμών ενός matrix· Εάν το RowGapRule είναι 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου)· Εάν το RowGapRule είναι 4 ("Multiple"), η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |

 **Επιστρέφει:**
void


---


### setRowGapRule {#setRowGapRule}

| Όνομα | Περιγραφή |
| --- | --- |
| setRowGapRule (int) | Ο τύπος του κάθετου διαστήματος μεταξύ των γραμμών ενός matrix· Οι μονάδες κάθετου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathLimit](../mathlimit)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathMatrix](../mathmatrix)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathBlock](../mathblock)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathRadical](../mathradical)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathArray](../matharray)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathPhantom](../mathphantom)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathDelimiter](../mathdelimiter)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathNaryOperator](../mathnaryoperator)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathAccent](../mathaccent)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathBorderBox](../mathborderbox)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathGroupingCharacter](../mathgroupingcharacter)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathBar](../mathbar)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathSuperscriptElement](../mathsuperscriptelement)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathFunction](../mathfunction)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathSubscriptElement](../mathsubscriptelement)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathFraction](../mathfraction)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathematicalText](../mathematicaltext)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [BaseScript](../basescript)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathBox](../mathbox)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathElementBase](../mathelementbase)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void


---


### set_Item {#set_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| set_Item (int, int, [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Στοιχείο του matrix |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | int | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη στοιχείου |
| column | int | Ο δείκτης μηδενικής βάσης της στήλης για λήψη στοιχείου |

 **Επιστρέφει:**
void

---