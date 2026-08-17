---
title: ISmartArtNode
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά κόμβο ενός διαγράμματος SmartArt.
type: docs
url: /el/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Αναπαριστά κόμβο ενός διαγράμματος SmartArt.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Επιστρέφει τις συλλογές όλων των υποκόμβων του τρέχοντος κόμβου. |
| [getShapes()](#getShapes--) | Επιστρέφει τις συλλογές όλων των σχημάτων που σχετίζονται με τον κόμβο. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει ή ορίζει το κείμενο του κόμβου. |
| [isAssistant()](#isAssistant--) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [getLevel()](#getLevel--) | Επιστρέφει το επίπεδο εμφώλευσης του κόμβου. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για τη σφαίρα ενός κόμβου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών του. |
| [setPosition(int value)](#setPosition-int-) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών του. |
| [isHidden()](#isHidden--) | Επιστρέφει true εάν αυτός ο κόμβος είναι κρυπτός κόμβος στο μοντέλο δεδομένων. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. |
| [remove()](#remove--) | Αφαιρεί τον τρέχοντα κόμβο. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Επιστρέφει τις συλλογές όλων των υποκόμβων του τρέχοντος κόμβου. Μόνο ανάγνωση [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Επιστρέφει:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Επιστρέφει τις συλλογές όλων των σχημάτων που σχετίζονται με τον κόμβο. Μόνο ανάγνωση [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Επιστρέφει:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Επιστρέφει ή ορίζει το κείμενο του κόμβου. Μόνο ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Επιστρέφει το επίπεδο εμφώλευσης του κόμβου. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για τη σφαίρα ενός κόμβου. Σημείωση: μπορεί να επιστρέψει null για ορισμένα είδη διάταξης SmartArt που δεν παρέχουν σφαίρες για κόμβους. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών του. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών του. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Επιστρέφει true εάν αυτός ο κόμβος είναι κρυπτός κόμβος στο μοντέλο δεδομένων. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/Εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Επιστρέφει:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που σχετίζεται με τον τρέχοντα κόμβο. Ανάγνωση/Εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

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
boolean - true if removed succesfully, otherwise false.