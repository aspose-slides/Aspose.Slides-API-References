---
title: IMathArray
second_title: Αναφορά API Aspose.Slides για Java
description: Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή οποιωνδήποτε μαθηματικών αντικειμένων
type: docs
url: /el/com.aspose.slides/imatharray/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή οποιωνδήποτε μαθηματικών αντικειμένων

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
```
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Το σύνολο των στοιχείων του πίνακα |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το γύρω κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το γύρω κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Μέγιστη κατανομή. Όταν αληθές, ο πίνακα διανέμεται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Μέγιστη κατανομή. Όταν αληθές, ο πίνακα διανέμεται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.). |
| [getObjectDistribution()](#getObjectDistribution--) | Κατανομή αντικειμένου. Όταν αληθές, τα περιεχόμενα του πίνακα διανέμονται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Κατανομή αντικειμένου. Όταν αληθές, τα περιεχόμενα του πίνακα διανέμονται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα |
| [getRowSpacing()](#getRowSpacing--) | Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή, αν είναι Multiple, η μονάδα είναι μισές γραμμές. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή, αν είναι Multiple, η μονάδα είναι μισές γραμμές. |
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

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το γύρω κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το γύρω κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```


Μέγιστη κατανομή. Όταν αληθές, ο πίνακα διανέμεται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```


Μέγιστη κατανομή. Όταν αληθές, ο πίνακα διανέμεται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```


Κατανομή αντικειμένου. Όταν αληθές, τα περιεχόμενα του πίνακα διανέμονται στο μέγιστο πλάτος του αντικειμένου πίνακα.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```


Κατανομή αντικειμένου. Όταν αληθές, τα περιεχόμενα του πίνακα διανέμονται στο μέγιστο πλάτος του αντικειμένου πίνακα.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
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

**Returns:**
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```


Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή, αν είναι Multiple, η μονάδα είναι μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Returns:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```


Απόσταση μεταξύ των γραμμών ενός πίνακα. Χρησιμοποιείται μόνο όταν το RowSpacingRule είναι ορισμένο σε 3. Στην περίπτωση αυτή η μονάδα μέτρησης είναι σημεία ή, αν είναι Multiple, η μονάδα είναι μισές γραμμές. Προεπιλογή: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |