---
title: IDocumentProperties class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/idocumentproperties/
---
## IDocumentProperties classe

Rappresenta le proprietà di una presentazione.

Il tipo IDocumentProperties espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/it/aspose.slides/idocumentproperties/app_version/) | Restituisce la versione dell'applicazione.<br/>            Solo lettura **str**. |
| [`name_of_application`](/slides/python-net/it/aspose.slides/idocumentproperties/name_of_application/) | Restituisce o imposta il nome dell'applicazione.<br/>            Lettura/Scrittura **str**. |
| [`company`](/slides/python-net/it/aspose.slides/idocumentproperties/company/) | Restituisce o imposta la proprietà dell'azienda.<br/>            Lettura/Scrittura **str**. |
| [`manager`](/slides/python-net/it/aspose.slides/idocumentproperties/manager/) | Restituisce o imposta la proprietà del responsabile.<br/>            Lettura/Scrittura **str**. |
| [`presentation_format`](/slides/python-net/it/aspose.slides/idocumentproperties/presentation_format/) | Restituisce o imposta il formato previsto di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`shared_doc`](/slides/python-net/it/aspose.slides/idocumentproperties/shared_doc/) | Determina se la presentazione è condivisa tra più persone.<br/>            Lettura/Scrittura **bool**. |
| [`application_template`](/slides/python-net/it/aspose.slides/idocumentproperties/application_template/) | Restituisce o imposta il modello di un'applicazione.<br/>            Lettura/Scrittura **str**. |
| [`total_editing_time`](/slides/python-net/it/aspose.slides/idocumentproperties/total_editing_time/) | Tempo totale di modifica di una presentazione.<br/>            Lettura/Scrittura **System.TimeSpan**. |
| [`title`](/slides/python-net/it/aspose.slides/idocumentproperties/title/) | Restituisce o imposta il titolo di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`subject`](/slides/python-net/it/aspose.slides/idocumentproperties/subject/) | Restituisce o imposta l'oggetto di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`author`](/slides/python-net/it/aspose.slides/idocumentproperties/author/) | Restituisce o imposta l'autore di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`keywords`](/slides/python-net/it/aspose.slides/idocumentproperties/keywords/) | Restituisce o imposta le parole chiave di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`comments`](/slides/python-net/it/aspose.slides/idocumentproperties/comments/) | Restituisce o imposta i commenti di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`category`](/slides/python-net/it/aspose.slides/idocumentproperties/category/) | Restituisce o imposta la categoria di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`created_time`](/slides/python-net/it/aspose.slides/idocumentproperties/created_time/) | Restituisce la data in cui è stata creata una presentazione.<br/>            I valori sono in UTC.<br/>            Lettura/Scrittura **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/it/aspose.slides/idocumentproperties/last_saved_time/) | Restituisce la data in cui una presentazione è stata modificata per l'ultima volta.<br/>            I valori sono in UTC.P<br/>            Solo lettura nel caso di Presentation.DocumentProperties (perché verrà aggiornato internamente durante il processo di salvataggio dell'oggetto IPresentation). <br/>            Può essere modificato tramite l'istanza DocumentProperties restituita dal metodo [`IPresentationInfo.read_document_properties`](/slides/python-net/it/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Si prega di vedere l'esempio in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** riepilogo del metodo. |
| [`last_printed`](/slides/python-net/it/aspose.slides/idocumentproperties/last_printed/) | Restituisce la data in cui una presentazione è stata stampata l'ultima volta.<br/>            Lettura/Scrittura **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/it/aspose.slides/idocumentproperties/last_saved_by/) | Restituisce o imposta il nome dell'ultima persona che ha modificato una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`revision_number`](/slides/python-net/it/aspose.slides/idocumentproperties/revision_number/) | Restituisce o imposta il numero di revisione della presentazione.<br/>            Lettura/Scrittura **int**. |
| [`content_status`](/slides/python-net/it/aspose.slides/idocumentproperties/content_status/) | Restituisce o imposta lo stato del contenuto di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`content_type`](/slides/python-net/it/aspose.slides/idocumentproperties/content_type/) | Restituisce o imposta il tipo di contenuto di una presentazione.<br/>            Lettura/Scrittura **str**. |
| [`hyperlink_base`](/slides/python-net/it/aspose.slides/idocumentproperties/hyperlink_base/) | Restituisce o imposta la proprietà di documento HyperlinkBase.<br/>            Lettura/Scrittura **str**. |
| [`scale_crop`](/slides/python-net/it/aspose.slides/idocumentproperties/scale_crop/) | Indica la modalità di visualizzazione della miniatura del documento.<br/>            Imposta questo elemento su **true** per abilitare il ridimensionamento della miniatura del documento al display.<br/>            Imposta questo elemento su **false** per abilitare il ritaglio della miniatura del documento in modo da mostrare solo le sezioni che si adattano al display.<br/>            Lettura/Scrittura **bool**. |
| [`links_up_to_date`](/slides/python-net/it/aspose.slides/idocumentproperties/links_up_to_date/) | Indica se i collegamenti ipertestuali in un documento sono aggiornati.<br/>            Imposta questo elemento su **true** per indicare che i collegamenti ipertestuali sono aggiornati.<br/>            Imposta questo elemento su **false** per indicare che i collegamenti ipertestuali sono obsoleti.<br/>            Lettura/Scrittura **bool**. |
| [`hyperlinks_changed`](/slides/python-net/it/aspose.slides/idocumentproperties/hyperlinks_changed/) | Specifica che uno o più collegamenti ipertestuali in questa parte sono stati aggiornati esclusivamente in questa parte da un produttore.<br/>            Il prossimo produttore che aprirà questo documento dovrà aggiornare le relazioni dei collegamenti ipertestuali con i nuovi collegamenti specificati in questa parte.<br/>            Lettura/Scrittura **bool**. |
| [`slides`](/slides/python-net/it/aspose.slides/idocumentproperties/slides/) | Specifica il numero totale di diapositive in un documento di presentazione.<br/it/>            Solo lettura **int**. |
| [`hidden_slides`](/slides/python-net/it/aspose.slides/idocumentproperties/hidden_slides/) | Specifica il numero di diapositive nascoste in un documento di presentazione.<br/>            Solo lettura **int**. |
| [`notes`](/slides/python-net/it/aspose.slides/idocumentproperties/notes/) | Specifica il numero di diapositive in una presentazione contenenti note.<br/>            Solo lettura **int**. |
| [`paragraphs`](/slides/python-net/it/aspose.slides/idocumentproperties/paragraphs/) | Specifica il numero totale di paragrafi trovati in un documento, se applicabile.<br/>            Solo lettura **int**. |
| [`words`](/slides/python-net/it/aspose.slides/idocumentproperties/words/) | Specifica il numero totale di parole contenute in un documento.<br/>            Solo lettura **int**. |
| [`multimedia_clips`](/slides/python-net/it/aspose.slides/idocumentproperties/multimedia_clips/) | Specifica il numero totale di clip audio o video presenti nel documento.<br/>            Solo lettura **int**. |
| [`titles_of_parts`](/slides/python-net/it/aspose.slides/idocumentproperties/titles_of_parts/) | Specifica il titolo di ogni parte del documento.<br/>            Queste parti non sono parti del documento ma rappresentazioni concettuali delle sezioni del documento.<br/>            Solo lettura **List[str]**. |
| [`heading_pairs`](/slides/python-net/it/aspose.slides/idocumentproperties/heading_pairs/) | Indica il raggruppamento delle parti del documento e il numero di parti in ciascun gruppo.<br/>            Solo lettura **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/it/aspose.slides/idocumentproperties/count_of_custom_properties/) | Restituisce il numero di proprietà personalizzate effettivamente contenute in una raccolta.<br/>            Solo lettura **int**. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ottiene un valore booleano con nome dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ottiene un valore intero con nome dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ottiene un valore DateTime con nome dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ottiene un valore stringa con nome dalle proprietà personalizzate. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Imposta una proprietà personalizzata boolean con nome. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Imposta una proprietà personalizzata intera con nome. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Imposta una proprietà personalizzata DateTime con nome. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Imposta una proprietà personalizzata stringa con nome. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Imposta una proprietà personalizzata float con nome. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/it/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Imposta una proprietà personalizzata double con nome. |
| [`get_custom_property_name(self, index)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Restituisce il nome di una proprietà personalizzata all'indice specificato. |
| [`remove_custom_property(self, name)`](/slides/python-net/it/aspose.slides/idocumentproperties/remove_custom_property/#str) | Rimuove una proprietà personalizzata associata a un nome specificato. |
| [`contains_custom_property(self, name)`](/slides/python-net/it/aspose.slides/idocumentproperties/contains_custom_property/#str) | Verifica la presenza di una proprietà personalizzata con un nome specificato. |
| [`clear_custom_properties(self)`](/slides/python-net/it/aspose.slides/idocumentproperties/clear_custom_properties/#) | Rimuove tutte le proprietà personalizzate. |
| [`clear_built_in_properties(self)`](/slides/python-net/it/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Cancella e imposta i valori predefiniti per tutte le proprietà integrate. |
| [`get_sensitivity_labels(self)`](/slides/python-net/it/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Ottiene un array di etichette di sensibilità dalle proprietà personalizzate del documento (Metadati Microsoft Information Protection SDK). |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)