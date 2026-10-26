---
title: XamlOptions
second_title: Aspose.Slides για την Αναφορά API της Java
description: Επιλογές που ελέγχουν πώς αποθηκεύεται ένα έγγραφο XAML.
type: docs
url: /el/com.aspose.slides/xamloptions/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Επιλογές που ελέγχουν πώς αποθηκεύεται ένα έγγραφο XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Δημιουργεί το στιγμιότυπο XamlOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. |
| [getOutputSaver()](#getOutputSaver--) | Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Δημιουργεί το στιγμιότυπο XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver.

**Επιστρέφει:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |