---
title: IMathGroupingCharacter
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Καθορίζει ένα σύμβολο ομαδοποίησης πάνω ή κάτω από μια έκφραση, συνήθως για να τονίσει τη σχέση μεταξύ των στοιχείων
type: docs
url: /el/com.aspose.slides/imathgroupingcharacter/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Καθορίζει ένα σύμβολο ομαδοποίησης πάνω ή κάτω από μια έκφραση, συνήθως για να τονίσει τη σχέση μεταξύ των στοιχείων

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
>  ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getCharacter()](#getCharacter--) | Προεπιλεγμένη τιμή χαρακτήρα ομαδοποίησης: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Προεπιλεγμένη τιμή χαρακτήρα ομαδοποίησης: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Θέση του χαρακτήρα ομαδοποίησης. |
| [setPosition(int value)](#setPosition-int-) | Θέση του χαρακτήρα ομαδοποίησης. |
| [getVerticalJustification()](#getVerticalJustification--) | Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Προεπιλεγμένη τιμή χαρακτήρα ομαδοποίησης: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω παρένθεση
> ```

**Επιστρέφει:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Προεπιλεγμένη τιμή χαρακτήρα ομαδοποίησης: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω παρένθεση
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Θέση του χαρακτήρα ομαδοποίησης. Προεπιλογή: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```


**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Θέση του χαρακτήρα ομαδοποίησης. Προεπιλογή: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, VerticalJustification της Top σημαίνει ότι το επάνω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Επιστρέφει:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, VerticalJustification της Top σημαίνει ότι το επάνω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |