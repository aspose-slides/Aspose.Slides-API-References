---
title: ReadElementContentAsBase64()
second_title: Referência da API Aspose.Slides for C++
description: Lê o elemento e decodifica o conteúdo Base64.
type: docs
weight: 469
url: /pt/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) método

Lê o elemento e decodifica o conteúdo Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O buffer no qual copiar o texto resultante. Este valor não pode ser **nullptr**. |
| index | **int32_t** | O deslocamento no buffer onde iniciar a cópia do resultado. |
| count | **int32_t** | O número máximo de bytes a copiar para o buffer. O número real de bytes copiados é retornado por este método. |

### Valor de Retorno

O número de bytes escritos no buffer.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlNodeReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)