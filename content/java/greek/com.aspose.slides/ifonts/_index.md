---
title: IFonts
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τη συλλογή γραμματοσειρών.
type: docs
url: /el/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Αντιπροσωπεύει τη συλλογή γραμματοσειρών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
| [getScriptFontMap()](#getScriptFontMap--) | Επιστρέφει ένα λεξικό όλων των ορισμών γραμματοσειρών script στην παρουσίαση. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Λαμβάνει το όνομα της γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Αποδίδει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, που ορίζει πώς θα αποτυπώνεται το κείμενο αυτού του script στην παρουσίαση. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/Εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Επιστρέφει ένα λεξικό όλων των ορισμών γραμματοσειρών script στην παρουσίαση.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - ένα λεξικό που αντιστοιχίζει τους κωδικούς script σε ονόματα γραμματοσειρών.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Λαμβάνει το όνομα της γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να ανακτήσετε τη γραμματοσειρά που έχει οριστεί για το κυριλλικό script στο θέμα της παρουσίασης.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την ταυτοποίηση ενός συστήματος γραφής. |

**Επιστρέφει:**
java.lang.String - Το όνομα της γραμματοσειράς που χρησιμοποιείται για το συγκεκριμένο script, ή  null  εάν το script δεν είναι ορισμένο.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Αποδίδει ένα όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, που ορίζει πώς θα αποτυπώνεται το κείμενο αυτού του script στην παρουσίαση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να ορίσετε τη γραμματοσειρά για το αραβικό script στο "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 (π.χ., "Arab", "Hebr", "Hans") που ταυτοποιεί το σύστημα γραφής. |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα αποδοθεί στο συγκεκριμένο script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να αφαιρέσετε την αντιστοίχηση γραμματοσειράς για το εβραϊκό script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 του οποίου η ρύθμιση γραμματοσειράς πρέπει να αφαιρεθεί. |