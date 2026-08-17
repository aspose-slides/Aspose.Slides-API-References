---
title: Fonts
second_title: Aspose.Slides για Java – Αναφορά API
description: Συλλογή γραμματοσειρών.
type: docs
url: /el/com.aspose.slides/fonts/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Συλλογή γραμματοσειρών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Επιστρέφει ένα λεξικό με όλους τους ορισμούς γραμματοσειρών script στην παρουσίαση. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Αποκτά το όνομα γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Αναθέτει όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία καθορίζει πώς θα εμφανίζεται το κείμενο αυτής της γραφής στην παρουσίαση. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος. |
| [getLatinFont()](#getLatinFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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
public final String getScriptFont(String script)
```

Αποκτά το όνομα γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από το θέμα της παρουσίασης.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 (π.χ., "Latn", "Cyrl", "Jpan") που χρησιμοποιείται για την ταυτοποίηση ενός συστήματος γραφής. |

**Επιστρέφει:**
java.lang.String - Το όνομα της γραμματοσειράς που χρησιμοποιείται για το συγκεκριμένο script, ή  null  αν το script δεν είναι ορισμένο.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Αναθέτει όνομα γραμματοσειράς σε μια συγκεκριμένη ετικέτα script, η οποία καθορίζει πώς θα εμφανίζεται το κείμενο αυτής της γραφής στην παρουσίαση.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 (π.χ., "Arab", "Hebr", "Hans") που προσδιορίζει το σύστημα γραφής. |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα αντιστοιχιστεί στο καθορισμένο script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Αφαιρεί τη ρύθμιση γραμματοσειράς που σχετίζεται με μια συγκεκριμένη ετικέτα script από τη συλλογή γραμματοσειρών του θέματος.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| script | java.lang.String | Ο κωδικός script BCP-47 του οποίου η ρύθμιση γραμματοσειράς πρέπει να αφαιρεθεί. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά Latin. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά East Asian. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Επιστρέφει:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά complex script. Ανάγνωση/εγγραφή [IFontData](../../com.aspose.slides/ifontdata).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |