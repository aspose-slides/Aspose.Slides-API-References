---
title: ReadContentAsBinHex()
second_title: Referência da API Aspose.Slides for C++
description: Lê o conteúdo e devolve os bytes binários decodificados em BinHex.
type: docs
weight: 781
url: /pt/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Lê o conteúdo e devolve os bytes binários decodificados em **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O buffer no qual copiar o texto resultante. Este valor não pode ser **nullptr**. |
| index | **int32_t** | O deslocamento no buffer onde iniciar a cópia do resultado. |
| count | **int32_t** | O número máximo de bytes a copiar para o buffer. O número real de bytes copiados é retornado por este método. |

### Valor de retorno

O número de bytes gravados no buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)