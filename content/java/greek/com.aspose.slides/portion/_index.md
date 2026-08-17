---
title: Portion
second_title: Aspose.Slides για το Java API Αναφορά
description: Αντιπροσωπεύει μια περιοχή κειμένου μέσα σε μια παράγραφο κειμένου.
type: docs
url: /el/com.aspose.slides/portion/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Αντιπροσωπεύει μια περιοχή κειμένου μέσα σε μια παράγραφο κειμένου.
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [Portion()](#Portion--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει ρητά ορισμένες ιδιότητες μορφοποίησης της περιοχής κειμένου χωρίς εφαρμογή κληρονομικότητας. |
| [getText()](#getText--) | Ανακτά ή ορίζει το απλό κείμενο μιας περιοχής. |
| [setText(String value)](#setText-java.lang.String-) | Ανακτά ή ορίζει το απλό κείμενο μιας περιοχής. |
| [getField()](#getField--) | Επιστρέφει ένα πεδίο αυτής της περιοχής. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Μετατρέπει αυτήν την περιοχή σε αυτόματα ενημερωμένο πεδίο. |
| [addField(String internalString)](#addField-java.lang.String-) | Μετατρέπει αυτήν την περιοχή σε αυτόματα ενημερωμένο πεδίο. |
| [removeField()](#removeField--) | Μετατρέπει αυτήν την περιοχή πεδίου σε απλή περιοχή. |
| [getRect()](#getRect--) | Ανάκτηση συντεταγμένων του ορθογωνίου που περιβάλλει την περιοχή. |
| [getCoordinates()](#getCoordinates--) | Ανάκτηση συντεταγμένων της αρχής της περιοχής. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός κειμένου. |
| [getPresentation()](#getPresentation--) | Επιστρέφει τη γονική παρουσίαση ενός κειμένου. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης Portion.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


Επιστρέφει το αντικείμενο μορφοποίησης που περιέχει ρητά ορισμένες ιδιότητες μορφοποίησης της περιοχής κειμένου χωρίς εφαρμογή κληρονομικότητας. Μόνο-ανάγνωση [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Το αντικείμενο μορφοποίησης περιέχει τις παραμέτρους μορφοποίησης που ορίζονται μόνο για την τρέχουσα περιοχή, τα κληρονομημένα δεδομένα δεν εφαρμόζονται.

Για να λάβετε τις αποτελεσματικές τιμές, συμπεριλαμβανομένων των κληρονομημένων, χρησιμοποιήστε τη μέθοδο [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


Ανακτά ή ορίζει το απλό κείμενο μιας περιοχής. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Επιστρέφει:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ανακτά ή ορίζει το απλό κείμενο μιας περιοχής. Ανάγνωση/εγγραφή String.

Τιμή: Το κείμενο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


Επιστρέφει ένα πεδίο αυτής της περιοχής. Μόνο-ανάγνωση [IField](../../com.aspose.slides/ifield).

**Επιστρέφει:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


Μετατρέπει αυτήν την περιοχή σε αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


Μετατρέπει αυτήν την περιοχή σε αυτόματα ενημερωμένο πεδίο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | Εσωτερικό όνομα του FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```


Μετατρέπει αυτήν την περιοχή πεδίου σε απλή περιοχή.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Ανάκτηση συντεταγμένων του ορθογωνίου που περιβάλλει την περιοχή. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στην περιοχή, συμπεριλαμβανομένων των κενών.

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
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```


Ανάκτηση συντεταγμένων της αρχής της περιοχής. Η συντεταγμένη X του σημείου αντιπροσωπεύει την αρχή της περιοχής από τον πρώτο χαρακτήρα, συμπεριλαμβανομένου του αριστερού περιθωρίου. Η συντεταγμένη Y περιλαμβάνει το άνω περιθώριο.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Επιστρέφει τη γονική διαφάνεια ενός κειμένου. Μόνο-ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επισ Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Επιστρέφει τη γονική παρουσίαση ενός κειμένου. Μόνο-ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επισ Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επισ Returns:**
com.aspose.slides.IDOMObject