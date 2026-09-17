---
title: set_license method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licencia el componente.

```python
def set_license(self, license_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| license_name | **str** | Puede ser un nombre de archivo completo o abreviado o el nombre de un recurso incrustado.<br/><br/>Utilice una cadena vacía para cambiar al modo de evaluación. |

### Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del ensamblado del componente.

3. La carpeta del ensamblado que llama el cliente.

4. La carpeta del ensamblado de entrada.

5. Un recurso incrustado en el ensamblado que llama el cliente.

**Nota:** En .NET Compact Framework, intenta encontrar la licencia solo en estas ubicaciones:

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

Utilice este método para cargar una licencia desde un flujo.

### Ver también
* clase [`ILicense`](/slides/python-net/es/aspose.slides/ilicense)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)