---
title: delete_embedded_binary_objects property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects propriedade
Determina se Aspose.Slides excluirá todos os objetos binários incorporados durante o carregamento da apresentação.

Os tipos de objetos binários incorporados:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/pt/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/pt/aspose.slides/icontrol/active_x_control_binary)

Leitura/gravação **bool**.

### Observações

O padrão é **false** .

### Definição:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Veja Também
* classe [`ILoadOptions`](/slides/python-net/pt/aspose.slides/iloadoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)