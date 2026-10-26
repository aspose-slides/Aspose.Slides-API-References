---
title: FontsLoader
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Κλάση για τη φόρτωση προσαρμοσμένων γραμματοσειρών που ορίζονται από τον χρήστη.
type: docs
url: /el/com.aspose.slides/fontsloader/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Κλάση για τη φόρτωση προσαρμοσμένων γραμματοσειρών που ορίζονται από τον χρήστη. Πρέπει να χρησιμοποιείται πριν από τη δημιουργία οποιωνδήποτε αντικειμένων παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Προσθέτει πρόσθετους φακέλους για την αναζήτηση γραμματοσειρών. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Προσθέτει γραμματοσειρά από τα δυαδικά δεδομένα |
| [getFontFolders()](#getFontFolders--) | Λαμβάνει φακέλους γραμματοσειρών. |
| [clearCache()](#clearCache--) | Αποδεσμεύει όλες τις προσαρμοσμένες γραμματοσειρές που ορίζονται από τον χρήστη |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Προσθέτει πρόσθετους φακέλους για την αναζήτηση γραμματοσειρών.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // folders to seek fonts
>  String[] folders = new String[] { dataDir };
>  // Load the custom font directory fonts
>  FontsLoader.loadExternalFonts(folders);
>  // Do Some work and perform presentation/slides rendering
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Clear Font Cachce
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| directories | java.lang.String[] | Κατάλογοι για την ανάγνωση πρόσθετων γραμματοσειρών. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Προσθέτει γραμματοσειρά από τα δυαδικά δεδομένα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Δεδομένα γραμματοσειράς |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Λαμβάνει φακέλους γραμματοσειρών. Επιστρέφει φακέλους που έχουν προστεθεί με τη μέθοδο LoadExternalFonts καθώς και φακέλους συστήματος

**Επιστρέφει:**
java.lang.String[] - πίνακας που περιέχει τα ονόματα των φακέλων
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Αποδεσμεύει όλες τις προσαρμοσμένες γραμματοσειρές που ορίζονται από τον χρήστη

--------------------

Αυτή η μέθοδος χρειάζεται να καθαρίσει την κρυφή μνήμη με τις προσαρμοσμένες γραμματοσειρές που ορίζονται από τον χρήστη.