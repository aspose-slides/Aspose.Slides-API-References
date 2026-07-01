---
title: DocumentProperties
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le proprietà di una presentazione.
type: docs
weight: 2770
url: /it/aspose.slides/documentproperties/
---
## DocumentProperties classe

Rappresenta le proprietà di una presentazione.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Costruttori

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inizializza una nuova istanza della classe [`DocumentProperties`](../documentproperties). |

## Proprietà

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Restituisce o imposta il modello di un'applicazione. Lettura/scrittura Stringa. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Restituisce la versione dell'app. Solo lettura Stringa. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Restituisce o imposta l'autore di una presentazione. Lettura/scrittura Stringa. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Restituisce o imposta la categoria di una presentazione. Lettura/scrittura Stringa. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Restituisce o imposta i commenti di una presentazione. Lettura/scrittura Stringa. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Restituisce o imposta la proprietà azienda. Lettura/scrittura Stringa. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Restituisce o imposta lo stato del contenuto di una presentazione. Lettura/scrittura Stringa. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Restituisce o imposta il tipo di contenuto di una presentazione. Lettura/scrittura Stringa. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Restituisce il numero di proprietà personalizzate effettivamente contenute in una raccolta. Solo lettura Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Restituisce la data in cui è stata creata una presentazione. I valori sono in UTC. Lettura/scrittura DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo. Solo lettura IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Restituisce il numero di diapositive nascoste in un documento di presentazione. Solo lettura Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Restituisce o imposta la proprietà HyperlinkBase del documento. Lettura/scrittura Stringa. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che apre questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Lettura/scrittura Booleano. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Restituisce o imposta la proprietà personalizzata associata a un nome specificato. Lettura/scrittura Oggetto. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Restituisce o imposta le parole chiave di una presentazione. Lettura/scrittura Stringa. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Restituisce la data in cui una presentazione è stata stampata l'ultima volta. Lettura/scrittura DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione. Lettura/scrittura Stringa. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Restituisce la data in cui una presentazione è stata modificata per l'ultima volta. I valori sono in UTC. Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Vedi l'esempio nel riepilogo del metodo [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indica se i collegamenti ipertestuali in un documento sono aggiornati. Imposta questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati. Imposta questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti. Lettura/scrittura Booleano. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Restituisce o imposta la proprietà manager. Lettura/scrittura Stringa. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Restituisce il numero totale di clip audio o video presenti nel documento. Solo lettura Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Restituisce o imposta il nome dell'applicazione. Lettura/scrittura Stringa. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Restituisce il numero di diapositive in una presentazione contenenti note. Solo lettura Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Restituisce il numero totale di paragrafi trovati in un documento, se applicabile. Solo lettura Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Restituisce o imposta il formato previsto di una presentazione. Lettura/scrittura Stringa. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Restituisce o imposta il numero di revisione della presentazione. Lettura/scrittura Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indica la modalità di visualizzazione della miniatura del documento. Imposta questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento alla visualizzazione. Imposta questo elemento su **false** per abilitare il ritaglio della miniatura del documento in modo da mostrare solo le sezioni che si adattano alla visualizzazione. Lettura/scrittura Booleano. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Determina se la presentazione è condivisa tra più persone. Lettura/scrittura Booleano. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Restituisce il numero totale di diapositive in un documento di presentazione. Solo lettura Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Restituisce o imposta l'oggetto della presentazione. Lettura/scrittura Stringa. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Restituisce o imposta il titolo di una presentazione. Lettura/scrittura Stringa. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Specifica il titolo di ciascuna parte del documento. Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento. Solo lettura string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Tempo totale di modifica di una presentazione. Lettura/scrittura TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Restituisce il numero totale di parole contenute in un documento. Solo lettura Int32. |

## Metodi

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Cancella e imposta i valori predefiniti per tutte le proprietà integrate. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Rimuove tutte le proprietà personalizzate. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clona l'oggetto corrente |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clona l'oggetto corrente |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Ottiene un valore booleano denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Ottiene un valore DateTime denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Ottiene un valore double denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Ottiene un valore float denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Ottiene un valore intero denominato dalle proprietà personalizzate. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Ottiene un valore stringa denominato dalle proprietà personalizzate. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Imposta una proprietà personalizzata booleana denominata. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Imposta una proprietà personalizzata DateTime denominata. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Imposta una proprietà personalizzata double denominata. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Imposta una proprietà personalizzata float denominata. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Imposta una proprietà personalizzata intera denominata. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Imposta una proprietà personalizzata stringa denominata. |

### Esempi

L'esempio seguente mostra come accedere alle proprietà integrate di una presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation che rappresenta la presentazione
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Crea un riferimento all'oggetto IDocumentProperties associato alla Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Visualizza le proprietà incorporate
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

L'esempio seguente mostra come modificare le proprietà integrate di una presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation che rappresenta la Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Crea un riferimento all'oggetto IDocumentProperties associato alla Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Imposta le proprietà predefinite
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Salva la presentazione in un file
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->