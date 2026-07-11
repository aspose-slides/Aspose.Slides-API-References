---
title: IMathematicalText
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Μαθηματικό κείμενο
type: docs
url: /el/com.aspose.slides/imathematicaltext/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Μαθηματικό κείμενο

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Τιμή κειμένου |
| [setValue(String value)](#setValue-java.lang.String-) | Τιμή κειμένου |
| [getFormat()](#getFormat--) | Ιδιότητες μορφοποίησης κειμένου |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Τιμή κειμένου

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Επιστρέφει:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


Τιμή κειμένου

--------------------

> ```
> Example:
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
public abstract IPortionFormat getFormat()
```


Ιδιότητες μορφοποίησης κειμένου

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Επιστρέφει:**
[IPortionFormat](../../com.aspose.slides/iportionformat)