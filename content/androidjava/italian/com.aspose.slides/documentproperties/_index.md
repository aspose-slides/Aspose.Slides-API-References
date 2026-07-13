---
title: DocumentProperties
second_title: Riferimento API di Aspose.Slides per Android via Java
description: Rappresenta le proprietà di una presentazione.
type: docs
url: /it/com.aspose.slides/documentproperties/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Rappresenta le proprietà di una presentazione.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta la presentazione
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Crea un riferimento all'oggetto IDocumentProperties associato alla Presentazione
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Visualizza le proprietà integrate
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta la Presentazione
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Crea un riferimento all'oggetto IDocumentProperties associato alla Presentazione
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Imposta le proprietà integrate
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Salva la presentazione in un file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Inizializza una nuova istanza della classe [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Restituisce la versione dell'app. |
| [getNameOfApplication()](#getNameOfApplication--) | Restituisce o imposta il nome dell'applicazione. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Restituisce o imposta il nome dell'applicazione. |
| [getCompany()](#getCompany--) | Restituisce o imposta la proprietà dell'azienda. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Restituisce o imposta la proprietà dell'azienda. |
| [getManager()](#getManager--) | Restituisce o imposta la proprietà del manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Restituisce o imposta la proprietà del manager. |
| [getPresentationFormat()](#getPresentationFormat--) | Restituisce o imposta il formato previsto di una presentazione. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Restituisce o imposta il formato previsto di una presentazione. |
| [getSharedDoc()](#getSharedDoc--) | Determina se la presentazione è condivisa tra più persone. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determina se la presentazione è condivisa tra più persone. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Restituisce o imposta il modello di un'applicazione. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Restituisce o imposta il modello di un'applicazione. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Tempo totale di modifica di una presentazione. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Tempo totale di modifica di una presentazione. |
| [getTitle()](#getTitle--) | Restituisce o imposta il titolo di una presentazione. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Restituisce o imposta il titolo di una presentazione. |
| [getSubject()](#getSubject--) | Restituisce o imposta l'oggetto di una presentazione. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Restituisce o imposta l'oggetto di una presentazione. |
| [getAuthor()](#getAuthor--) | Restituisce o imposta l'autore di una presentazione. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Restituisce o imposta l'autore di una presentazione. |
| [getKeywords()](#getKeywords--) | Restituisce o imposta le parole chiave di una presentazione. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Restituisce o imposta le parole chiave di una presentazione. |
| [getComments()](#getComments--) | Restituisce o imposta i commenti di una presentazione. |
| [setComments(String value)](#setComments-java.lang.String-) | Restituisce o imposta i commenti di una presentazione. |
| [getCategory()](#getCategory--) | Restituisce o imposta la categoria di una presentazione. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Restituisce o imposta la categoria di una presentazione. |
| [getCreatedTime()](#getCreatedTime--) | Restituisce la data in cui è stata creata una presentazione. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Restituisce la data in cui è stata creata una presentazione. |
| [getLastSavedTime()](#getLastSavedTime--) | Restituisce la data in cui una presentazione è stata modificata l'ultima volta. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Restituisce la data in cui una presentazione è stata modificata l'ultima volta. |
| [getLastPrinted()](#getLastPrinted--) | Restituisce la data in cui una presentazione è stata stampata l'ultima volta. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Restituisce la data in cui una presentazione è stata stampata l'ultima volta. |
| [getLastSavedBy()](#getLastSavedBy--) | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. |
| [getRevisionNumber()](#getRevisionNumber--) | Restituisce o imposta il numero di revisione della presentazione. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Restituisce o imposta il numero di revisione della presentazione. |
| [getContentStatus()](#getContentStatus--) | Restituisce o imposta lo stato del contenuto di una presentazione. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Restituisce o imposta lo stato del contenuto di una presentazione. |
| [getContentType()](#getContentType--) | Restituisce o imposta il tipo di contenuto di una presentazione. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Restituisce o imposta il tipo di contenuto di una presentazione. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Restituisce o imposta la proprietà del documento HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Restituisce o imposta la proprietà del documento HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Restituisce il numero di proprietà personalizzate effettivamente contenute in una collezione. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Imposta una proprietà personalizzata booleana denominata. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Imposta una proprietà personalizzata intera denominata. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Imposta una proprietà personalizzata DateTime denominata. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Imposta una proprietà personalizzata stringa denominata. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Imposta una proprietà personalizzata float denominata. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Imposta una proprietà personalizzata double denominata. |
| [clearCustomProperties()](#clearCustomProperties--) | Rimuove tutte le proprietà personalizzate. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Cancella e imposta i valori predefiniti per tutte le proprietà integrate. |
| [getScaleCrop()](#getScaleCrop--) | Indica la modalità di visualizzazione della miniatura del documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica la modalità di visualizzazione della miniatura del documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica se i collegamenti ipertestuali in un documento sono aggiornati. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica se i collegamenti ipertestuali in un documento sono aggiornati. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. |
| [getSlides()](#getSlides--) | Restituisce il numero totale di diapositive in un documento di presentazione. |
| [getHiddenSlides()](#getHiddenSlides--) | Restituisce il numero di diapositive nascoste in un documento di presentazione. |
| [getNotes()](#getNotes--) | Restituisce il numero di diapositive in una presentazione contenenti note. |
| [getParagraphs()](#getParagraphs--) | Restituisce il numero totale di paragrafi trovati in un documento, se applicabile. |
| [getWords()](#getWords--) | Restituisce il numero totale di parole contenute in un documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Restituisce il numero totale di clip audio o video presenti nel documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specifica il titolo di ogni parte del documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo. |
| [deepClone()](#deepClone--) | Duplica l'oggetto corrente |
| [cloneT()](#cloneT--) | Duplica l'oggetto corrente |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Inizializza una nuova istanza della classe [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Restituisce la versione dell'app. Solo lettura String.

**Restituisce:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Restituisce o imposta il nome dell'applicazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Restituisce o imposta il nome dell'applicazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Restituisce o imposta la proprietà dell'azienda. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Restituisce o imposta la proprietà dell'azienda. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Restituisce o imposta la proprietà del manager. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Restituisce o imposta la proprietà del manager. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Restituisce o imposta il formato previsto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Restituisce o imposta il formato previsto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Determina se la presentazione è condivisa tra più persone. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Determina se la presentazione è condivisa tra più persone. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Restituisce o imposta il modello di un'applicazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Restituisce o imposta il modello di un'applicazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Tempo totale di modifica di una presentazione. Lettura/Scrittura double.

**Restituisce:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Tempo totale di modifica di una presentazione. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Restituisce o imposta il titolo di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Restituisce o imposta il titolo di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Restituisce o imposta l'oggetto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Restituisce o imposta l'oggetto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Restituisce o imposta l'autore di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Restituisce o imposta l'autore di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Restituisce o imposta le parole chiave di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Restituisce o imposta le parole chiave di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Restituisce o imposta i commenti di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Restituisce o imposta i commenti di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Restituisce o imposta la categoria di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Restituisce o imposta la categoria di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Restituisce la data in cui è stata creata una presentazione. I valori sono in UTC. Lettura/Scrittura java.util.Date.

**Restituisce:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Restituisce la data in cui è stata creata una presentazione. I valori sono in UTC. Lettura/Scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Restituisce la data in cui una presentazione è stata modificata l'ultima volta. I valori sono in UTC. Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vedere l'esempio nel riepilogo del metodo [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Restituisce:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Restituisce la data in cui una presentazione è stata modificata l'ultima volta. I valori sono in UTC. Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Vedere l'esempio nel riepilogo del metodo [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Restituisce la data in cui una presentazione è stata stampata l'ultima volta. Lettura/Scrittura java.util.Date.

**Restituisce:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Restituisce la data in cui una presentazione è stata stampata l'ultima volta. Lettura/Scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Restituisce o imposta il numero di revisione della presentazione. Lettura/Scrittura int.

**Restituisce:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Restituisce o imposta il numero di revisione della presentazione. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Restituisce o imposta la proprietà del documento HyperlinkBase. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Restituisce o imposta la proprietà del documento HyperlinkBase. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Restituisce il numero di proprietà personalizzate effettivamente contenute in una collezione. Solo lettura int.

**Restituisce:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Restituisce il nome di una proprietà personalizzata all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero della proprietà personalizzata da ottenere. |

**Restituisce:**
java.lang.String - Nome della proprietà personalizzata all'indice specificato.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Rimuove una proprietà personalizzata associata a un nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da rimuovere. |

**Restituisce:**
boolean - Restituisce true se la proprietà è stata rimossa, false altrimenti.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Verifica la presenza di una proprietà personalizzata con un nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da verificare. |

**Restituisce:**
boolean - Restituisce true se la proprietà esiste, false altrimenti.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/Scrittura Object.

--------------------

Il valore può essere **int**, **float**, **String**, **boolean** o **Date**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |

**Restituisce:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/Scrittura Object.

--------------------

Il valore può essere **int**, **float**, **String**, **boolean** o **Date**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Ottiene un valore booleano con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | boolean[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Ottiene un valore intero con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | int[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Ottiene un valore DateTime con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | java.util.Date[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public            (the text appears corrupted)
```

Ottiene un valore stringa con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | java.lang.String[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Ottiene un valore float con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | float[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Ottiene un valore double con nome dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere. |
| value | double[] | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Imposta una proprietà personalizzata booleana denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | boolean | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Imposta una proprietà personalizzata intera denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | int | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Imposta una proprietà personalizzata DateTime denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | java.util.Date | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Imposta una proprietà personalizzata stringa denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | java.lang.String | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Imposta una proprietà personalizzata float denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | float | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Imposta una proprietà personalizzata double denominata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | double | Valore della proprietà personalizzata |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Rimuove tutte le proprietà personalizzate.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Cancella e imposta i valori predefiniti per tutte le proprietà integrate.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Indica la modalità di visualizzazione della miniatura del documento. Impostare questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento al display. Impostare questo elemento su **false** per abilitare il ritaglio della miniatura del documento per mostrare solo le sezioni che si adattano al display. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Indica la modalità di visualizzazione della miniatura del documento. Impostare questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento al display. Impostare questo elemento su **false** per abilitare il ritaglio della miniatura del documento per mostrare solo le sezioni che si adattano al display. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Indica se i collegamenti ipertestuali in un documento sono aggiornati. Impostare questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati. Impostare questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Indica se i collegamenti ipertestuali in un documento sono aggiornati. Impostare questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati. Impostare questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Restituisce il numero totale di diapositive in un documento di presentazione. Solo lettura int.

**Restituisce:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Restituisce il numero di diapositive nascoste in un documento di presentazione. Solo lettura int.

**Restituisce:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Restituisce il numero di diapositive in una presentazione contenenti note. Solo lettura int.

**Restituisce:**
int
### getParagraphs() {#getParagraphs--}
```
public   …  …  …  …  ? ? ? ? ? ? ? 
```

Restituisce il numero totale di paragrafi trovati in un documento, se applicabile. Solo lettura int.

**Restituisce:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Restituisce il numero totale di parole contenute in un documento. Solo lettura int.

**Restituisce:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Restituisce il numero totale di clip audio o video presenti nel documento. Solo lettura int.

**Restituisce:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Specifica il titolo di ogni parte del documento. Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento. Solo lettura String[].

**Restituisce:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo. Solo lettura IHeadingPair[].

**Restituisce:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Duplica l'oggetto corrente

**Restituisce:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Duplica l'oggetto corrente

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone