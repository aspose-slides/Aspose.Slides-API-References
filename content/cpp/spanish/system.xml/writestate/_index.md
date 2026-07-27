---
title: WriteState
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica el estado del XmlWriter.
type: docs
weight: 755
url: /es/system.xml/writestate/
---
## Enumeración WriteState

Especifica el estado del [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Start | 0 | Indica que el método XmlWriter::Write aún no ha sido llamado. |
| Prolog | 1 | Indica que se está escribiendo el prólogo. |
| Element | 2 | Indica que se está escribiendo una etiqueta de inicio de elemento. |
| Attribute | 3 | Indica que se está escribiendo un valor de atributo. |
| Content | 4 | Indica que se está escribiendo el contenido del elemento. |
| Closed | 5 | Indica que el método [XmlWriter::Close](../xmlwriter/close/) ha sido llamado. |
| Error | 6 | Se ha lanzado una excepción, lo que ha dejado al [XmlWriter](../xmlwriter/) en un estado no válido. Puede llamar al método [XmlWriter::Close](../xmlwriter/close/) para colocar al [XmlWriter](../xmlwriter/) en el estado [WriteState::Closed](./). Cualquier otra llamada al método [XmlWriter](../xmlwriter/) resulta en una InvalidOperationException. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)