---
title: BulletFormat
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/bulletformat/
---
## BulletFormat κλάση

Αναπαριστά τις ιδιότητες μορφοποίησης κουκίδας παραγράφου.

### applyDefaultParagraphIndentsShifts {#applyDefaultParagraphIndentsShifts}

| Όνομα | Περιγραφή |
| --- | --- |
| applyDefaultParagraphIndentsShifts () | Ορίζει τις προεπιλεγμένες μετακινήσεις μη μηδενικές για το αποτελεσματικό paragraph Indent και MarginLeft όταν οι κουκίδες είναι ενεργοποιημένες (όπως κάνει το PowerPoint εάν ενεργοποιήσετε τις κουκίδες/αρίθμηση παραγράφων). Αν οι κουκίδες είναι απενεργοποιημένες, τότε απλώς επαναφέρει το paragraph Indent και MarginLeft (όπως κάνει το PowerPoint αν απενεργοποιήσετε τις κουκίδες/αρίθμηση παραγράφων). Οι μετακινήσεις των ενδιάμεσων αποστάσεων εφαρμόζονται σε σχέση με το τρέχον πλαίσιο κουκίδας - IBulletFormat.Type, .NumberedBulletStyle και FontHeight του πρώτου τμήματος. Οι μη μηδενικές μετακινήσεις ενδιάμεσων αποστάσεων εφαρμόζονται στο αποτελεσματικό Indent και MarginLeft της τρέχουσας παραγράφου (καθιστώντας τις τιμές αποτελέσματος τοπικές). |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| InvalidOperationException | Η κλήση αυτής της μεθόδου δεν έχει σημασία και ρίχνει InvalidOperationException στις παρακάτω περιπτώσεις: εάν το γονικό μορφοποιημένο αντικείμενο δεν είναι παράγραφος (π.χ. η κλήση ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() θα ρίξει εξαίρεση); ή εάν η παράγραφος δεν έχει προστεθεί σε καμία συλλογή ITextFrame.Paragraphs (πρέπει να προστεθεί πρώτα). |

---

### getChar {#getChar}

| Όνομα | Περιγραφή |
| --- | --- |
| getChar () | Επιστρέφει ή ορίζει το bullet char μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή char. |

**Επιστρέφει:**  
char

---

### getColor {#getColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getColor () | Επιστρέφει το χρωματικό φορμά μιας κουκίδας μιας παραγράφου χωρίς κληρονομικότητα. Μόνο για ανάγνωση IColorFormat. |

**Επιστρέφει:**  
[ColorFormat](../colorformat)

---

### getEffective {#getEffective}

| Όνομα | Περιγραφή |
| --- | --- |
| getEffective () | Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμοσμένη κληρονομικότητα. |

**Επιστρέφει:**  
BulletFormatEffectiveData

---

### getFont {#getFont}

| Όνομα | Περιγραφή |
| --- | --- |
| getFont () | Επιστρέφει ή ορίζει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή IFontData. |

**Επιστρέφει:**  
[FontData](../fontdata)

---

### getHeight {#getHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeight () | Επιστρέφει ή ορίζει το ύψος bullet μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float. Μια αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε σημεία και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του περιβάλλοντος κειμένου. |

**Επιστρέφει:**  
float

---

### getNumberedBulletStartWith {#getNumberedBulletStartWith}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberedBulletStartWith () | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή short. |

**Επιστρέφει:**  
short

---

### getNumberedBulletStyle {#getNumberedBulletStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getNumberedBulletStyle () | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή NumberedBulletStyle. |

**Επιστρέφει:**  
byte

---

### getPicture {#getPicture}

| Όνομα | Περιγραφή |
| --- | --- |
| getPicture () | Επιστρέφει την εικόνα που χρησιμοποιείται ως κουκίδα σε μια παράγραφο χωρίς κληρονομικότητα. Μόνο για ανάγνωση ISlidesPicture. |

**Επιστρέφει:**  
[Picture](../picture)

---

### getType {#getType}

| Όνομα | Περιγραφή |
| --- | --- |
| getType () | Επιστρέφει ή ορίζει τον τύπο bullet μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή BulletType. |

**Επιστρέφει:**  
byte

---

### getVersion {#getVersion}

| Όνομα | Περιγραφή |
| --- | --- |
| getVersion () |  |

**Επιστρέφει:**  
long

---

### isBulletHardColor {#isBulletHardColor}

| Όνομα | Περιγραφή |
| --- | --- |
| isBulletHardColor () | Καθορίζει αν το bullet έχει δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. NullableBool.True αν το bullet έχει δικό του χρώμα και NullableBool.False αν το bullet κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή NullableBool. |

**Επιστρέφει:**  
byte

---

### isBulletHardFont {#isBulletHardFont}

| Όνομα | Περιγραφή |
| --- | --- |
| isBulletHardFont () | Καθορίζει αν το bullet έχει δική του γραμματοσειρά ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. NullableBool.True αν το bullet έχει δική του γραμματοσειρά και NullableBool.False αν το bullet κληρονομεί γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή NullableBool. |

**Επιστρέφει:**  
byte

---

### setBulletHardColor {#setBulletHardColor}

| Όνομα | Περιγραφή |
| --- | --- |
| setBulletHardColor (byte) | Καθορίζει αν το bullet έχει δικό του χρώμα ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. NullableBool.True αν το bullet έχει δικό του χρώμα και NullableBool.False αν το bullet κληρονομεί χρώμα από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή NullableBool. |

**Επιστρέφει:**  
void

---

### setBulletHardFont {#setBulletHardFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setBulletHardFont (byte) | Καθορίζει αν το bullet έχει δική του γραμματοσειρά ή το κληρονομεί από το πρώτο τμήμα στην παράγραφο. NullableBool.True αν το bullet έχει δική του γραμματοσειρά και NullableBool.False αν το bullet κληρονομεί γραμματοσειρά από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή NullableBool. |

**Επιστρέφει:**  
void

---

### setChar {#setChar}

| Όνομα | Περιγραφή |
| --- | --- |
| setChar (char) | Επιστρέφει ή ορίζει το bullet char μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή char. |

**Επιστρέφει:**  
void

---

### setFont {#setFont}

| Όνομα | Περιγραφή |
| --- | --- |
| setFont ([FontData](../fontdata)) | Επιστρέφει ή ορίζει τη γραμματοσειρά bullet μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή IFontData. |

**Επιστρέφει:**  
void

---

### setHeight {#setHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setHeight (float) | Επιστρέφει ή ορίζει το ύψος bullet μιας παραγράφου χωρίς κληρονομικότητα. Η τιμή Float.NaN καθορίζει ότι το bullet κληρονομεί το ύψος από το πρώτο τμήμα στην παράγραφο. Ανάγνωση/εγγραφή float. Μια αρνητική τιμή ύψους σημαίνει ότι το ύψος δίνεται σε σημεία και μια θετική τιμή σημαίνει ότι το ύψος είναι ποσοστό του περιβάλλοντος κειμένου. |

**Επιστρέφει:**  
void

---

### setNumberedBulletStartWith {#setNumberedBulletStartWith}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberedBulletStartWith (short) | Επιστρέφει ή ορίζει τον πρώτο αριθμό που χρησιμοποιείται για ομάδα αριθμημένων κουκίδων χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή short. |

**Επιστρέφει:**  
void

---

### setNumberedBulletStyle {#setNumberedBulletStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberedBulletStyle (byte) | Επιστρέφει ή ορίζει το στυλ μιας αριθμημένης κουκίδας χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή NumberedBulletStyle. |

**Επιστρέφει:**  
void

---

### setType {#setType}

| Όνομα | Περιγραφή |
| --- | --- |
| setType (byte) | Επιστρέφει ή ορίζει τον τύπο bullet μιας παραγράφου χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή BulletType. |

**Επιστρέφει:**  
void

---