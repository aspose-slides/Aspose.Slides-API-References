---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta gli spostamenti predefiniti diversi da zero per l'Indent e il MarginLeft del paragrafo efficace quando i punti elenco sono abilitati (come fa PowerPoint se si abilita l'elenco puntato/numerazione dei paragrafi). Se i punti elenco sono disabilitati, viene semplicemente ripristinato l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disabilita l'elenco puntato/numerazione dei paragrafi). Gli spostamenti degli indent vengono applicati in relazione al contesto corrente del punto elenco – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti degli indent diversi da zero vengono applicati all'Indent e al MarginLeft efficaci del paragrafo corrente (rendendo i valori risultanti valori locali)."
type: docs
weight: 235
url: /it/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() metodo

Imposta gli spostamenti predefiniti diversi da zero per l'Indent e il MarginLeft del paragrafo efficace quando l'elenco puntato è abilitato (come fa PowerPoint se si attiva l'elenco puntato/numero nei paragrafi). Se l'elenco puntato è disabilitato, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disattiva l'elenco puntato/numero nei paragrafi). Gli spostamenti degli indent sono applicati in base al contesto corrente del punto elenco – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indent diversi da zero sono applicati all'Indent e al MarginLeft efficaci del paragrafo corrente (rendendo i valori risultati valori locali).

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## Vedi anche

* Classe [IBulletFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)