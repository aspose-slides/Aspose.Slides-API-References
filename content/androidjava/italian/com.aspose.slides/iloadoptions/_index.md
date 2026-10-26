---
title: ILoadOptions
second_title: Aspose.Slides per Android tramite API Java
description: Consente di specificare opzioni aggiuntive come formato o carattere predefinito durante il caricamento di una presentazione.
type: docs
url: /it/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Consente di specificare opzioni aggiuntive (come formato o carattere predefinito) durante il caricamento di una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Restituisce o imposta il formato di una presentazione da caricare. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Restituisce o imposta il formato di una presentazione da caricare. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Restituisce o imposta il carattere Regular usato nel caso in cui il carattere di origine non sia trovato. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Restituisce o imposta il carattere Regular usato nel caso in cui il carattere di origine non sia trovato. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere di origine non sia trovato. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere di origine non sia trovato. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Restituisce o imposta il carattere Asian usato nel caso in cui il carattere di origine non sia trovato. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Restituisce o imposta il carattere Asian usato nel caso in cui il carattere di origine non sia trovato. |
| [getPassword()](#getPassword--) | Ottiene o imposta la password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Questa proprietà ha senso se il file della presentazione è protetto da password. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Questa proprietà ha senso se il file della presentazione è protetto da password. |
| [getWarningCallback()](#getWarningCallback--) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento deve continuare o essere interrotto. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento deve continuare o essere interrotto. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB), ad esempio l'uso di file temporanei o il numero massimo di byte BLOB in memoria. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB), ad esempio l'uso di file temporanei o il numero massimo di byte BLOB in memoria. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specifica le font esterne da utilizzare nella presentazione. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specifica le font esterne da utilizzare nella presentazione. |
| [getInterruptionToken()](#getInterruptionToken--) | Il token da monitorare per richieste di interruzione. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Il token da monitorare per richieste di interruzione. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento di risorse esterne. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento di risorse esterne. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Rappresenta le opzioni che possono essere utilizzate per specificare comportamenti aggiuntivi per i fogli di calcolo. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Rappresenta le opzioni che possono essere utilizzate per specificare comportamenti aggiuntivi per i fogli di calcolo. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Restituisce o imposta la lingua predefinita per il testo della presentazione. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Restituisce o imposta la lingua predefinita per il testo della presentazione. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Restituisce o imposta il formato di una presentazione da caricare. Lettura/scrittura [LoadFormat](../../com.aspose.slides/loadformat).

**Restituisce:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Restituisce o imposta il formato di una presentazione da caricare. Lettura/scrittura [LoadFormat](../../com.aspose.slides/loadformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Restituisce o imposta il carattere Regular usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Restituisce:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Restituisce o imposta il carattere Regular usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Restituisce:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Restituisce o imposta il carattere Asian usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Restituisce:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Restituisce o imposta il carattere Asian usato nel caso in cui il carattere di origine non sia trovato. Lettura-scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Ottiene o imposta la password. Lettura-scrittura String.

Valore: La password.

**Restituisce:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Ottiene o imposta la password. Lettura-scrittura String.

Valore: La password.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Questa proprietà ha senso se il file della presentazione è protetto da password. Il valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione cifrato e la password viene ignorata. Il valore false indica che l'intera presentazione cifrata deve essere caricata utilizzando la password corretta. Se la presentazione non è cifrata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file cifrato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione. Lettura-scrittura boolean.

**Restituisce:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Questa proprietà ha senso se il file della presentazione è protetto da password. Il valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione cifrato e la password viene ignorata. Il valore false indica che l'intera presentazione cifrata deve essere caricata utilizzando la password corretta. Se la presentazione non è cifrata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file cifrato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione. Lettura-scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento deve continuare o essere interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Restituisce:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento deve continuare o essere interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB), ad esempio l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono intese per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari.

--------------------

Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola – ad esempio un BLOB può essere un audio, un video o la presentazione stessa.

**Restituisce:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB), ad esempio l'uso di file temporanei o il numero massimo di byte BLOB in memoria. Queste opzioni sono intese per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari.

--------------------

Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola – ad esempio un BLOB può essere un audio, un video o la presentazione stessa.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Specifica le font esterne da utilizzare nella presentazione. Queste font sono disponibili per la presentazione per tutta la sua durata e non sono condivise con altre presentazioni.

**Restituisce:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Specifica le font esterne da utilizzare nella presentazione. Queste font sono disponibili per la presentazione per tutta la sua durata e non sono condivise con altre presentazioni.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Il token da monitorare per richieste di interruzione.

--------------------

Questo token gestisce l'intera durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio della presentazione, verrà interrotta chiamando il metodo [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) di [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Restituisce:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Il token da monitorare per richieste di interruzione.

--------------------

Questo token gestisce l'intera durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio della presentazione, verrà interrotta chiamando il metodo [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) di [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Restituisce o imposta l'interfaccia di callback che gestisce il caricamento di risorse esterne. Lettura/scrittura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Restituisce:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Restituisce o imposta l'interfaccia di callback che gestisce il caricamento di risorse esterne. Lettura/scrittura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Rappresenta le opzioni che possono essere utilizzate per specificare comportamenti aggiuntivi per i fogli di calcolo.

**Restituisce:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Rappresenta le opzioni che possono essere utilizzate per specificare comportamenti aggiuntivi per i fogli di calcolo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/scrittura String.

--------------------

> ```
> Example:
>   
>  // Utilizzare le opzioni di caricamento per definire la cultura del testo predefinita
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Aggiungere una nuova forma rettangolare con testo
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificare la lingua della prima porzione
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/scrittura String.

--------------------

> ```
> Example:
>   
>  // Utilizzare le opzioni di caricamento per definire la cultura del testo predefinita
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Aggiungere una nuova forma rettangolare con testo
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verificare la lingua della prima porzione
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

I tipi di oggetti binari incorporati:

 *  
 *  
 *  

Lettura-scrittura  boolean .

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

Il valore predefinito è **false**.

**Restituisce:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

I tipi di oggetti binari incorporati:

 *  
 *  
 *  

Lettura-scrittura  boolean .

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

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |