---
title: FontsManager class
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/fontsmanager/
---
## FontsManager classe

Gestisce i caratteri in tutta la presentazione.

Il tipo FontsManager espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/it/aspose.slides/fontsmanager/font_subst_rule_list/) | Sostituzioni di carattere da utilizzare durante il rendering.<br/>            Lettura/Scrittura [`IFontSubstRuleCollection`](/slides/python-net/it/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/it/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Rappresenta la raccolta di regole FontFallBack di un utente per la gestione delle raccolte di caratteri per corrette sostituzioni tramite la funzionalità di fallback.<br/>            Lettura/Scrittura [`IFontFallBackRulesCollection`](/slides/python-net/it/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/it/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Specifica se i caratteri registrati devono essere preferiti rispetto ai caratteri incorporati con lo stesso nome e stile.<br/>            Quando abilitato, i caratteri incorporati corrispondenti vengono temporaneamente sostituiti con i caratteri registrati corrispondenti durante l'esportazione. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_substitutions/#) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione. |
| [`get_substitutions(self, slides)`](/slides/python-net/it/aspose.slides/fontsmanager/get_substitutions/#listint) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering delle diapositive specificate. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Aggiunge il carattere incorporato<br/>            Tieni presente che, quando copi qualsiasi carattere, la maggior parte dei caratteri è soggetta a copyright. Prima individua la licenza di <br/>            un carattere in anticipo e verifica che possa essere trasferita liberamente a un altro computer.Può essere sollevata un'ArgumentException se i dati del carattere sono None o se questo carattere è già incorporato |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Aggiunge il carattere incorporato<br/>            Tieni presente che, quando copi qualsiasi carattere, la maggior parte dei caratteri è soggetta a copyright. Prima individua la licenza di <br/>            un carattere in anticipo e verifica che possa essere trasferita liberamente a un altro computer.Può essere sollevata un'ArgumentException se i dati del carattere sono None o se questo carattere è già incorporato |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Sostituisci il carattere nella presentazione |
| [`replace_font(self, subst_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Sostituisci il carattere nella presentazione usando le informazioni fornite in [`FontSubstRule`](/slides/python-net/it/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Sostituisci il carattere nella presentazione usando le informazioni fornite nella raccolta di [`FontSubstRule`](/slides/python-net/it/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_fonts/#) | Restituisce i caratteri utilizzati nella presentazione |
| [`get_embedded_fonts(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_embedded_fonts/#) | Restituisce i caratteri incorporati nella presentazione |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/it/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Rimuove il carattere incorporato |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/it/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera l'array di byte che rappresenta i dati del carattere per uno stile di carattere e dati del carattere specificati. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/it/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determina il livello di incorporamento di un carattere dall'array di byte e dal nome del carattere forniti. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)