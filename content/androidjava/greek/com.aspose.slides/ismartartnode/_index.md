---
title: ISmartArtNode
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει κόμβο ενός διαγράμματος SmartArt.
type: docs
url: /el/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Αντιπροσωπεύει κόμβο ενός διαγράμματος SmartArt.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Επιστρέφει συλλογές όλων των υποκόμβων του τρέχοντος κόμβου. |
| [getShapes()](#getShapes--) | Επιστρέφει συλλογές όλων των σχήματος που σχετίζονται με το κόμβο. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει ή ορίζει το κείμενο του κόμβου. |
| [isAssistant()](#isAssistant--) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [getLevel()](#getLevel--) | Επιστρέφει το επίπεδο ένθεσης του κόμβου. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για τη σφαίρα του κόμβου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών. |
| [setPosition(int value)](#setPosition-int-) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών. |
| [isHidden()](#isHidden--) | Επιστρέφει true εάν αυτός ο κόμβος είναι κρυφός στο μοντέλο δεδομένων. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [remove()](#remove--) | Αφαιρεί τον τρέχοντα κόμβο. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Επιστρέφει συλλογές όλων των υποκόμβων του τρέχοντος κόμβου. Μόνο-ανάγνωση [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Επιστρέφει:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Επιστρέφει συλλογές όλων των σχήματος που σχετίζονται με το κόμβο. Μόνο-ανάγνωση [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Επιστρέφει:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Επιστρέφει ή ορίζει το κείμενο του κόμβου. Μόνο-ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Επιστρέφει το επίπεδο ένθεσης του κόμβου. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για τη σφαίρα του κόμβου. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους διάταξης SmartArt που δεν παρέχουν σφαίρες για κόμβους. Μόνο-ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Επιστρέφει true εάν αυτός ο κόμβος είναι κρυφός στο μοντέλο δεδομένων. Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Επιστρέφει:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Αφαιρεί τον τρέχοντα κόμβο.

**Επιστρέφει:**
boolean - true εάν αφαιρεθεί επιτυχώς, αλλιώς false.