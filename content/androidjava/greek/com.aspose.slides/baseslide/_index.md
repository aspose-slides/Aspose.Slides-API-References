---
title: BaseSlide
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τα κοινά δεδομένα για όλους τους τύπους διαφανειών.
type: docs
url: /el/com.aspose.slides/baseslide/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Αντιπροσωπεύει κοινά δεδομένα για όλους τους τύπους διαφανειών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapes()](#getShapes--) | Επιστρέφει τα σχήματα μιας διαφάνειας. |
| [getControls()](#getControls--) | Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. |
| [getName()](#getName--) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. |
| [getSlideId()](#getSlideId--) | Επιστρέφει το ID μιας διαφάνειας. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Καθορίζει εάν οι δύο εμφανίσεις του IBaseSlide είναι ίσες. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συνδέει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Συνδέει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
| [createThemeEffective()](#createThemeEffective--) | Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια. |
| [getCustomData()](#getCustomData--) | Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. |
| [getTimeline()](#getTimeline--) | Επιστρέφει το αντικείμενο χρονοδιάγραμμα της κίνησης. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες σχετικά με το πώς η καθορισμένη διαφάνεια προχωρά κατά τη διάρκεια μιας παρουσίασης. |
| [getBackground()](#getBackground--) | Επιστρέφει το φόντο της διαφάνειας. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Παρέχει εύκολη πρόσβαση στους περιέχοντες υπερσυνδέσμους. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει εάν τα σχήματα στη μητρική διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει εάν τα σχήματα στη μητρική διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Επιστρέφει τη διεπαφή IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Επιστρέφει τα σχήματα μιας διαφάνειας. Μόνο για ανάγνωση [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Επιστρέφει:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Επιστρέφει τη συλλογή των ελέγχων ActiveX σε μια διαφάνεια. Μόνο για ανάγνωση [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Επιστρέφει:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Επιστρέφει ή ορίζει το όνομα μιας διαφάνειας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Επιστρέφει το ID μιας διαφάνειας. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Καθορίζει εάν οι δύο εμφανίσεις του IBaseSlide είναι ίσες. Η επιστρεφόμενη τιμή υπολογίζεται βάσει της δομής της διαφάνειας και του στατικού περιεχομένου. Δύο διαφάνειες είναι ίσες εάν όλα τα σχήματα, τα στυλ, τα κείμενα, η κίνηση και άλλες ρυθμίσεις κ.λπ. είναι ίσα. Η σύγκριση δεν λαμβάνει υπόψη τις μοναδικές τιμές αναγνωριστικών, π.χ. SlideId και το δυναμικό περιεχόμενο, π.χ. την τρέχουσα τιμή ημερομηνίας σε Date Placeholder.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Το IBaseSlide προς σύγκριση με το τρέχον IBaseSlide. |

**Επιστρέφει:**
boolean -  **true**  εάν το συγκεκριμένο IBaseSlide είναι ίσο με το τρέχον IBaseSlide· διαφορετικά,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Συνδέει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Συνδέει τμήματα με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Επιστρέφει ένα αποτελεσματικό θέμα για αυτή τη διαφάνεια.

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Επιστρέφει τα προσαρμοσμένα δεδομένα της διαφάνειας. Μόνο για ανάγνωση [ICustomData](../../com.aspose.slides/icustomdata).

**Επιστρέφει:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Επιστρέφει το αντικείμενο χρονοδιάγραμμα κίνησης. Μόνο για ανάγνωση [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Επιστρέφει:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Επιστρέφει το αντικείμενο Transition που περιέχει πληροφορίες σχετικά με το πώς η καθορισμένη διαφάνεια προχωρά κατά τη διάρκεια μιας παρουσίασης. Μόνο για ανάγνωση [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Επιστρέφει:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Επιστρέφει το φόντο της διαφάνειας. Μόνο για ανάγνωση [IBackground](../../com.aspose.slides/ibackground).

**Επιστρέφει:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Παρέχει εύκολη πρόσβαση στους περιεχόμενους υπερσυνδέσμους. Μόνο για ανάγνωση [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Επιστρέφει:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Καθορίζει εάν τα σχήματα στη μητρική διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη μητρική διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Καθορίζει εάν τα σχήματα στη μητρική διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Για τη μητρική διαφάνεια αυτή η ιδιότητα επιστρέφει πάντα false. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Βρίσκει την πρώτη εμφάνιση ενός σχήματος με το καθορισμένο εναλλακτικό κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| altText | java.lang.String | Εναλλακτικό κείμενο. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - αντικείμενο Shape ή null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent\_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει τη διεπαφή IPresentation. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)