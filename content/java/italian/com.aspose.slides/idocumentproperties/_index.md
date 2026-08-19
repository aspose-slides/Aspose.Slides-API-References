---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Represents properties of a presentation.
type: docs
url: /it/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Rappresenta le proprietà di una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Restituisce la versione dell'app. |
| [getNameOfApplication()](#getNameOfApplication--) | Restituisce o imposta il nome dell'applicazione. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Restituisce o imposta il nome dell'applicazione. |
| [getCompany()](#getCompany--) | Restituisce o imposta la proprietà azienda. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Restituisce o imposta la proprietà azienda. |
| [getManager()](#getManager--) | Restituisce o imposta la proprietà manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Restituisce o imposta la proprietà manager. |
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
| [getCreatedTime()](#getCreatedTime--) | Restituisce la data in cui una presentazione è stata creata. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Restituisce la data in cui una presentazione è stata creata. |
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
| [getScaleCrop()](#getScaleCrop--) | Indica la modalità di visualizzazione della miniatura del documento. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indica la modalità di visualizzazione della miniatura del documento. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indica se i collegamenti ipertestuali in un documento sono aggiornati. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indica se i collegamenti ipertestuali in un documento sono aggiornati. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. |
| [getSlides()](#getSlides--) | Specifica il numero totale di diapositive in un documento di presentazione. |
| [getHiddenSlides()](#getHiddenSlides--) | Specifica il numero di diapositive nascoste in un documento di presentazione. |
| [getNotes()](#getNotes--) | Specifica il numero di diapositive in una presentazione contenente note. |
| [getParagraphs()](#getParagraphs--) | Specifica il numero totale di paragrafi trovati in un documento, se applicabile. |
| [getWords()](#getWords--) | Specifica il numero totale di parole contenute in un documento. |
| [getMultimediaClips()](#getMultimediaClips--) | Specifica il numero totale di clip audio o video presenti nel documento. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specifica il titolo di ogni parte del documento. |
| [getHeadingPairs()](#getHeadingPairs--) | Indica il raggruppamento delle parti del documento e il numero di parti in ogni gruppo. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Restituisce il numero di proprietà personalizzate effettivamente contenute in una raccolta. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. |
| [clearCustomProperties()](#clearCustomProperties--) | Rimuove tutte le proprietà personalizzate. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Cancella e imposta i valori predefiniti per tutte le proprietà integrate. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Ottiene un valore booleano denominato dalle proprietà personalizzate. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Ottiene un valore intero denominato dalle proprietà personalizzate. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Ottiene un valore DateTime denominato dalle proprietà personalizzate. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Ottiene un valore stringa denominato dalle proprietà personalizzate. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Ottiene un valore float denominato dalle proprietà personalizzate. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Ottiene un valore double denominato dalle proprietà personalizzate. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Imposta una proprietà personalizzata boolean denominata. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Imposta una proprietà personalizzata intera denominata. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Imposta una proprietà personalizzata DateTime denominata. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Imposta una proprietà personalizzata stringa denominata. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Imposta una proprietà personalizzata float denominata. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Imposta una proprietà personalizzata double denominata. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Restituisce la versione dell'app. Solo lettura String.

Il contenuto di questo elemento deve essere nel formato XX.YYYY, dove X e Y rappresentano valori numerici; altrimenti, il documento sarà considerato non conforme. Aspose.Slides rappresenta la sua versione nel formato XX.YY.ZZ, dove: XX - versione principale YY - versione secondaria ZZ - versione patch. Per esempio, il valore 23.0105 indica la versione 23.1.5 di Aspose.Slides.

**Restituisce:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Restituisce o imposta il nome dell'applicazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Restituisce o imposta il nome dell'applicazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Restituisce o imposta la proprietà azienda. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Restituisce o imposta la proprietà azienda. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Restituisce o imposta la proprietà manager. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Restituisce o imposta la proprietà manager. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Restituisce o imposta il formato previsto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Restituisce o imposta il formato previsto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Determina se la presentazione è condivisa tra più persone. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Determina se la presentazione è condivisa tra più persone. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Restituisce o imposta il modello di un'applicazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Restituisce o imposta il modello di un'applicazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Tempo totale di modifica di una presentazione. Lettura/Scrittura double.

**Restituisce:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Tempo totale di modifica di una presentazione. Lettura/Scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Restituisce o imposta il titolo di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Restituisce o imposta il titolo di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Restituisce o imposta l'oggetto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Restituisce o imposta l'oggetto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Restituisce o imposta l'autore di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Restituisce o imposta l'autore di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Restituisce o imposta le parole chiave di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Restituisce o imposta le parole chiave di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Restituisce o imposta i commenti di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Restituisce o imposta i commenti di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Restituisce o imposta la categoria di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Restituisce la data in cui è stata creata una presentazione. I valori sono in UTC. Lettura/Scrittura java.util.Date.

**Restituisce:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Restituisce la data in cui è stata creata una presentazione. I valori sono in UTC. Lettura/Scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Restituisce la data in cui una presentazione è stata modificata per l'ultima volta. I valori sono in UTC. Sola lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Si prega di vedere l'esempio nel riepilogo del metodo [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Restituisce:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Restituisce la data in cui una presentazione è stata modificata per l'ultima volta. I valori sono in UTC. Sola lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Si prega di vedere l'esempio nel riepilogo del metodo [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Restituisce la data in cui una presentazione è stata stampata per l'ultima volta. Lettura/Scrittura java.util.Date.

**Restituisce:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Restituisce la data in cui una presentazione è stata stampata per l'ultima volta. Lettura/Scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Restituisce o imposta il numero di revisione della presentazione. Lettura/Scrittura int.

**Restituisce:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Restituisce o imposta il numero di revisione della presentazione. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Restituisce o imposta la proprietà HyperlinkBase del documento. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Restituisce o imposta la proprietà HyperlinkBase del documento. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Indica la modalità di visualizzazione della miniatura del documento. Impostare questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento sullo schermo. Impostare questo elemento su **false** per abilitare il ritaglio della miniatura del documento in modo da mostrare solo le sezioni che si adattano allo schermo. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Indica la modalità di visualizzazione della miniatura del documento. Impostare questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento sullo schermo. Impostare questo elemento su **false** per abilitare il ritaglio della miniatura del documento in modo da mostrare solo le sezioni che si adattano allo schermo. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Indica se i collegamenti ipertestuali in un documento sono aggiornati. Impostare questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati. Impostare questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Indica se i collegamenti ipertestuali in un documento sono aggiornati. Impostare questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati. Impostare questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Specifica il numero totale di diapositive in un documento di presentazione. Sola lettura int.

**Restituisce:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Specifica il numero di diapositive nascoste in un documento di presentazione. Sola lettura int.

**Restituisce:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Specifica il numero di diapositive in una presentazione che contengono note. Sola lettura int.

**Restituisce:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Specifica il numero totale di paragrafi trovati in un documento, se applicabile. Sola lettura int.

**Restituisce:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Specifica il numero totale di parole contenute in un documento. Sola lettura int.

**Restituisce:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Specifica il numero totale di clip audio o video presenti nel documento. Sola lettura int.

**Restituisce:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Specifica il titolo di ogni parte del documento. Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento. Sola lettura String[].

**Restituisce:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo. Sola lettura IHeadingPair[].

**Restituisce:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Restituisce il numero di proprietà personalizzate effettivamente contenute in una collezione. Sola lettura int.

**Restituisce:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
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
public abstract boolean removeCustomProperty(String name)
```

Rimuove una proprietà personalizzata associata a un nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da rimuovere. |

**Restituisce:**
boolean - Restituisce true se una proprietà è stata rimossa, false altrimenti.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Verifica la presenza di una proprietà personalizzata con il nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da verificare. |

**Restituisce:**
boolean - Restituisce true se la proprietà esiste, false altrimenti.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/Scrittura Object.

--------------------

Il valore può essere **int**, **float**, **double**, **String**, **boolean** o **Date**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |

**Restituisce:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/Scrittura Object.

--------------------

Il valore può essere **int**, **float**, **double**, **String**, **boolean** o **Date**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Rimuove tutte le proprietà personalizzate.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Cancella e imposta i valori predefiniti per tutte le proprietà builtIn.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Ottiene un valore booleano nominato dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | boolean[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Ottiene un valore intero nominato dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | int[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Ottiene un valore DateTime nominato dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | java.util.Date[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Ottiene un valore stringa nominato dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | java.lang.String[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Ottiene un valore float nominato dalle proprietà personalizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da ottenere |
| value | float[] | Valore della proprietà personalizzata |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Ottiene un valore double nominato dalle proprietà personalizzate.

**Parametri:**
| nome | java.lang.String | Nome della proprietà personalizzata da ottenere. |
| valore | double[] | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Imposta una proprietà personalizzata di tipo boolean con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | boolean | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Imposta una proprietà personalizzata di tipo int con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | int | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Imposta una proprietà personalizzata di tipo DateTime con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | java.util.Date | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Imposta una proprietà personalizzata di tipo string con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | java.lang.String | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Imposta una proprietà personalizzata di tipo float con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | float | Valore della proprietà personalizzata |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Imposta una proprietà personalizzata di tipo double con nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà personalizzata da impostare |
| value | double | Valore della proprietà personalizzata |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Restituisce un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata).

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