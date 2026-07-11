---
title: IXamlOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Επιλογές που ελέγχουν πώς αποθηκεύεται ένα έγγραφο XAML.
type: docs
url: /el/com.aspose.slides/ixamloptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Options that control how a XAML document is saved.

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [getOutputSaver()](#getOutputSaver--) | Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.

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
public abstract void setExportHiddenSlides(boolean value)
```


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν.

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
public abstract IXamlOutputSaver getOutputSaver()
```


Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver.

**Επιστρέφει:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Αντιπροσωπεύει μια υλοποίηση της διεπαφής IOutputSaver.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |