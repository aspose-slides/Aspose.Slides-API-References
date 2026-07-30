---
title: DocumentProperties
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le proprietà di una presentazione.
type: docs
weight: 794
url: /it/aspose.slides/documentproperties/
---
## DocumentProperties classe

Rappresenta le proprietà di una presentazione.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Cancella e imposta i valori predefiniti per tutte le proprietà builtIn. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Rimuove tutte le proprietà personalizzate. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Clona l'oggetto corrente |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Clona l'oggetto corrente |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
|  [DocumentProperties](./documentproperties/)() | Inizializza una nuova istanza della classe [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C#, dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Restituisce il modello di un'applicazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Restituisce la versione dell'app. Solo lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Restituisce l'autore di una presentazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Restituisce la categoria di una presentazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Restituisce i commenti di una presentazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Restituisce la proprietà azienda. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Restituisce lo stato del contenuto di una presentazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Restituisce il tipo di contenuto di una presentazione. Leggi [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Restituisce il numero di proprietà personalizzate effettivamente contenute in una collezione. Solo lettura **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Restituisce la data di creazione di una presentazione. I valori sono in UTC. Leggi [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indica il raggruppamento delle parti del documento e il numero di parti in ogni gruppo. Solo lettura [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Restituisce il numero di diapositive nascoste in un documento di presentazione. Solo lettura **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Restituisce la proprietà documento HyperlinkBase. Leggi [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Leggi **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Restituisce le parole chiave di una presentazione. Leggi [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Restituisce la data dell'ultima stampa di una presentazione. Leggi [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Restituisce il nome dell'ultima persona che ha modificato una presentazione. Leggi [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Restituisce la data dell'ultima modifica di una presentazione. I valori sono in UTC. Solo lettura in caso di [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto [IPresentation](../ipresentation/)). Può essere modificato tramite l'istanza [DocumentProperties](./) restituita dal metodo [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Vedi l'esempio nel riepilogo del metodo [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indica se i collegamenti ipertestuali in un documento sono aggiornati. Imposta questo elemento su **true** per indicare che i collegamenti sono aggiornati. Imposta questo elemento su **false** per indicare che i collegamenti sono obsoleti. Leggi **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Restituisce la proprietà manager. Leggi [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Restituisce il numero totale di clip audio o video presenti nel documento. Solo lettura **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Restituisce il nome dell'applicazione. Leggi [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Restituisce il numero di diapositive in una presentazione contenenti note. Solo lettura **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Restituisce il numero totale di paragrafi trovati in un documento, se applicabile. Solo lettura **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Restituisce il formato previsto di una presentazione. Leggi [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Restituisce il numero di revisione della presentazione. Leggi **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indica la modalità di visualizzazione della miniatura del documento. Imposta questo elemento su **true** per abilitare il ridimensionamento della miniatura al display. Imposta questo elemento su **false** per abilitare il ritaglio della miniatura mostrando solo le sezioni che si adattano al display. Leggi **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Determina se la presentazione è condivisa tra più persone. Leggi **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Restituisce il numero totale di diapositive in un documento di presentazione. Solo lettura **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Restituisce l'oggetto di una presentazione. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Restituisce il titolo di una presentazione. Leggi [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Specifica il titolo di ogni parte del documento. Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento. Solo lettura [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Tempo totale di modifica di una presentazione. Leggi [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Restituisce il numero totale di parole contenute in un documento. Solo lettura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Restituisce un nome di proprietà personalizzata all'indice specificato. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Ottiene un valore booleano denominato dalle proprietà personalizzate. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Ottiene un valore intero denominato dalle proprietà personalizzate. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Ottiene un valore DateTime denominato dalle proprietà personalizzate. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Ottiene un valore stringa denominato dalle proprietà personalizzate. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Ottiene un valore float denominato dalle proprietà personalizzate. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Ottiene un valore double denominato dalle proprietà personalizzate. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Metadati Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Restituisce la proprietà personalizzata associata a un nome specificato. Leggi [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Imposta la proprietà personalizzata associata a un nome specificato. Scrivi [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Rimuove una proprietà personalizzata associata a un nome specificato. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Imposta il modello di un'applicazione. Scrivi [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Imposta l'autore di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Imposta la categoria di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Imposta i commenti di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Imposta la proprietà azienda. Scrivi [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Imposta lo stato del contenuto di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Imposta il tipo di contenuto di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Restituisce la data di creazione di una presentazione. I valori sono in UTC. Scrivi [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Imposta la proprietà documento HyperlinkBase. Scrivi [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore. Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte. Scrivi **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Imposta le parole chiave di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Restituisce la data dell'ultima stampa di una presentazione. Scrivi [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Imposta il nome dell'ultima persona che ha modificato una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Restituisce la data dell'ultima modifica di una presentazione. I valori sono in UTC. Solo lettura in caso di [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto [IPresentation](../ipresentation/)). Può essere modificato tramite l'istanza [DocumentProperties](./) restituita dal metodo [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Vedi l'esempio nel riepilogo del metodo [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indica se i collegamenti ipertestuali in un documento sono aggiornati. Imposta questo elemento su **true** per indicare che i collegamenti sono aggiornati. Imposta questo elemento su **false** per indicare che i collegamenti sono obsoleti. Scrivi **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Imposta la proprietà manager. Scrivi [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Imposta il nome dell'applicazione. Scrivi [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Imposta il formato previsto di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Imposta il numero di revisione della presentazione. Scrivi **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indica la modalità di visualizzazione della miniatura del documento. Imposta questo elemento su **true** per abilitare il ridimensionamento della miniatura al display. Imposta questo elemento su **false** per abilitare il ritaglio della miniatura mostrando solo le sezioni che si adattano al display. Scrivi **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Determina se la presentazione è condivisa tra più persone. Scrivi **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Imposta l'oggetto di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Imposta il titolo di una presentazione. Scrivi [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Tempo totale di modifica di una presentazione. Scrivi [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Imposta una proprietà personalizzata boolean denominata. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Imposta una proprietà personalizzata intera denominata. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Imposta una proprietà personalizzata DateTime denominata. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Imposta una proprietà personalizzata stringa denominata. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Imposta una proprietà personalizzata float denominata. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Imposta una proprietà personalizzata double denominata. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello a un puntatore debole (piuttosto che condiviso). Consente lo scambio di puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

L'esempio seguente mostra come accedere alle proprietà integrate di PowerPoint [Presentation](../presentation/).
```cpp
// Instanzia la classe Presentation che rappresenta la presentazione
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
L'esempio seguente mostra come modificare le proprietà integrate di PowerPoint [Presentation](../presentation/).
```cpp
// Istanzia la classe Presentation che rappresenta la Presentazione
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Crea un riferimento all'oggetto IDocumentProperties associato alla Presentazione
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Imposta le proprietà integrate
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Salva la tua presentazione in un file
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [IDocumentProperties](../idocumentproperties/)
* Classe [IGenericCloneable](../igenericcloneable/)
* Spazio dei nomi [Aspose::Slides](../)
* Library [Aspose.Slides](../../)