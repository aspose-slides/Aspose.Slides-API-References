---
title: IMathGroupingCharacter
second_title: Αναφορά API του Aspose.Slides για Java
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
> ```
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getCharacter()](#getCharacter--) | Grouping Character προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET) |
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


Grouping Character προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω Παρένθεση
> ```

**Επιστρέφει:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Grouping Character προεπιλεγμένη τιμή: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Κάτω Παρένθεση
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


Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η VerticalJustification του Top δηλώνει ότι το επάνω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom όταν Position=Top, και Top όταν Position=Bottom

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


Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η VerticalJustification του Top δηλώνει ότι το επάνω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom όταν Position=Top, και Top όταν Position=Bottom

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