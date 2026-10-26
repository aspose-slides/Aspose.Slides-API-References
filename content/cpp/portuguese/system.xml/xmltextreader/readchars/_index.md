---
title: ReadChars()
second_title: Referência da API Aspose.Slides para C++
description: Lê o conteúdo de texto de um elemento para um buffer de caracteres. Este método foi projetado para ler fluxos grandes de texto incorporado chamando-o sucessivamente.
type: docs
weight: 755
url: /pt/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

Lê o conteúdo de texto de um elemento para um buffer de caracteres. Este método foi projetado para ler fluxos grandes de texto incorporado chamando-o sucessivamente.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A matriz de caracteres que serve como buffer ao qual o conteúdo de texto é escrito. |
| index | **int32_t** | A posição dentro de **buffer** onde o método pode começar a gravar o conteúdo de texto. |
| count | **int32_t** | O número de caracteres a gravar em **buffer**. |

### Valor de Retorno

O número de caracteres lidos. Isso pode ser 0 se o leitor não estiver posicionado em um elemento ou se não houver mais conteúdo de texto a ser retornado no contexto atual.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)