---
title: IFontsManager class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ifontsmanager/
---
## IFontsManager classe

Gestisce i caratteri in tutta la presentazione.

Il tipo IFontsManager espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/it/aspose.slides/ifontsmanager/font_subst_rule_list/) | Sostituzioni di carattere da utilizzare durante il rendering<br/>            Lettura/scrittura [`IFontSubstRuleCollection`](/slides/python-net/it/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/it/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Rappresenta la raccolta di regole FontFallBack di un utente per la gestione delle collezioni di caratteri per corrette sostituzioni mediante funzionalità di fallback<br/>            Lettura/scrittura [`IFontFallBackRulesCollection`](/slides/python-net/it/aspose.slides/ifontfallbackrulescollection). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_substitutions/#) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering della presentazione. |
| [`get_substitutions(self, slides)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_substitutions/#listint) | Ottiene le informazioni sui caratteri che saranno sostituiti durante il rendering delle diapositive specificate. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Aggiunge il carattere incorporato.<br/>            Tieni presente che, quando copi qualsiasi carattere, la maggior parte è protetta da copyright. Prima individua la licenza di <br/>            un carattere in anticipo e verifica che possa essere trasferita liberamente su un'altra macchina. Un'ArgumentException può essere generata se i dati del carattere sono None o se questo carattere è già incorporato |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Aggiunge il carattere incorporato<br/>            Tieni presente che, quando aggiungi qualsiasi carattere, la maggior parte è protetta da copyright. Prima individua la licenza di <br/>            un carattere in anticipo e verifica che possa essere trasferita liberamente su un'altra macchina. Un'ArgumentException può essere generata se i dati del carattere sono None o se questo carattere è già incorporato |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/it/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Sostituisci il carattere nella presentazione |
| [`replace_font(self, subst_rule)`](/slides/python-net/it/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Sostituisci il carattere nella presentazione usando le informazioni fornite in [`IFontSubstRule`](/slides/python-net/it/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/it/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Sostituisci il carattere nella presentazione usando le informazioni fornite nella collezione di [`IFontSubstRule`](/slides/python-net/it/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_fonts/#) | Restituisce i caratteri utilizzati nella presentazione |
| [`get_embedded_fonts(self)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Restituisce i caratteri incorporati nella presentazione |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/it/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Rimuove il carattere incorporato |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera l'array di byte che rappresenta i dati del carattere per uno stile di carattere e dati del carattere specificati. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/it/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determina il livello di incorporamento di un carattere dall'array di byte e dal nome del carattere forniti. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)