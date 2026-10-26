---
title: set_embedded_data method
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Establece información sobre los datos incrustados OLE.

```python
def set_embedded_data(self, embedded_data):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo) | Datos incrustados [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo) |

### Observaciones

Este método cambia las propiedades del objeto para reflejar los nuevos datos y 
            establece la bandera IsObjectLink a false, indicando que el objeto OLE está incrustado.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Cuando el parámetro embeddedData es None. |

### Ver también
* clase [`IOleEmbeddedDataInfo`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo)
* clase [`IOleObjectFrame`](/slides/python-net/es/aspose.slides/ioleobjectframe)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)