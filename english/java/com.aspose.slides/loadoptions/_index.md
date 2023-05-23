---
title: LoadOptions
second_title: Aspose.Slides for Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
weight: 292
url: /java/com.aspose.slides/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Allows to specify additional options (such as format or default font) when loading a presentation.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Creates new default load options. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Creates new load options. |
## Methods

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Returns or sets format of a presentation to load. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Returns or sets format of a presentation to load. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returns or sets Regular font used in case source font is not found. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returns or sets Regular font used in case source font is not found. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Returns or sets Symbol font used in case source font is not found. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Returns or sets Symbol font used in case source font is not found. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Returns or sets Asian font used in case source font is not found. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Returns or sets Asian font used in case source font is not found. |
| [getPassword()](#getPassword--) | Gets or sets the password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | This property makes sense, if presentation file is password protected. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | This property makes sense, if presentation file is password protected. |
| [getWarningCallback()](#getWarningCallback--) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specifies sources for external fonts to be used by the presentation. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specifies sources for external fonts to be used by the presentation. |
| [getInterruptionToken()](#getInterruptionToken--) | The token to monitor for interruption requests. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | The token to monitor for interruption requests. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Returns or sets callback interface which manages external resources loading. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Returns or sets callback interface which manages external resources loading. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Gets options for spreadsheets. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Gets options for spreadsheets. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Creates new default load options.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```


Creates new load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadFormat | int | Format of a presentation to load. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Returns or sets format of a presentation to load. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```


Returns or sets format of a presentation to load. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Returns or sets Regular font used in case source font is not found. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Returns or sets Regular font used in case source font is not found. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


Returns or sets Symbol font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


Returns or sets Symbol font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


Returns or sets Asian font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


Returns or sets Asian font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // work with decrypted presentation
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // work with decrypted presentation
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Returns:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Returns:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```


Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


The token to monitor for interruption requests.

--------------------

This token manages the whole [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) method of the [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returns:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


The token to monitor for interruption requests.

--------------------

This token manages the whole [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) method of the [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```


Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returns:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Returns:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

