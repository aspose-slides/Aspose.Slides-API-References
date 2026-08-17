---
title: MathematicalText
second_title: Aspose.Slides για Java API Αναφορά
description: Μαθηματικό κείμενο
type: docs
url: /el/com.aspose.slides/mathematicaltext/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Μαθηματικό κείμενο

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Constructors

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Προεπιλεγμένος κατασκευαστής (δημιουργία τιμής String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Δημιουργία MathText με ένα σύμβολο |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Δημιουργία MathematicalText από κείμενο |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Δημιουργία MathematicalText από κείμενο και ρυθμίσεις μορφοποίησης |
## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Τιμή κειμένου |
| [setValue(String value)](#setValue-java.lang.String-) | Τιμή κειμένου |
| [getFormat()](#getFormat--) | Ιδιότητες μορφοποίησης κειμένου |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Προεπιλεγμένος κατασκευαστής (δημιουργία τιμής String.Empty)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Δημιουργία MathText με ένα σύμβολο

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathSymbol | char | ένα σύμβολο |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Δημιουργία MathematicalText από κείμενο

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | τιμή κειμένου |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Δημιουργία MathematicalText από κείμενο και ρυθμίσεις μορφοποίησης

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | τιμή κειμένου |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | ρυθμίσεις μορφοποίησης κειμένου |

### getValue() {#getValue--}
```
public final String getValue()
```


Τιμή κειμένου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Επιστρέφει:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Τιμή κειμένου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Ιδιότητες μορφοποίησης κειμένου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]