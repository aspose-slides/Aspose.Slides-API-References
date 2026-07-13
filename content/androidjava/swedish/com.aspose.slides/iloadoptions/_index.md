---
title: ILoadOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att ange ytterligare alternativ, såsom format eller standardtypsnitt, när en presentation laddas.
type: docs
url: /sv/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Tillåter att ange ytterligare alternativ (såsom format eller standardtypsnitt) när en presentation laddas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Returnerar eller anger formatet för en presentation som ska laddas. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Returnerar eller anger formatet för en presentation som ska laddas. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returnerar eller anger Regular-typsnitt som används om kälttypsnittet inte hittas. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returnerar eller anger Regular-typsnitt som används om kälttypsnittet inte hittas. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Returnerar eller anger Symbol-typsnitt som används om kälttypsnittet inte hittas. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Returnerar eller anger Symbol-typsnitt som används om kälttypsnittet inte hittas. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Returnerar eller anger Asian-typsnitt som används om kälttypsnittet inte hittas. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Returnerar eller anger Asian-typsnitt som används om kälttypsnittet inte hittas. |
| [getPassword()](#getPassword--) | Hämtar eller anger lösenordet. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenordet. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad. |
| [getWarningCallback()](#getWarningCallback--) | Returnerar eller anger ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returnerar eller anger ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller max antal BLOB-bytes i minnet. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller max antal BLOB-bytes i minnet. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Anger källor för externa typsnitt som ska användas av presentationen. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Anger källor för externa typsnitt som ska användas av presentationen. |
| [getInterruptionToken()](#getInterruptionToken--) | Tokenet för att övervaka avbrottsförfrågningar. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Tokenet för att övervaka avbrottsförfrågningar. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Returnerar eller anger callback-gränssnitt som hanterar inläsning av externa resurser. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Returnerar eller anger callback-gränssnitt som hanterar inläsning av externa resurser. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Representerar alternativ som kan användas för att specificera ytterligare beteende för kalkylblad. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Representerar alternativ som kan användas för att specificera ytterligare beteende för kalkylblad. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Returnerar eller anger standardspråket för presentationstext. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Returnerar eller anger standardspråket för presentationstext. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt under laddning av presentationen. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt under laddning av presentationen. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Returnerar eller anger formatet för en presentation som ska laddas. Läs/skriv [LoadFormat](../../com.aspose.slides/loadformat).

**Returnerar:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```


Returnerar eller anger formatet för en presentation som ska laddas. Läs/skriv [LoadFormat](../../com.aspose.slides/loadformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Returnerar eller anger Regular-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Returnerar:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Returnerar eller anger Regular-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```


Returnerar eller anger Symbol-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Returnerar:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```


Returnerar eller anger Symbol-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```


Returnerar eller anger Asian-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Returnerar:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```


Returnerar eller anger Asian-typsnitt som används om kälttypsnittet inte hittas. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Hämtar eller anger lösenordet. Läs/skriv String.

Värde: Lösenordet.

**Returnerar:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


Hämtar eller anger lösenordet. Läs/skriv String.

Värde: Lösenordet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```


Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska laddas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska laddas med rätt lösenord. Om presentationen inte är krypterad ignoreras alltid egenskapsvärdet. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapsvärdet är true kan inte dokumentegenskaperna laddas och ett undantag kastas. Läs/skriv boolean.

**Returnerar:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```


Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska laddas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen ska laddas med rätt lösenord. Om presentationen inte är krypterad ignoreras alltid egenskapsvärdet. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapsvärdet är true kan inte dokumentegenskaperna laddas och ett undantag kastas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Returnerar eller anger ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returnerar:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Returnerar eller anger ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Läs/skriv [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```


Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller max antal BLOB-bytes i minnet. Dessa alternativ är avsedda att ställa in bästa prestanda/minnesförbrukningsförhållande för en viss miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. kan ett BLOB vara ljud, video eller själva presentationen.

**Returnerar:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```


Representerar de alternativ som kan användas för att hantera Binary Large Objects (BLOBs), t.ex. användning av temporära filer eller max antal BLOB-bytes i minnet. Dessa alternativ är avsedda att ställa in bästa prestanda/minnesförbrukningsförhållande för en viss miljö eller krav.

--------------------

Ett Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. kan ett BLOB vara ljud, video eller själva presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```


Anger källor för externa typsnitt som ska användas av presentationen. Dessa typsnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer.

**Returnerar:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```


Anger källor för externa typsnitt som ska användas av presentationen. Dessa typsnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```


Tokenet för att övervaka avbrottsförfrågningar.

--------------------

Detta token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livstid. Alla långvariga operationer, såsom laddning eller sparande av en presentation, avbryts genom att anropa [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-metoden på [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Returnerar:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```


Tokenet för att övervaka avbrottsförfrågningar.

--------------------

Detta token hanterar hela [IPresentation](../../com.aspose.slides/ipresentation)-instansens livtid. Alla långvariga operationer, såsom laddning eller sparande av en presentation, avbryts genom att anropa [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt)-metoden på [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```


Returnerar eller anger callback-gränssnitt som hanterar inläsning av externa resurser. Läs/skriv [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returnerar:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Returnerar eller anger callback-gränssnitt som hanterar inläsning av externa resurser. Läs/skriv [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```


Representerar alternativ som kan användas för att specificera ytterligare beteende för kalkylblad.

**Returnerar:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Representerar alternativ som kan användas för att specificera ytterligare beteende för kalkylblad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```


Returnerar eller anger standardspråket för presentationstext. Läs/skriv String.

--------------------

> ```
> Example:
>   
>  // Använd laddningsalternativ för att definiera standardtextkulturen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till en ny rektangelform med text
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Kontrollera språket för den första delen
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```


Returnerar eller anger standardspråket för presentationstext. Läs/skriv String.

--------------------

> ```
> Example:
>   
>  // Använd laddningsalternativ för att definiera standardtextkulturen
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Lägg till en ny rektangelform med text
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```


Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt under laddning av presentationen.

Typerna av de inbäddade binära objekten:

 *  
 *  
 *  

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

**Returnerar:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```


Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt under laddning av presentationen.

Typerna av de inbäddade binära objekten:

 *  
 *  
 *  

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