---
title: ReadValueChunk()
second_title: Aspose.Slides para C++ Referência da API
description: Lê fluxos grandes de texto incorporados em um documento XML.
type: docs
weight: 807
url: /pt/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Lê fluxos grandes de texto incorporados em um documento XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | A matriz de caracteres que serve como buffer para o qual o conteúdo de texto é escrito. Este valor não pode ser **nullptr**. |
| index | **int32_t** | O deslocamento dentro do buffer onde o [XmlReader](../) pode começar a copiar os resultados. |
| count | **int32_t** | O número máximo de caracteres a copiar para o buffer. O número real de caracteres copiados é retornado por este método. |

### Valor de Retorno

O número de caracteres lidos para o buffer. O valor zero é retornado quando não há mais conteúdo de texto.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)