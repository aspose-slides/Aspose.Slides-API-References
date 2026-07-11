---
title: IPortion
second_title: Aspose.Slides για Android μέσω Java API
description: Αναπαριστά ένα τμήμα κειμένου μέσα σε μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/iportion/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Αναπαριστά ένα τμήμα κειμένου μέσα σε μία παράγραφο κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει τις ρητά καθορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς κληρονομική εφαρμογή. |
| [getText()](#getText--) | Αποκτά ή ορίζει το απλό κείμενο ενός τμήματος. |
| [setText(String value)](#setText-java.lang.String-) | Αποκτά ή ορίζει το απλό κείμενο ενός τμήματος. |
| [getField()](#getField--) | Επιστρέφει ένα πεδίο αυτού του τμήματος. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο. |
| [addField(String internalString)](#addField-java.lang.String-) | Μετατρέπει αυτό το τμήμα στο αυτόματα ενημερωμένο πεδίο. |
| [removeField()](#removeField--) | Μετατρέπει αυτό το τμήμα πεδίου σε απλό τμήμα. |
| [getRect()](#getRect--) | Λάβετε τις συντεταγμένες του ορθογωνίου που περιβάλλει το τμήμα. |
| [getCoordinates()](#getCoordinates--) | Λάβετε τις συντεταγμένες της έναρξης του τμήματος. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει τις ρητά καθορισμένες ιδιότητες μορφοποίησης του τμήματος κειμένου χωρίς κληρονομική εφαρμογή. Μόνο για ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για το τρέχον τμήμα· δεν εφαρμόζονται τα κληρονομικά δεδομένα.

Για να λάβετε τις αποτελεσματικές τιμές, συμπεριλαμβανομένων των κληρονομημένων, χρησιμοποιήστε τη μέθοδο [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Αποκτά ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Αποκτά ή ορίζει το απλό κείμενο ενός τμήματος. Ανάγνωση/εγγραφή String.

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

Μετατρέπει αυτό το τμήμα πεδίου σε απλό τμήμα.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Λάβετε τις συντεταγμένες του ορθογωνίου που περιβάλλει το τμήμα. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων των κενών.

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
android.graphics.RectF - Ορθογώνιο που περιβάλλει το τμήμα android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

Λάβετε τις συντεταγμένες της έναρξης του τμήματος. Η συντεταγμένη X του σημείου αντιπροσωπεύει την έναρξη του τμήματος από τον πρώτο χαρακτήρα, συμπεριλαμβανομένου του αριστερού περιθωρίου. Η συντεταγμένη Y περιλαμβάνει το επάνω περιθώριο.

**Επιστρέφει:**
android.graphics.PointF - Συντεταγμένες της έναρξης του τμήματος android.graphics.PointF