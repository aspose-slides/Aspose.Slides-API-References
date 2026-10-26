---
title: Portion
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα τμήμα κειμένου μέσα σε μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/portion/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Αντιπροσωπεύει ένα τμήμα κειμένου μέσα σε μια παράγραφο κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Portion()](#Portion--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει τις ρητά ορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς εφαρμογή κληρονόμησης. |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. |
| [getField()](#getField--) | Επιστρέφει ένα πεδίο αυτού του τμήματος. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Μετατρέπει αυτό το τμήμα σε αυτόματα ενημερωμένο πεδίο. |
| [addField(String internalString)](#addField-java.lang.String-) | Μετατρέπει αυτό το τμήμα σε αυτόματα ενημερωμένο πεδίο. |
| [removeField()](#removeField--) | Μετατρέπει αυτό το τμήμα πεδίου σε απλό τμήμα. |
| [getRect()](#getRect--) | Λαμβάνει τις συντεταγμένες του ορθογωνίου που ορίζει τα όρια του τμήματος. |
| [getCoordinates()](#getCoordinates--) | Λαμβάνει τις συντεταγμένες της αρχής του τμήματος. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια του κειμένου. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση του κειμένου. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Portion.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει τις ρητά ορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς εφαρμογή κληρονόμησης. Μόνο για ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για το τρέχον τμήμα· τα κληρονομημένα δεδομένα δεν εφαρμόζονται.

Για να λάβετε τις αποτελεσματικές τιμές, συμπεριλαμβανομένων των κληρονομημένων, χρησιμοποιήστε τη μέθοδο [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Επιστρέφει ένα πεδίο αυτού του τμήματος. Μόνο για ανάγνωση [IField](../../com.aspose.slides/ifield).

**Επιστρέφει:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Μετατρέπει αυτό το τμήμα σε αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Μετατρέπει αυτό το τμήμα σε αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| internalString | java.lang.String | Εσωτερικό όνομα του FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Μετατρέπει αυτό το τμήμα πεδίου σε απλό τμήμα.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Λαμβάνει τις συντεταγμένες του ορθογωνίου που ορίζει τα όρια του τμήματος. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων και των κενών.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Λαμβάνει τις συντεταγμένες της αρχής του τμήματος. Η συντεταγμένη X του σημείου αντιπροσωπεύει την αρχή του τμήματος από τον πρώτο χαρακτήρα, συμπεριλαμβανομένου του αριστερού περιθωρίου. Η συντεταγμένη Y περιλαμβάνει το άνω περιθώριο.

**Επιστρέφει:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια του κειμένου. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση του κειμένου. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject