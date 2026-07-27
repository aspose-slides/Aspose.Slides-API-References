---
title: Debug
second_title: Referência da API Aspose.Slides para C++
description: Coleção de métodos de depuração que permitem enviar informações de depuração para ouvintes registrados. Todas as funções de saída funcionam apenas no modo Debug. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 105
url: /pt/system.diagnostics/debug/
---
## Struct de Depuração

Coleção de métodos de depuração que permitem enviar informações de depuração para ouvintes registrados. Todas as funções de saída funcionam apenas em [Debug](./). Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.

```cpp
class Debug
```

## Métodos

| Method | Description |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Verifica a condição e envia informações em caso de falha. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Verifica a condição e envia informações em caso de falha. |
| static void [Assert](./assert/)(**bool**, const char *) | Verifica a condição e envia informações em caso de falha. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Verifica a condição e envia informações em caso de falha. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Envia mensagem de falha. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Acessa a lista estática de ouvintes. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Imprime mensagem na interface de depuração. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Imprime mensagem na interface de depuração. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Escreve string na interface de depuração. |
| static void [Write](./write/)(const char_t *) | Escreve string na interface de depuração. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Escreve string na interface de depuração se a condição for verdadeira. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Escreve linha na interface de depuração. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Escreve linha na interface de depuração. |
| static void [WriteLine](./writeline/)(const char_t *) | Escreve linha na interface de depuração. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Escreve linha na interface de depuração. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Escreve linha na interface de depuração se a condição for verdadeira. |

## Veja Também

* Namespace [System::Diagnostics](../)
* Library [Aspose.Slides](../../)