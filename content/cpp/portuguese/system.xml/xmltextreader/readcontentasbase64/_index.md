---
title: ReadContentAsBase64()
second_title: Aspose.Slides para C++ - Referência da API
description: Lê o conteúdo e retorna os bytes binários decodificados em Base64.
type: docs
weight: 638
url: /pt/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Lê o conteúdo e retorna os bytes binários decodificados em **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O buffer no qual copiar o texto resultante. Este valor não pode ser **nullptr**. |
| index | **int32_t** | O deslocamento no buffer onde iniciar a cópia do resultado. |
| count | **int32_t** | O número máximo de bytes a copiar para o buffer. O número real de bytes copiados é retornado por este método. |

### Valor de Retorno

O número de bytes gravados no buffer.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)