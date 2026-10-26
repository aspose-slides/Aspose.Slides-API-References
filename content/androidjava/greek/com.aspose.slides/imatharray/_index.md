---
title: IMathArray
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή οποιαδήποτε μαθηματικά αντικείμενα
type: docs
url: /el/com.aspose.slides/imatharray/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή οποιαδήποτε μαθηματικά αντικείμενα

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArguments()](#getArguments--) | Το σύνολο των στοιχείων του πίνακα |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το επάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το επάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Μέγιστη Διανομή. Όταν είναι true, ο πίνακας κλιμακώνεται στο μέγιστο πλάτος του περιβάλλοντος στοιχείου (σελίδα, στήλη, κελί κλ.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Μέγιστη Διανομή. Όταν είναι true, ο πίνακας κλιμακώνεται στο μέγιστο πλάτος του περιβάλλοντος στοιχείου (σελίδα, στήλη, κελί κλ.). |
| [getObjectDistribution()](#getObjectDistribution--) | Κατανομή Αντικειμένου. Όταν είναι true, τα περιεχόμενα του πίνακα κλιμακώνονται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Κατανομή Αντικειμένου. Όταν είναι true, τα περιεχόμενα του πίνακα κλιμακώνονται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα |
| [getRowSpacing()](#getRowSpacing--) | Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση που η μονάδα μέτρησης είναι μισές γραμμές. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση που η μονάδα μέτρησης είναι μισές γραμμές. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Το σύνολο των στοιχείων του πίνακα

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Επιστρέφει:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το επάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Επιστρέφει:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το επάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Μέγιστη Διανομή. Όταν είναι true, ο πίνακας κλιμακώνεται στο μέγιστο πλάτος του περιβάλλοντος στοιχείου (σελίδα, στήλη, κελί κλ.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Επιστρέφει:**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Μέγιστη Διανομή. Όταν είναι true, ο πίνακας κλιμακώνεται στο μέγιστο πλάτος του περιβάλλοντος στοιχείου (σελίδα, στήλη, κελί κλ.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Κατανομή Αντικειμένου. Όταν είναι true, τα περιεχόμενα του πίνακα κλιμακώνονται στο μέγιστο πλάτος του αντικειμένου πίνακα.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Επιστρέφει:**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Κατανομή Αντικειμένου. Όταν είναι true, τα περιεχόμενα του πίνακα κλιμακώνονται στο μέγιστο πλάτος του αντικειμένου πίνακα.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Επιστρέφει:**
int

### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση που η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Επιστρέφει:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule ορίζεται σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή Multiple στην περίπτωση που η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |