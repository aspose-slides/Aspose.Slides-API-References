---
title: LoadOptions
second_title: Aspose.Slides för Java API-referens
description: Gör det möjligt att ange ytterligare alternativ, såsom format eller standardteckensnitt, vid inläsning av en presentation.
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

Tillåter att specificera ytterligare alternativ (t.ex. format eller standardteckensnitt) vid inläsning av en presentation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Skapar nya standardladdningsalternativ. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Skapar nya laddningsalternativ. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Returnerar eller anger format för en presentation som ska läsas in. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Returnerar eller anger format för en presentation som ska läsas in. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returnerar eller anger standardteckensnitt som används om källteckensnittet inte hittas. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returnerar eller anger standardteckensnitt som används om källteckensnittet inte hittas. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte hittas. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte hittas. |
| [getPassword()](#getPassword--) | Hämtar eller anger lösenordet. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenordet. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. |
| [getWarningCallback()](#getWarningCallback--) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representerar alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller maximalt antal BLOB-byte i minnet. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representerar alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller maximalt antal BLOB-byte i minnet. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Anger källor för externa teckensnitt som ska användas av presentationen. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Anger källor för externa teckensnitt som ska användas av presentationen. |
| [getInterruptionToken()](#getInterruptionToken--) | Tokenen för att övervaka avbrottsförfrågningar. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Tokenen för att övervaka avbrottsförfrågningar. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Hämtar alternativ för kalkylblad. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Hämtar alternativ för kalkylblad. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Returnerar eller anger standardspråket för presentations-text. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Returnerar eller anger standardspråket för presentations-text. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Avgör om Aspose.Slides ska radera alla inbäddade binära objekt vid presentations-inläsning. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Avgör om Aspose.Slides ska radera alla inbäddade binära objekt vid presentations-inläsning. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Skapar nya standardladdningsalternativ.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Skapar nya laddningsalternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadFormat | int | Format för en presentation som ska läsas in. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Returnerar eller anger format för en presentation som ska läsas in. Läsa/skriva [LoadFormat](../../com.aspose.slides/loadformat).

**Returnerar:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Returnerar eller anger format för en presentation som ska läsas in. Läsa/skriva [LoadFormat](../../com.aspose.slides/loadformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Returnerar eller anger standardteckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

--------------------

> ```
> Följande exempel visar hur man ställer in standardteckensnitt för rendering av PowerPoint-presentation.
>  
>  // Använd laddningsalternativ för att definiera standardteckensnittet för vanlig text och asiatisk text
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Läs in presentationen
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generera miniatyr för slide
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generera PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generera XPS
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

Returnerar eller anger standardteckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Använd laddningsalternativ för att definiera standardteckensnittet för vanlig text och asiatisk text
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Läs in presentationen
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generera miniatyr för slide
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generera PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generera XPS
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

Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

**Returnerar:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Returnerar eller anger symbolteckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

**Returnerar:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Returnerar eller anger asiatisk teckensnitt som används om källteckensnittet inte hittas. Läsa/skriva String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Hämtar eller anger lösenordet. Läsa/skriva String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // arbeta med dekrypterad presentation
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

Hämtar eller anger lösenordet. Läsa/skriva String.

--------------------

> ```
> Följande exempel på kod visar hur man öppnar ett lösenordsskyddat PowerPoint-presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // arbeta med dekrypterad presentation
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

Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska läsas in från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska läsas in med korrekt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapens värde är true kan inte dokumentegenskaperna läsas in och ett undantag kastas. Läsa/skriva boolean.

**Returnerar:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska läsas in från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska läsas in med korrekt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapens värde är true kan inte dokumentegenskaperna läsas in och ett undantag kastas. Läsa/skriva boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. Läsa/skriva [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returnerar:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. Läsa/skriva [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Representerar alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att ställa in det bästa prestanda/minnesförbrukningsförhållandet för en viss miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. ett ljud, video eller själva presentationen.

**Returnerar:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Representerar alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att ställa in det bästa prestanda/minnesförbrukningsförhållandet för en viss miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. ett ljud, video eller själva presentationen.

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
> Följande exempel visar hur man anger anpassade teckensnitt som används med PowerPoint-presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
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
> Följande exempel visar hur man anger anpassade teckensnitt som används med PowerPoint-presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
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

Tokenen för att övervaka avbrottsförfrågningar.

--------------------

Denna token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-metoden på [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returnerar:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public           // This statement 
```

Tokenen för att övervaka avbrottsförfrågningar.

--------------------

Denna token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom inläsning eller sparande av presentation, avbryts genom att anropa [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)-metoden på [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. Läsa/skriva [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returnerar:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Returnerar eller anger återuppringnings-gränssnitt som hanterar inläsning av externa resurser. Läsa/skriva [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

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

Returnerar eller anger standardspråket för presentations-text. Läsa/skriva String.

--------------------

> ```
> Exempel:
>   
>  // Använd laddningsalternativ för att definiera standardtextkultur
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till ny rektangulär form med text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kontrollera språk för den första delen
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

Returnerar eller anger standardspråket för presentations-text. Läsa/skriva String.

--------------------

> ```
> Exempel:
>   
>  // Använd laddningsalternativ för att definiera standardtextkultur
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till ny rektangulär form med text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kontrollera språket för den första delen
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

Avgör om Aspose.Slides ska radera alla inbäddade binära objekt vid presentations-inläsning.

De inbäddade binära objekten:

Läsa/skriva boolean.

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

Avgör om Aspose.Slides ska radera alla inbäddade binära objekt vid presentations-inläsning.

De inbäddade binära objekten:

Läsa/skriva boolean.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |