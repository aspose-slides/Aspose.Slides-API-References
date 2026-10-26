---
title: SmartArtNode
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει κόμβο ενός αντικειμένου SmartArt
type: docs
url: /el/com.aspose.slides/smartartnode/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Αντιπροσωπεύει κόμβο ενός αντικειμένου SmartArt
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Επιστρέφει συλλογές όλων των θυγατρικών κόμβων του τρέχοντος κόμβου. |
| [getShapes()](#getShapes--) | Επιστρέφει συλλογές όλων των σχημάτων που σχετίζονται με τον κόμβο. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το πλαίσιο κειμένου του κόμβου. |
| [isAssistant()](#isAssistant--) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [getLevel()](#getLevel--) | Επιστρέφει το επίπεδο ένθεσης του κόμβου. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για τη σφαίρα κουκίδας ενός κόμβου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση μηδενικού βάσης του κόμβου μεταξύ των αδελφών κόμβων. |
| [setPosition(int value)](#setPosition-int-) | Επιστρέφει ή ορίζει τη θέση μηδενικού βάσης του κόμβου μεταξύ των αδελφών κόμβων. |
| [isHidden()](#isHidden--) | Επιστρέφει true εάν αυτός ο κόμβος είναι κρυφός στο μοντέλο δεδομένων. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [remove()](#remove--) | Αφαιρεί τον τρέχοντα κόμβο. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Επιστρέφει συλλογές όλων των θυγατρικών κόμβων του τρέχοντος κόμβου. Μόνο ανάγνωση [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Επιστρέφει:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Επιστρέφει συλλογές όλων των σχημάτων που σχετίζονται με τον κόμβο. Μόνο ανάγνωση [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Επιστρέφει:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Επιστρέφει το πλαίσιο κειμένου του κόμβου. Μόνο ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Επιστρέφει το επίπεδο ένθεσης του κόμβου. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για τη σφαίρα κουκίδας ενός κόμβου. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους διάταξης SmartArt που δεν παρέχουν σφαίρες κουκίδας για κόμβους. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Επιστρέφει ή ορίζει τη θέση μηδενικού βάσης του κόμβου μεταξύ των αδελφών κόμβων. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Επιστρέφει ή ορίζει τη θέση μηδενικού βάσης του κόμβου μεταξύ των αδελφών κόμβων. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Επιστρέφει true εάν αυτός ο κόμβος είναι κρυφός στο μοντέλο δεδομένων. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Επιστρέφει:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Αφαιρεί τον τρέχοντα κόμβο.

**Επιστρέφει:**
boolean - true εάν αφαιρεθεί επιτυχώς, αλλιώς false