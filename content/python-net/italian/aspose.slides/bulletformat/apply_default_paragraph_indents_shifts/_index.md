---
title: apply_default_paragraph_indents_shifts method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Imposta gli spostamenti predefiniti diversi da zero per l'Indent e il MarginLeft del paragrafo effettivo quando i bullet sono abilitati (come fa PowerPoint se si attivano i bullet/numerazione del paragrafo). Se i bullet sono disabilitati, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disattivano i bullet/numerazione del paragrafo). Gli spostamenti di indentazione vengono applicati in base al contesto corrente del bullet – IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione diversi da zero vengono applicati all'Indent e al MarginLeft effettivi del paragrafo corrente (rendendo i valori di risultato valori locali).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Invocare questo metodo non ha importanza e genera **System.InvalidOperationException** nei seguenti casi:<br/>            se l'oggetto formattato padre non è un paragrafo (ad esempio chiamando ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() verrà generata un'eccezione);<br/>            o se il paragrafo non è stato aggiunto a nessuna collezione ITextFrame.Paragraphs (aggiungilo prima); |



### Vedi anche
* classe [`BulletFormat`](/slides/python-net/it/aspose.slides/bulletformat)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)