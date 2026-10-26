---
title: SmartArtNode
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά κόμβο ενός αντικειμένου SmartArt
type: docs
url: /el/com.aspose.slides/smartartnode/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Αναπαριστά κόμβο ενός αντικειμένου SmartArt
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Επιστρέφει συλλογές όλων των θυγατρικών κόμβων του τρέχοντος κόμβου. |
| [getShapes()](#getShapes--) | Επιστρέφει συλλογές όλων των σχημάτων που συνδέονται με τον κόμβο. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το πλαίσιο κειμένου του κόμβου. |
| [isAssistant()](#isAssistant--) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Επιστρέφει ή ορίζει τον κόμβο ως βοηθό. |
| [getLevel()](#getLevel--) | Επιστρέφει το επίπεδο ενσωμάτωσης του κόμβου. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για τη σφαίρα σημειολογίου ενός κόμβου. |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών κόμβων. |
| [setPosition(int value)](#setPosition-int-) | Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών κόμβων. |
| [isHidden()](#isHidden--) | Επιστρέφει true αν αυτός ο κόμβος είναι κρυφός στον δεδομενικό μοντέλο. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που συνδέεται με τον τρέχοντα κόμβο. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που συνδέεται με τον τρέχοντα κόμβο. |
| [remove()](#remove--) | Καταργεί τον τρέχοντα κόμβο. |
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


Επιστρέφει συλλογές όλων των σχημάτων που συνδέονται με τον κόμβο. Μόνο ανάγνωση [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

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


Επιστρέφει το επίπεδο ενσωμάτωσης του κόμβου. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για τη σφαίρα σημειολογίου ενός κόμβου. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους διάταξης SmartArt που δεν παρέχουν σφαίρες σημειολογίου για κόμβους. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών κόμβων. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Επιστρέφει ή ορίζει τη θέση μηδενικής βάσης του κόμβου μεταξύ των αδερφών κόμβων. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Επιστρέφει true αν αυτός ο κόμβος είναι κρυφός στον δεδομενικό μοντέλο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που συνδέεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Επιστρέφει:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Επιστρέφει ή ορίζει τον τύπο διάταξης οργανωτικού διαγράμματος που συνδέεται με τον τρέχοντα κόμβο. Ανάγνωση/εγγραφή [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


Καταργεί τον τρέχοντα κόμβο.

**Επιστρέφει:**
boolean - true αν αφαιρέθηκε επιτυχώς, αλλιώς false