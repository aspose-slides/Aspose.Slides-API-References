---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides para Referência da API C++
description: Lê o elemento e decodifica o conteúdo BinHex.
type: docs
weight: 612
url: /pt/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) método

Lê o elemento e decodifica o conteúdo BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Classe [XmlValidatingReader](../)
* Espaço de Nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)