---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά έναν ορισμό γραμματοσειράς.
type: docs
url: /el/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Αναπαριστά έναν ορισμό γραμματοσειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontName()](#getFontName--) | Επιστρέφει το όνομα της γραμματοσειράς. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική γραμματοσειρά που χρησιμοποιείται. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Επιστρέφει το όνομα της γραμματοσειράς. Μόνο-ανάγνωση String.

**Επιστρέφει:** 
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Επιστρέφει το όνομα της γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική γραμματοσειρά που χρησιμοποιείται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Θέμα από το οποίο πρέπει να ληφθεί το όνομα γραμματοσειράς του θέματος. Εξαρτάται από τον καλούντα να παρέχει μια σωστή τιμή. |

**Επιστρέφει:**
java.lang.String - Όνομα γραμματοσειράς.