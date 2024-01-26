---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Java API Reference
description: Represents options that control how presentation should be saved to markdown.
type: docs
url: /com.aspose.slides/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Represents options that control how presentation should be saved to markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Methods

| Method | Description |
| --- | --- |
| [getExportType()](#getExportType--) | Specifies markdown specification to convert presentation. |
| [setExportType(int value)](#setExportType-int-) | Specifies markdown specification to convert presentation. |
| [getBasePath()](#getBasePath--) | Specifies the base path where document with resources will be saved. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specifies the base path where document with resources will be saved. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specifies folder name to save images. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specifies folder name to save images. |
| [getNewLineType()](#getNewLineType--) | Specifies whether the generated document should have new lines \\\\r(Macintosh) of \\\\n(Unix) or \\\\r\\\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Specifies whether the generated document should have new lines \\\\r(Macintosh) of \\\\n(Unix) or \\\\r\\\\n(Windows). |
| [getShowComments()](#getShowComments--) | Specifies whether the generated document should show comments or not. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Specifies whether the generated document should show comments or not. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Specifies whether the generated document should show number of each slide or not. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Specifies whether the generated document should show number of each slide or not. |
| [getFlavor()](#getFlavor--) | Specifies markdown specification to convert presentation. |
| [setFlavor(int value)](#setFlavor-int-) | Specifies markdown specification to convert presentation. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Specifies markdown specification to convert presentation. Default is  TextOnly .

**Returns:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Specifies markdown specification to convert presentation. Default is  TextOnly .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Specifies the base path where document with resources will be saved. Default is the current directory of the application.

**Returns:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Specifies the base path where document with resources will be saved. Default is the current directory of the application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Specifies folder name to save images. Default is  Images .

**Returns:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Specifies folder name to save images. Default is  Images .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Specifies whether the generated document should have new lines \\\\r(Macintosh) of \\\\n(Unix) or \\\\r\\\\n(Windows). Default is  Unix .

**Returns:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Specifies whether the generated document should have new lines \\\\r(Macintosh) of \\\\n(Unix) or \\\\r\\\\n(Windows). Default is  Unix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Specifies whether the generated document should show comments or not. Default is  false .

**Returns:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Specifies whether the generated document should show comments or not. Default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is  false .

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Specifies whether the generated document should show number of each slide or not. Default is  false .

**Returns:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Specifies whether the generated document should show number of each slide or not. Default is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Specifies markdown specification to convert presentation. Default is  Multi-markdown .

**Returns:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Specifies markdown specification to convert presentation. Default is  Multi-markdown .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

