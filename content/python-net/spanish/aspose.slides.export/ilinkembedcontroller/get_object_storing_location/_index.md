---
title: get_object_storing_location method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Determina dónde se debe almacenar el objeto.
            Este método se llama una vez por cada id de objeto.
            No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con diferentes id.

### Devuelve

Decisión



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | **int** | Id del objeto. Este id es único en toda la operación de guardado. |
| entity_data | **bytes** | Datos binarios del objeto. Este parámetro puede ser None, si los datos binarios del objeto aún no se han generado. |
| semantic_name | **str** | Algún texto corto que describe el significado del objeto. El controlador puede usarlo como parte del nombre externo del objeto, pero depende del despachador garantizar que los nombres sean únicos y contengan solo los caracteres permitidos. |
| content_type | **int** | Tipo MIME del objeto. |
| recomended_extension | **str** | Extensión de nombre de archivo, recomendada para este tipo MIME. |



### Ver también
* clase [`ILinkEmbedController`](/slides/python-net/es/aspose.slides.export/ilinkembedcontroller)
* enumeración [`LinkEmbedDecision`](/slides/python-net/es/aspose.slides.export/linkembeddecision)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)