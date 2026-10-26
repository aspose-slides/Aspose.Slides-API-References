---
title: FontSubstitutionInfo
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αυτή η δομή αντιπροσωπεύει τις πληροφορίες σχετικά με την αντικατάσταση της γραμματοσειράς όταν θα αποδοθεί.
type: docs
url: /el/com.aspose.slides/fontsubstitutioninfo/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Αυτή η δομή αντιπροσωπεύει τις πληροφορίες σχετικά με την αντικατάσταση της γραμματοσειράς όταν θα αποδοθεί.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Δημιουργεί μια παρουσία της κλάσης [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Υποδεικνύει το όνομα της πηγαίας γραμματοσειράς στην παρουσίαση. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Υποδεικνύει το όνομα της αντικατεστημένης γραμματοσειράς για την αρχική γραμματοσειρά. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Δημιουργεί μια παρουσία της κλάσης [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| originFontName | java.lang.String | Όνομα πηγαίας γραμματοσειράς στην παρουσίαση String |
| substFontName | java.lang.String | Όνομα αντικατεστημένης γραμματοσειράς για την αρχική γραμματοσειρά String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Υποδεικνύει το όνομα της πηγαίας γραμματοσειράς στην παρουσίαση. Μόνο για ανάγνωση String

**Επιστρέφει:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Υποδεικνύει το όνομα της αντικατεστημένης γραμματοσειράς για την αρχική γραμματοσειρά. Μόνο για ανάγνωση String

**Επιστρέφει:**
java.lang.String