---
title: IDocumentProperties
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le proprietà di una presentazione.
type: docs
weight: 5710
url: /it/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfaccia

Rappresenta le proprietà di una presentazione.

```csharp
public interface IDocumentProperties
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Restituisce o imposta il modello di un'applicazione. Lettura/Scrittura String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Restituisce la versione dell'app. Solo lettura String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Restituisce o imposta l'autore di una presentazione. Lettura/Scrittura String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Restituisce o imposta la categoria di una presentazione. Lettura/Scrittura String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Restituisce o imposta i commenti di una presentazione. Lettura/Scrittura String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Restituisce o imposta la proprietà company. Lettura/Scrittura String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/Scrittura String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/Scrittura String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Restituisce il numero di proprietà personalizzate effettivamente contenute in una collezione. Solo lettura Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Restituisce la data di creazione di una presentazione. I valori sono in UTC. Lettura/Scrittura DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indica il raggruppamento delle parti del documento e il numero di parti in ogni gruppo. Solo lettura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Specifica il numero di diapositive nascoste in un documento di presentazione. Solo lettura Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Restituisce o imposta la proprietà di documento HyperlinkBase. Lettura/Scrittura String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che apre questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/Scrittura Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/Scrittura Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Restituisce o imposta le parole chiave di una presentazione. Lettura/Scrittura String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Restituisce la data dell'ultima stampa di una presentazione. Lettura/Scrittura DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/Scrittura String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Restituisce la data di ultima modifica di una presentazione. I valori sono in UTC. Solo lettura nel caso di Presentation.DocumentProperties (perché sarà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificata tramite l'istanza DocumentProperties restituita dal metodo [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Vedere l'esempio nel riepilogo del metodo [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indica se i collegamenti ipertestuali in un documento sono aggiornati. Imposta questo elemento su **true** per indicare che i collegamenti sono aggiornati. Imposta questo elemento su **false** per indicare che i collegamenti sono obsoleti. Lettura/Scrittura Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Restituisce o imposta la proprietà manager. Lettura/Scrittura String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Specifica il numero totale di clip audio o video presenti nel documento. Solo lettura Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Restituisce o imposta il nome dell'applicazione. Lettura/Scrittura String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Specifica il numero di diapositive in una presentazione contenenti note. Solo lettura Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Specifica il numero totale di paragrafi trovati in un documento, se applicabile. Solo lettura Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Restituisce o imposta il formato previsto di una presentazione. Lettura/Scrittura String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Restituisce o imposta il numero di revisione della presentazione. Lettura/Scrittura Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indica la modalità di visualizzazione della miniatura del documento. Imposta questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento al display. Imposta questo elemento su **false** per abilitare il ritaglio della miniatura del documento in modo da mostrare solo le sezioni che si adattano al display. Lettura/Scrittura Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Determina se la presentazione è condivisa tra più persone. Lettura/Scrittura Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Specifica il numero totale di diapositive in un documento di presentazione. Solo lettura Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Restituisce o imposta l'argomento di una presentazione. Lettura/Scrittura String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Restituisce o imposta il titolo di una presentazione. Lettura/Scrittura String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Specifica il titolo di ciascuna parte del documento. Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento. Solo lettura string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Tempo totale di modifica di una presentazione. Lettura/Scrittura TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Specifica il numero totale di parole contenute in un documento. Solo lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Cancella e imposta i valori predefiniti per tutte le proprietà builtIn. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Rimuove tutte le proprietà personalizzate. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Ottiene un valore booleano denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Ottiene un valore DateTime denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Ottiene un valore double denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Ottiene un valore float denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Ottiene un valore intero denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Ottiene un valore stringa denominato dalle proprietà personalizzate. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Imposta una proprietà personalizzata boolean denominata. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Imposta una proprietà personalizzata DateTime denominata. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Imposta una proprietà personalizzata double denominata. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Imposta una proprietà personalizzata float denominata. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Imposta una proprietà personalizzata intera denominata. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Imposta una proprietà personalizzata stringa denominata. |

### Vedi anche

* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->