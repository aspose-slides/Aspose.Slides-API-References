---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει έναν ορισμό γραμματοσειράς.
type: docs
url: /el/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Αντιπροσωπεύει έναν ορισμό γραμματοσειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFontName()](#getFontName--) | Επιστρέφει το όνομα γραμματοσειράς. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Επιστρέφει το όνομα γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική γραμματοσειρά που χρησιμοποιείται. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Επιστρέφει το όνομα γραμματοσειράς. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Επιστρέφει το όνομα γραμματοσειράς, αντικαθιστώντας την αναφορά θέματος με την πραγματική γραμματοσειρά που χρησιμοποιείται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Θέμα από το οποίο θα ληφθεί το ονομασία γραμματοσειράς με θέμα. Εξαρτάται από τον καλούντα να παρέχει σωστή τιμή. |

**Επιστρέφει:**
java.lang.String - Όνομα γραμματοσειράς.