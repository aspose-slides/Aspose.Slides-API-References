---
title: apply_default_paragraph_indents_shifts method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Imposta le deviazioni predefinite non zero per l'Indent e il MarginLeft del paragrafo efficace quando i bullet sono abilitati (come fa PowerPoint se si attivano i bullet/numero nei paragrafi). Se i bullet sono disabilitati, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disattivano i bullet/numero nei paragrafi). Le deviazioni di indentazione sono applicate in base al contesto corrente del bullet – IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Le deviazioni di indentazione non zero sono applicate all'Indent e al MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Chiamare questo metodo non ha effetto e genera **System.InvalidOperationException** nei seguenti casi:<br/>            se l'oggetto formattato genitore non è un paragrafo (ad esempio chiamare ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() genererà un'eccezione);<br/>            oppure se il paragrafo non è stato aggiunto a nessuna collezione ITextFrame.Paragraphs (aggiungilo prima); |



### Vedi anche
* classe [`IBulletFormat`](/slides/python-net/it/aspose.slides/ibulletformat)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)