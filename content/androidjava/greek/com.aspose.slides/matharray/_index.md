---
title: MathArray
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή άλλων μαθηματικών αντικειμένων
type: docs
url: /el/com.aspose.slides/matharray/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Καθορίζει έναν κατακόρυφο πίνακα εξισώσεων ή άλλων μαθηματικών αντικειμένων

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί το καθορισμένο στοιχείο σε αυτό |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί τα καθορισμένα στοιχεία σε αυτό |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArguments()](#getArguments--) | Το σύνολο των στοιχείων του πίνακα |
| [getBaseJustification()](#getBaseJustification--) | Καθορίζει τη στοίχιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Καθορίζει τη στοίχιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Μέγιστη Κατανομή. Όταν είναι αληθές, ο πίνακας τοποθετείται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Μέγιστη Κατανομή. Όταν είναι αληθές, ο πίνακας τοποθετείται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.). |
| [getObjectDistribution()](#getObjectDistribution--) | Κατανομή Αντικειμένου. Όταν είναι αληθές, τα περιεχόμενα του πίνακα τοποθετούνται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Κατανομή Αντικειμένου. Όταν είναι αληθές, τα περιεχόμενα του πίνακα τοποθετούνται στο μέγιστο πλάτος του αντικειμένου πίνακα. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα. Προεπιλογή: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα. Προεπιλογή: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Απόσταση μεταξύ των σειρών ενός πίνακα. Χρησιμοποιείται μόνο όταν η RowSpacingRule έχει τιμή 3. Σε αυτή την περίπτωση η μονάδα μέτρησης είναι points ή, εάν είναι Multiple, η μονάδα μέτρησης είναι μισές γραμμές. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Απόσταση μεταξύ των σειρών ενός πίνακα. Χρησιμοποιείται μόνο όταν η RowSpacingRule έχει τιμή 3. Σε αυτή την περίπτωση η μονάδα μέτρησης είναι points ή, εάν είναι Multiple, η μονάδα μέτρησης είναι μισές γραμμές. |
| [getChildren()](#getChildren--) | Λαμβάνει στοιχεία παιδιών |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί το καθορισμένο στοιχείο σε αυτό

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο για τοποθέτηση στο πίνακα |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί τα καθορισμένα στοιχεία σε αυτό

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Στοιχεία για τοποθέτηση στο πίνακα |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final int getBaseJustification()
```

Καθορίζει τη στοίχιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

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
public final void setBaseJustification(int value)
```

Καθορίζει τη στοίχιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το πάνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

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
public final boolean getMaximumDistribution()
```

Μέγιστη Κατανομή. Όταν είναι αληθές, ο πίνακας τοποθετείται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.).

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
public final void setMaximumDistribution(boolean value)
```

Μέγιστη Κατανομή. Όταν είναι αληθές, ο πίνακας τοποθετείται στο μέγιστο πλάτος του περιέχοντος στοιχείου (σελίδα, στήλη, κελί κ.λπ.).

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
public final boolean getObjectDistribution()
```

Κατανομή Αντικειμένου. Όταν είναι αληθές, τα περιεχόμενα του πίνακα τοποθετούνται στο μέγιστο πλάτος του αντικειμένου πίνακα.

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
public final void setObjectDistribution(boolean value)
```

Κατανομή Αντικειμένου. Όταν είναι αληθές, τα περιεχόμενα του πίνακα τοποθετούνται στο μέγιστο πλάτος του αντικειμένου πίνακα.

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
public final int getRowSpacingRule()
```

Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα. Προεπιλογή: SingleLineGap

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
public final void setRowSpacingRule(int value)
```

Ο τύπος της κατακόρυφης απόστασης μεταξύ των στοιχείων του πίνακα. Προεπιλογή: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Απόσταση μεταξύ των σειρών ενός πίνακα. Χρησιμοποιείται μόνο όταν η RowSpacingRule είναι 3. Σε αυτή την περίπτωση η μονάδα μέτρησης είναι points ή, εάν είναι Multiple, η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

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
public final void setRowSpacing(long value)
```

Απόσταση μεταξύ των σειρών ενός πίνακα. Χρησιμοποιείται μόνο όταν η RowSpacingRule είναι 3. Σε αυτή την περίπτωση η μονάδα μέτρησης είναι points ή, εάν είναι Multiple, η μονάδα μέτρησης είναι μισές γραμμές. Προεπιλογή: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]