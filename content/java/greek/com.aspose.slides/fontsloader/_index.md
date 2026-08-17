---
title: FontsLoader
second_title: Αναφορά API του Aspose.Slides για Java
description: Κατηγορία για τη φόρτωση προσαρμοσμένων γραμματοσειρών που ορίζονται από το χρήστη.
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

Κατηγορία για τη φόρτωση προσαρμοσμένων γραμματοσειρών που ορίζονται από το χρήστη. Πρέπει να χρησιμοποιηθεί πριν από τη δημιουργία οποιωνδήποτε αντικειμένων παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adds additional folders to seek fonts. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adds font from the binary data |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Προσθέτει επιπλέον φακέλους για την αναζήτηση γραμματοσειρών.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // φάκελοι για την αναζήτηση γραμματοσειρών
>  String[] folders = new String[] { dataDir };
>  // Φόρτωση των γραμματοσειρών του προσαρμοσμένου καταλόγου
>  FontsLoader.loadExternalFonts(folders);
>  // Κάντε κάποια εργασία και εκτελέστε απόδοση παρουσίασης/διαφανειών
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Καθαρίστε την προσωρινή μνήμη γραμματοσειρών
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| directories | java.lang.String[] | Directories to read additional fonts. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Προσθέτει γραμματοσειρά από τα δυαδικά δεδομένα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Font's data |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Gets font folders. Επιστρέφει φακέλους που έχουν προστεθεί με τη μέθοδο LoadExternalFonts καθώς και φακέλους γραμματοσειρών του συστήματος

**Επιστρέφει:**
java.lang.String[] - πίνακας που περιέχει τα ονόματα των φακέλων
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Releases all custom fonts defined by user

--------------------

Αυτή η μέθοδος χρειάζεται να καθαρίσει την προσωρινή μνήμη με τις προσαρμοσμένες γραμματοσειρές που ορίζονται από το χρήστη.