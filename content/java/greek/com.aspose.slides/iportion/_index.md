---
title: IPortion
second_title: Aspose.Slides for Java API Reference
description: Αντιπροσωπεύει ένα τμήμα κειμένου μέσα σε μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/iportion/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Αντιπροσωπεύει ένα τμήμα κειμένου μέσα σε μια παράγραφο κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει αντικείμενο μορφοποίησης που περιέχει ρητά ορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς να εφαρμοστεί κληρονομικότητα. |
| [getText()](#getText--) | Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. |
| [setText(String value)](#setText-java.lang.String-) | Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. |
| [getField()](#getField--) | Επιστρέφει ένα πεδίο αυτού του τμήματος. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο. |
| [addField(String internalString)](#addField-java.lang.String-) | Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο. |
| [removeField()](#removeField--) | Μετατρέπει αυτό το πεδίο τμήματος στο απλό τμήμα. |
| [getRect()](#getRect--) | Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιορίζει το τμήμα. |
| [getCoordinates()](#getCoordinates--) | Λαμβάνει τις συντεταγμένες της αρχής του τμήματος. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```


Επιστρέφει αντικείμενο μορφοποίησης που περιέχει ρητά ορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς να εφαρμοστεί κληρονομικότητα. Μόνο για ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για το τρέχον τμήμα· τα κληρονομικά δεδομένα δεν εφαρμόζονται.

Για να λάβετε τις αποτελεσματικές τιμές, συμπεριλαμβανομένων των κληρονομικών, χρησιμοποιήστε τη μέθοδο [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```


Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Λαμβάνει ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/Εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```


Επιστρέφει ένα πεδίο αυτού του τμήματος. Μόνο για ανάγνωση [IField](../../com.aspose.slides/ifield).

**Επιστρέφει:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```


Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Τύπος του πεδίου [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```


Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| internalString | java.lang.String | Εσωτερικό όνομα του FieldTypeEx String |

### removeField() {#removeField--}
```
public abstract void removeField()
```


Μετατρέπει αυτό το πεδίο τμήματος στο απλό τμήμα.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Λαμβάνει τις συντεταγμένες του ορθογωνίου που περιορίζει το τμήμα. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων των κενών.

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
java.awt.geom.Rectangle2D.Float - Ορθογώνιο που περιορίζει το τμήμα java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```


Λαμβάνει τις συντεταγμένες της αρχής του τμήματος. Η συντεταγμένη X του σημείου αντιπροσωπεύει την αρχή του τμήματος από τον πρώτο χαρακτήρα, συμπεριλαμβανομένης της αριστερής πλευρικής απόστασης. Η συντεταγμένη Y περιλαμβάνει την επάνω πλευρική απόσταση.

**Επιστρέφει:**
java.awt.geom.Point2D.Float - Συντεταγμένες της αρχής του τμήματος java.awt.geom.Point2D.Float