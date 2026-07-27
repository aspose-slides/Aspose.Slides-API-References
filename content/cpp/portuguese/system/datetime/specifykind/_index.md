---
title: SpecifyKind()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um novo objeto DateTime que representa o mesmo número de ticks do objeto DateTime especificado e representa hora local, hora UTC ou nenhuma das duas, conforme especificado pelo argumento kind.
type: docs
weight: 833
url: /pt/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) method

Constrói um novo objeto [DateTime](../) que representa o mesmo número de ticks do objeto [DateTime](../) especificado e representa hora local, hora UTC ou nenhuma das duas, conforme especificado pelo argumento **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [DateTime](../) | O objeto [DateTime](../) do qual copiar o número de ticks |
| kind | [DateTimeKind](../../datetimekind/) | Especifica se o novo objeto deve representar hora local, hora UTC ou nenhuma das duas. |

### Valor de Retorno

Um novo objeto [DateTime](../) que representa o mesmo número de ticks de **value** e o valor DateTimeKind especificado por **kind**.

## Veja Também

* Enum [DateTimeKind](../../datetimekind/)
* Classe [DateTime](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)