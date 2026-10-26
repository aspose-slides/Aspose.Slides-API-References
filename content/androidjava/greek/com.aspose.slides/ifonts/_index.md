---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /el/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Αντιπροσωπεύει τη συλλογή γραμματοσειρών.
## Μεθόδους

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
| [getScriptFontMap()](#getScriptFontMap--) | Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών script στην παρουσίαση. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Λαμβάνει το όνομα της γραμματοσειράς που συνδέεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Αντιστοιχεί ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία ορίζει πώς θα αποδοθεί το κείμενο αυτού του script στην παρουσίαση. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών script στην παρουσίαση.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


Λαμβάνει το όνομα της γραμματοσειράς που συνδέεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να ανακτήσετε τη γραμματοσειρά που έχει οριστεί για το κυριλλικό σενάριο στο θέμα της παρουσίασης.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κώδικας script BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την αναγνώριση ενός συστήματος γραφής. |

**Επιστρέφει:**
java.lang.String - Το όνομα της γραμματοσειράς που χρησιμοποιείται για το συγκεκριμένο script, ή  null  αν το script δεν είναι ορισμένο.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Αντιστοιχεί ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία ορίζει πώς θα αποδοθεί το κείμενο αυτού του script στην παρουσίαση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να ορίσετε τη γραμματοσειρά για το αραβικό σενάριο σε "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κώδικας script BCP-47 (π.χ., "Arab", "Hebr", "Hans") που αναγνωρίζει το σύστημα γραφής. |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα ανατεθεί στο συγκεκριμένο script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να αφαιρέσετε τη αντιστοίχηση γραμματοσειράς για το εβραϊκό σενάριο:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κώδικας script BCP-47 της γραμματοσειράς του οποίου θα αφαιρεθεί η ρύθμιση. |