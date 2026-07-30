---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta gli spostamenti predefiniti non-zero per l'Indent e il MarginLeft effettivi del paragrafo quando i punti elenco sono abilitati (come fa PowerPoint se si attivano i punti elenco/numerazione nei paragrafi). Se i punti elenco sono disabilitati, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disattivano i punti elenco/numerazione nei paragrafi). Gli spostamenti degli Indent vengono applicati in base al contesto corrente del bullet – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti non-zero degli Indent vengono applicati all'Indent e al MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali)."
type: docs
weight: 235
url: /it/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() metodo


Imposta gli spostamenti predefiniti non-zero per l'Indent e il MarginLeft del paragrafo effettivo quando i punti elenco sono abilitati (come fa PowerPoint se si attivano i punti elenco/numerazione dei paragrafi). Se i punti elenco sono disabilitati, allora semplicemente ripristina l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disattivano i punti elenco/numerazione dei paragrafi). Gli spostamenti degli Indent sono applicati in base al contesto corrente del bullet – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti non-zero degli Indent sono applicati all'Indent e al MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali).

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```


## Vedi anche

* Classe [BulletFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)