---
title: FontsManager class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/fontsmanager/
---
## FontsManager classe

Gestisce i font nella presentazione.

Il tipo FontsManager espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/it/aspose.slides/fontsmanager/font_subst_rule_list/) | Sostituzioni di font da usare durante il rendering.<br/>            Lettura/scrittura [`IFontSubstRuleCollection`](/slides/python-net/it/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/it/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Rappresenta la raccolta di regole FontFallBack di un utente per la gestione delle raccolte di font per corrette sostituzioni tramite funzionalità di fallback<br/>            Lettura/scrittura [`IFontFallBackRulesCollection`](/slides/python-net/it/aspose.slides/ifontfallbackrulescollection). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_substitutions/#) | Restituisce le informazioni sui font che saranno sostituiti durante il rendering della presentazione. |
| [`get_substitutions(self, slides)`](/slides/python-net/it/aspose.slides/fontsmanager/get_substitutions/#listint) | Restituisce le informazioni sui font che saranno sostituiti durante il rendering delle diapositive specificate. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Aggiunge il font incorporato<br/>            Tieni presente che, quando copi qualsiasi font, la maggior parte dei font è protetta da copyright. Prima individua la licenza di <br/>            un font in anticipo e verifica che possa essere trasferita liberamente su un'altra macchina. Un'ArgumentException può essere sollevata se i dati del font sono None o se questo font è già incorporato |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Aggiunge il font incorporato<br/>            Tieni presente che, quando copi qualsiasi font, la maggior parte dei font è protetta da copyright. Prima individua la licenza di <br/>            un font in anticipo e verifica che possa essere trasferita liberamente su un'altra macchina. Un'ArgumentException può essere sollevata se i dati del font sono None o se questo font è già incorporato |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Sostituisci il font nella presentazione |
| [`replace_font(self, subst_rule)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Sostituisci il font nella presentazione usando le informazioni fornite in [`FontSubstRule`](/slides/python-net/it/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/it/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Sostituisci il font nella presentazione usando le informazioni fornite nella raccolta di [`FontSubstRule`](/slides/python-net/it/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_fonts/#) | Restituisce i font usati nella presentazione |
| [`get_embedded_fonts(self)`](/slides/python-net/it/aspose.slides/fontsmanager/get_embedded_fonts/#) | Restituisce i font incorporati nella presentazione |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/it/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Rimuove il font incorporato |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/it/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera l'array di byte che rappresenta i dati del font per uno stile e dati del font specificati. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/it/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determina il livello di incorporamento di un font dall'array di byte e dal nome del font forniti. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)