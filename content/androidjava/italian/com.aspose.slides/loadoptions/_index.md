---
title: LoadOptions
second_title: Aspose.Slides per Android tramite Java API Reference
description: Consente di specificare opzioni aggiuntive come formato o carattere predefinito durante il caricamento di una presentazione.
type: docs
url: /it/com.aspose.slides/loadoptions/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Consente di specificare opzioni aggiuntive (come formato o carattere predefinito) durante il caricamento di una presentazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Crea nuove opzioni di caricamento predefinite. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Crea nuove opzioni di caricamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Restituisce o imposta il formato di una presentazione da caricare. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Restituisce o imposta il formato di una presentazione da caricare. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Restituisce o imposta il carattere Regular usato nel caso in cui il carattere sorgente non sia trovato. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Restituisce o imposta il carattere Regular usato nel caso in cui il carattere sorgente non sia trovato. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere sorgente non sia trovato. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere sorgente non sia trovato. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Restituisce o imposta il carattere Asian usato nel caso in cui il carattere sorgente non sia trovato. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Restituisce o imposta il carattere Asian usato nel caso in cui il carattere sorgente non sia trovato. |
| [getPassword()](#getPassword--) | Ottiene o imposta la password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Questa proprietà ha senso se il file della presentazione è protetto da password. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Questa proprietà ha senso se il file della presentazione è protetto da password. |
| [getWarningCallback()](#getWarningCallback--) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB). Ad esempio l'uso di file temporanei o il numero massimo di byte dei BLOB in memoria. Queste opzioni sono pensate per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB). Ad esempio l'uso di file temporanei o il numero massimo di byte dei BLOB in memoria. Queste opzioni sono pensate per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Specifica le sorgenti per i caratteri esterni da utilizzare nella presentazione. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Specifica le sorgenti per i caratteri esterni da utilizzare nella presentazione. |
| [getInterruptionToken()](#getInterruptionToken--) | Il token per monitorare le richieste di interruzione. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Il token per monitorare le richieste di interruzione. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ottiene le opzioni per i fogli di calcolo. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Ottiene le opzioni per i fogli di calcolo. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Restituisce o imposta la lingua predefinita per il testo della presentazione. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Restituisce o imposta la lingua predefinita per il testo della presentazione. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Crea nuove opzioni di caricamento predefinite.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Crea nuove opzioni di caricamento.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loadFormat | int | Formato di una presentazione da caricare. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Restituisce o imposta il formato di una presentazione da caricare. Lettura/scrittura [LoadFormat](../../com.aspose.slides/loadformat).

**Restituisce:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Restituisce o imposta il formato di una presentazione da caricare. Lettura/scrittura [LoadFormat](../../com.aspose.slides/loadformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Restituisce o imposta il carattere Regular usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Usa le opzioni di caricamento per definire i caratteri regular e asian predefiniti
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Carica la presentazione
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Genera l'anteprima della diapositiva
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
>      // Genera PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Genera XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Restituisce o imposta il carattere Regular usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Usa le opzioni di caricamento per definire i caratteri regular e asian predefiniti
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Carica la presentazione
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Genera l'anteprima della diapositiva
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
>      // Genera PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Genera XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Restituisce o imposta il carattere Symbol usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Restituisce o imposta il carattere Asian usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Restituisce o imposta il carattere Asian usato nel caso in cui il carattere sorgente non sia trovato. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Ottiene o imposta la password. Lettura/scrittura String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // lavora con la presentazione decrittata
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valore: La password.

**Restituisce:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ottiene o imposta la password. Lettura/scrittura String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // lavora con la presentazione decrittata
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Valore: La password.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Questa proprietà ha senso se il file della presentazione è protetto da password. Un valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione crittografato e la password deve essere ignorata. Un valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta. Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Questa proprietà ha senso se il file della presentazione è protetto da password. Un valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione crittografato e la password deve essere ignorata. Un valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta. Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Restituisce:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB). Ad esempio l'uso di file temporanei o il numero massimo di byte dei BLOB in memoria. Queste opzioni sono pensate per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari.

--------------------

Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola, ad es. un BLOB può essere un audio, un video o la presentazione stessa.

**Restituisce:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Rappresenta le opzioni che possono essere utilizzate per gestire il comportamento di manipolazione dei Binary Large Objects (BLOB). Ad esempio l'uso di file temporanei o il numero massimo di byte dei BLOB in memoria. Queste opzioni sono pensate per impostare il miglior rapporto prestazioni/consumo di memoria per un ambiente o requisiti particolari.

--------------------

Un Binary Large Object (BLOB) è un dato binario memorizzato come entità singola, ad es. un BLOB può essere un audio, un video o la presentazione stessa.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Specifică le sorgenti per i caratteri esterni da utilizzare nella presentazione. Questi caratteri sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni.

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
>  //lavora con la presentazione
>  //CustomFont1, CustomFont2 così come i caratteri da cartelle assets\fonts e global\fonts e le loro sottocartelle sono disponibili per la presentazione
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Specifică le sorgenti per i caratteri esterni da utilizzare nella presentazione. Questi caratteri sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni.

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
>  //lavora con la presentazione
>  //CustomFont1, CustomFont2 così come i caratteri dalle cartelle assets\fonts e global\fonts e le loro sottocartelle sono disponibili per la presentazione
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Il token per monitorare le richieste di interruzione.

--------------------

Questo token gestisce l'intera durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio di una presentazione, sarà interrotta chiamando il metodo [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) di [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Restituisce:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Il token per monitorare le richieste di interruzione.

--------------------

Questo token gestisce l'intera durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio di una presentazione, sarà interrotta chiamando il metodo [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) di [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. Lettura/scrittura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Restituisce:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Restituisce o imposta l'interfaccia di callback che gestisce il caricamento delle risorse esterne. Lettura/scrittura [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Ottiene le opzioni per i fogli di calcolo. Per esempio, queste opzioni influenzano il calcolo delle formule per i grafici.

**Restituisce:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Ottiene le opzioni per i fogli di calcolo. Per esempio, queste opzioni influenzano il calcolo delle formule per i grafici.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/scrittura String.

--------------------

> ```
> Example:
>   
>  // Usa le opzioni di caricamento per definire la cultura di testo predefinita
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Aggiungi una nuova forma rettangolare con testo
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verifica la lingua della prima porzione
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Restituisce o imposta la lingua predefinita per il testo della presentazione. Lettura/scrittura String.

--------------------

> ```
> Example:
>   
>  // Usa le opzioni di caricamento per definire la cultura di testo predefinita
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Aggiungi una nuova forma rettangolare con testo
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Verifica la lingua della prima porzione
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

I tipi degli oggetti binari incorporati:

Lettura/scrittura boolean.

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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Determina se Aspose.Slides eliminerà tutti gli oggetti binari incorporati durante il caricamento della presentazione.

I tipi degli oggetti binari incorporati:

Lettura/scrittura boolean.

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