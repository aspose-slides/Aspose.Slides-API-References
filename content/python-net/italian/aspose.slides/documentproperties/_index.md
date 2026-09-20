---
title: DocumentProperties class
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides/documentproperties/
---
## DocumentProperties classe

Rappresenta le proprietà di una presentazione.

Il tipo DocumentProperties espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/documentproperties/__init__/#) | Inizializza una nuova istanza della classe [`DocumentProperties`](/slides/python-net/it/aspose.slides/documentproperties). |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`app_version`](/slides/python-net/it/aspose.slides/documentproperties/app_version/) | Restituisce la versione dell'applicazione.<br/>            Solo lettura **str**. |
| [`name_of_application`](/slides/python-net/it/aspose.slides/documentproperties/name_of_application/) | Restituisce o imposta il nome dell'applicazione.<br/>            Lettura/scrittura **str**. |
| [`company`](/slides/python-net/it/aspose.slides/documentproperties/company/) | Restituisce o imposta la proprietà azienda.<br/>            Lettura/scrittura **str**. |
| [`manager`](/slides/python-net/it/aspose.slides/documentproperties/manager/) | Restituisce o imposta la proprietà manager.<br/>            Lettura/scrittura **str**. |
| [`presentation_format`](/slides/python-net/it/aspose.slides/documentproperties/presentation_format/) | Restituisce o imposta il formato previsto di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`shared_doc`](/slides/python-net/it/aspose.slides/documentproperties/shared_doc/) | Determina se la presentazione è condivisa tra più persone.<br/>            Lettura/scrittura **bool**. |
| [`application_template`](/slides/python-net/it/aspose.slides/documentproperties/application_template/) | Restituisce o imposta il modello di un'applicazione.<br/>            Lettura/scrittura **str**. |
| [`total_editing_time`](/slides/python-net/it/aspose.slides/documentproperties/total_editing_time/) | Tempo totale di modifica di una presentazione.<br/>            Lettura/scrittura **System.TimeSpan**. |
| [`title`](/slides/python-net/it/aspose.slides/documentproperties/title/) | Restituisce o imposta il titolo di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`subject`](/slides/python-net/it/aspose.slides/documentproperties/subject/) | Restituisce o imposta l'oggetto di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`author`](/slides/python-net/it/aspose.slides/documentproperties/author/) | Restituisce o imposta l'autore di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`keywords`](/slides/python-net/it/aspose.slides/documentproperties/keywords/) | Restituisce o imposta le parole chiave di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`comments`](/slides/python-net/it/aspose.slides/documentproperties/comments/) | Restituisce o imposta i commenti di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`category`](/slides/python-net/it/aspose.slides/documentproperties/category/) | Restituisce o imposta la categoria di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`created_time`](/slides/python-net/it/aspose.slides/documentproperties/created_time/) | Restituisce la data in cui è stata creata una presentazione.<br/>            I valori sono in UTC.<br/>            Lettura/scrittura **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/it/aspose.slides/documentproperties/last_saved_time/) | Restituisce la data in cui una presentazione è stata modificata l'ultima volta.<br/>            I valori sono in UTC.<br/>            Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). <br/>            Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [`IPresentationInfo.read_document_properties`](/slides/python-net/it/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Si prega di consultare l'esempio nel riepilogo del metodo **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/it/aspose.slides/documentproperties/last_printed/) | Restituisce la data dell'ultima stampa di una presentazione.<br/>            Lettura/scrittura **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/it/aspose.slides/documentproperties/last_saved_by/) | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione.<br/>            Lettura/scrittura **str**. |
| [`revision_number`](/slides/python-net/it/aspose.slides/documentproperties/revision_number/) | Restituisce o imposta il numero di revisione della presentazione.<br/>            Lettura/scrittura **int**. |
| [`content_status`](/slides/python-net/it/aspose.slides/documentproperties/content_status/) | Restituisce o imposta lo stato del contenuto di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`content_type`](/slides/python-net/it/aspose.slides/documentproperties/content_type/) | Restituisce o imposta il tipo di contenuto di una presentazione.<br/>            Lettura/scrittura **str**. |
| [`hyperlink_base`](/slides/python-net/it/aspose.slides/documentproperties/hyperlink_base/) | Restituisce o imposta la proprietà HyperlinkBase del documento.<br/>            Lettura/scrittura **str**. |
| [`count_of_custom_properties`](/slides/python-net/it/aspose.slides/documentproperties/count_of_custom_properties/) | Restituisce il numero di proprietà personalizzate effettivamente contenute in una raccolta.<br/>            Solo lettura **int**. |
| [`scale_crop`](/slides/python-net/it/aspose.slides/documentproperties/scale_crop/) | Indica la modalità di visualizzazione della miniatura del documento.<br/>            Impostare questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento allo schermo.<br/>            Impostare questo elemento su **false** per abilitare il ritaglio della miniatura del documento per mostrare solo le sezioni che si adattano allo schermo.<br/>            Lettura/scrittura **bool**. |
| [`links_up_to_date`](/slides/python-net/it/aspose.slides/documentproperties/links_up_to_date/) | Indica se i collegamenti ipertestuali in un documento sono aggiornati.<br/>            Impostare questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati.<br/>            Impostare questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti.<br/>            Lettura/scrittura **bool**. |
| [`hyperlinks_changed`](/slides/python-net/it/aspose.slides/documentproperties/hyperlinks_changed/) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore.<br/>            Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte.<br/>            Lettura/scrittura **bool**. |
| [`slides`](/slides/python-net/it/aspose.slides/documentproperties/slides/) | Restituisce il numero totale di diapositive in un documento di presentazione.<br/it/>            Solo lettura **int**. |
| [`hidden_slides`](/slides/python-net/it/aspose.slides/documentproperties/hidden_slides/) | Restituisce il numero di diapositive nascoste in un documento di presentazione.<br/>            Solo lettura **int**. |
| [`notes`](/slides/python-net/it/aspose.slides/documentproperties/notes/) | Restituisce il numero di diapositive in una presentazione che contengono note.<br/>            Solo lettura **int**. |
| [`paragraphs`](/slides/python-net/it/aspose.slides/documentproperties/paragraphs/) | Restituisce il numero totale di paragrafi trovati in un documento, se applicabile.<br/>            Solo lettura **int**. |
| [`words`](/slides/python-net/it/aspose.slides/documentproperties/words/) | Restituisce il numero totale di parole contenute in un documento.<br/>            Solo lettura **int**. |
| [`multimedia_clips`](/slides/python-net/it/aspose.slides/documentproperties/multimedia_clips/) | Restituisce il numero totale di clip audio o video presenti nel documento.<br/>            Solo lettura **int**. |
| [`titles_of_parts`](/slides/python-net/it/aspose.slides/documentproperties/titles_of_parts/) | Specifica il titolo di ciascuna parte del documento.<br/>            Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento.<br/>            Solo lettura **List[str]**. |
| [`heading_pairs`](/slides/python-net/it/aspose.slides/documentproperties/heading_pairs/) | Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo.<br/>            Solo lettura **List[IHeadingPair]**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ottiene un valore booleano nominato dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ottiene un valore intero nominato dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ottiene un valore DateTime nominato dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ottiene un valore stringa nominato dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Imposta una proprietà personalizzata booleana nominata. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Imposta una proprietà personalizzata intera nominata. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Imposta una proprietà personalizzata DateTime nominata. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Imposta una proprietà personalizzata stringa nominata. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Imposta una proprietà personalizzata float nominata. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Imposta una proprietà personalizzata double nominata. |
| [`get_custom_property_name(self, index)`](/slides/python-net/it/aspose.slides/documentproperties/get_custom_property_name/#int) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [`remove_custom_property(self, name)`](/slides/python-net/it/aspose.slides/documentproperties/remove_custom_property/#str) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [`contains_custom_property(self, name)`](/slides/python-net/it/aspose.slides/documentproperties/contains_custom_property/#str) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [`clear_custom_properties(self)`](/slides/python-net/it/aspose.slides/documentproperties/clear_custom_properties/#) | Rimuove tutte le proprietà personalizzate. |
| [`get_sensitivity_labels(self)`](/slides/python-net/it/aspose.slides/documentproperties/get_sensitivity_labels/#) | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Metadati SDK di Microsoft Information Protection). |
| [`clear_built_in_properties(self)`](/slides/python-net/it/aspose.slides/documentproperties/clear_built_in_properties/#) | Cancella e imposta i valori predefiniti per tutte le proprietà incorporate. |
| [`clone(self)`](/slides/python-net/it/aspose.slides/documentproperties/clone/#) | Clona l'oggetto corrente |
| [`clone_t(self)`](/slides/python-net/it/aspose.slides/documentproperties/clone_t/#) | Clona l'oggetto corrente |

### Vedi anche
* classe [`DocumentProperties`](/slides/python-net/it/aspose.slides/documentproperties)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)