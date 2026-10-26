---
title: Theme
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα θέμα.
type: docs
url: /el/com.aspose.slides/theme/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Αντιπροσωπεύει ένα θέμα.
## Μεθόδοι

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Επιστρέφει το σχήμα χρωμάτων. |
| [getFontScheme()](#getFontScheme--) | Επιστρέφει το σχήμα γραμματοσειράς. |
| [getFormatScheme()](#getFormatScheme--) | Επιστρέφει το σχήμα μορφοποίησης σχήματος. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα θέματος με την κληρονόμηση εφαρμοσμένη. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Επιστρέφει το σχήμα χρωμάτων. Μόνο-ανάγνωση [IColorScheme](../../com.aspose.slides/icolorscheme).

**Επιστρέφει:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Επιστρέφει το σχήμα γραμματοσειράς. Μόνο-ανάγνωση [IFontScheme](../../com.aspose.slides/ifontscheme).

**Επιστρέφει:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Επιστρέφει το σχήμα μορφοποίησης σχήματος. Μόνο-ανάγνωση [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Επιστρέφει:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση. Μόνο-ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα θέματος με την κληρονόμηση εφαρμοσμένη.

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Ένα [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο-ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Έκδοση. Μόνο-ανάγνωση long.

**Επιστρέφει:**
long