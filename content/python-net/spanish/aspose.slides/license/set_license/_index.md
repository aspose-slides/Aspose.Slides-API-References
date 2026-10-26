---
title: set_license method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licencia el componente.


```python
def set_license(self, license_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| license_name | **str** | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado.<br/><br/>            Use una cadena vacía para cambiar al modo de evaluación. |

### Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:


1. Ruta explícita.

2. La carpeta del ensamblado del componente.

3. La carpeta del ensamblado que llama el cliente.

4. La carpeta del ensamblado de entrada.

5. Un recurso incrustado en el ensamblado que llama el cliente.

**Nota:** En el .NET Compact Framework, intenta encontrar la licencia solo en estas ubicaciones:


1. Ruta explícita.

2. Un recurso incrustado en el ensamblado que llama el cliente.


## set_license(self, stream) {#iorawiobase}
Licencia el componente.


```python
def set_license(self, stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Un flujo que contiene la licencia. |

### Observaciones

Use este método para cargar una licencia desde un flujo.



### Ver también
* clase [`License`](/slides/python-net/es/aspose.slides/license)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)