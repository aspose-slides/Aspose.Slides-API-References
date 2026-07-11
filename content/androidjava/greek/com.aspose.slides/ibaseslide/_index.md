---
title: IBaseSlide
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τα κοινά δεδομένα για όλα τα είδη διαφανειών.
type: docs
url: /el/com.aspose.slides/ibaseslide/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Αναπαριστά τα κοινά δεδομένα για όλα τα είδη διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapes()](#getShapes--) | Επιστρέφει τα σχήματα μιας διαφάνειας. |
| [getControls()](#getControls--) | Επιστρέφει τη συλλογή των στοιχείων ελέγχου ActiveX σε μια διαφάνεια. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. |
| [getSlideId()](#getSlideId--) | Επιστρέφει το αναγνωριστικό (ID) μιας διαφάνειας. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. |
| [getTimeline()](#getTimeline--) | Επιστρέφει το αντικείμενο του χρονοδιαγράμματος κίνησης. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Επιστρέφει το αντικείμενο TransitionEx που περιέχει πληροφορίες σχετικά με τον τρόπο προόδου της συγκεκριμένης διαφάνειας κατά τη διάρκεια μιας παρουσίασης. |
| [getBackground()](#getBackground--) | Επιστρέφει το φόντο της διαφάνειας. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Εντοπίζει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τα τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Καθορίζει εάν τα δύο αντικείμενα IBaseSlide είναι ίσα. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο για ανάγνωση [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Επιστρέφει:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Επιστρέφει τη συλλογή των στοιχείων ελέγχου ActiveX σε μια διαφάνεια. Μόνο για ανάγνωση [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Επιστρέφει:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Επιστρέφει το αναγνωριστικό (ID) μιας διαφάνειας. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο για ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Επιστρέφει το αντικείμενο του χρονοδιαγράμματος κίνησης. Μόνο για ανάγνωση [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Επιστρέφει:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Επιστρέφει το αντικείμενο TransitionEx που περιέχει πληροφορίες σχετικά με τον τρόπο προόδου της συγκεκριμένης διαφάνειας κατά τη διάρκεια μιας παρουσίασης. Μόνο για ανάγνωση [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Επιστρέφει:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Επιστρέφει το φόντο της διαφάνειας. Μόνο για ανάγνωση [IBackground](../../com.aspose.slides/ibackground).

**Επιστρέφει:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Παρέχει εύκολη πρόσβαση στους ενσωματωμένους υπερσυνδέσμους. Μόνο για ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Καθορίζει αν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη δική της κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Καθορίζει αν τα σχήματα στη κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη δική της κύρια διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Εντοπίζει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| altText | java.lang.String | Εναλλακτικό κείμενο. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - αντικείμενο ShapeEx ή null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Ενώνει τα τμήματα κειμένου με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Καθορίζει εάν τα δύο αντικείμενα IBaseSlide είναι ίσα. Η τιμή επιστροφής υπολογίζεται βάσει της δομής και του στατικού περιεχομένου της διαφάνειας. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, οι κινήσεις και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές ταυτοτήτων, π.χ. SlideId, καθώς και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα ημερομηνία σε θέση ημερομηνίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Το IBaseSlide προς σύγκριση με το τρέχον IBaseSlide. |

**Επιστρέφει:**
boolean - **true** εάν το καθορισμένο IBaseSlide είναι ίσο με το τρέχον IBaseSlide· διαφορετικά, **false**.