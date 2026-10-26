---
title: LoadOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att ange ytterligare alternativ såsom format eller standardteckensnitt när en presentation laddas.
type: docs
url: /sv/com.aspose.slides/loadoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Tillåter att ange ytterligare alternativ (såsom format eller standardteckensnitt) när en presentation laddas.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Creates new default load options. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Creates new load options. |
## Metoder

| Metod | Beskrivning |
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
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Returns or sets the default language for presentation text. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Returns or sets the default language for presentation text. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Skapar nya standardinläsningsalternativ.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```


Skapar nya inläsningsalternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadFormat | int | Format för en presentation som ska laddas. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Returnerar eller anger format för en presentation som ska laddas. Läs/skriv [LoadFormat](../../com.aspose.slides/loadformat).

**Returnerar:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```


Returnerar eller anger format för en presentation som ska laddas. Läs/skriv [LoadFormat](../../com.aspose.slides/loadformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Returnerar eller anger vanligt teckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Returnerar eller anger vanligt teckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

**Returnerar:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

**Returnerar:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte finns. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar eller anger lösenordet. Läs/skriv String.

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

Värde: Lösenordet.

**Returnerar:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Hämtar eller anger lösenordet. Läs/skriv String.

--------------------

> ```
> Följande exempel visar hur man öppnar ett lösenordsskyddat PowerPoint-presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // arbeta med avkrypterad presentation
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Värde: Lösenordet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska laddas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska laddas med rätt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är publika och egenskapens värde är true kan dokumentegenskaperna inte laddas och ett undantag kommer att kastas. Läs/skriv boolean.

**Returnerar:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska laddas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska laddas med rätt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är publika och egenskapens värde är true kan dokumentegenskaperna inte laddas och ett undantag kommer att kastas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Returnerar eller anger ett objekt som tar emot varningar och beslutar om inläsningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returnerar:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Returnerar eller anger ett objekt som tar emot varningar och beslutar om inläsningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs) hanteringsbeteende, såsom användning av temporära filer eller maximalt antal BLOB-bytes i minnet. Dessa alternativ är avsedda att optimera prestanda/minnesanvändningsförhållandet för en specifik miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data som lagras som en enda enhet – t.ex. kan ett BLOB vara ett ljud, en video eller själva presentationen.

**Returnerar:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs) hanteringsbeteende, såsom användning av temporära filer eller maximalt antal BLOB-bytes i minnet. Dessa alternativ är avsedda att optimera prestanda/minnesanvändningsförhållandet för en specifik miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data som lagras som en enda enhet – t.ex. kan ett BLOB vara ett ljud, en video eller själva presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //arbeta med presentationen
>  //CustomFont1, CustomFont2 samt teckensnitt från assets\fonts & global\fonts mappar och deras undermappar är tillgängliga för presentationen
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```


Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //arbeta med presentationen
>  //CustomFont1, CustomFont2 samt teckensnitt från assets\fonts & global\fonts mappar och deras undermappar är tillgängliga för presentationen
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


Token för att övervaka avbrottsförfrågningar.

--------------------

Detta token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom inladdning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-metoden på [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returnerar:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


Token för att övervaka avbrottsförfrågningar.

--------------------

Detta token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom inladdning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-metoden på [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```


Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. Läs/skriv [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returnerar:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. Läs/skriv [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


Hämtar alternativ för kalkylblad. Till exempel påverkar dessa alternativ beräkning av formler för diagram.

**Returnerar:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Hämtar alternativ för kalkylblad. Till exempel påverkar dessa alternativ beräkning av formler för diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```


Returnerar eller anger standardspråket för presentationstext. Läs/skriv String.

--------------------

> ```
> Example:
>   
>  // Använd inläsningsalternativ för att definiera standardspråket för text
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till ny rektangelform med text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kontrollera första delens språk
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```


Returnerar eller anger standardspråket för presentationstext. Läs/skriv String.

--------------------

> ```
> Example:
>   
>  // Använd inläsningsalternativ för att definiera standardspråket för text
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till ny rektangelform med text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kontrollera första delens språk
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```


Bestämmer om Aspose.Slides ska ta bort alla inbäddade binära objekt under inläsning av presentation.

Typerna av de inbäddade binära objekten:

Läs/skriv boolean.

--------------------

> ```
> Följande exempel visar hur man laddar presentationen utan några inbäddade binära objekt.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Standard är **false**.

**Returnerar:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```


Bestämmer om Aspose.Slides ska ta bort alla inbäddade binära objekt under inläsning av presentation.

Typerna av de inbäddade binära objekten:

Läs/skriv boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |