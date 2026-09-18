---
title: register_ink_effect_image method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registra uma imagem na coleção de imagens personalizadas usadas para simular efeitos visuais para pincéis de tinta.
Essas imagens são usadas ao renderizar tinta com valores específicos [`InkEffectType`](/slides/python-net/pt/aspose.slides.ink/inkeffecttype), como Galaxy, Rainbow, etc. Ao fornecer suas próprias imagens, você pode controlar como cada efeito de tinta aparece.

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/pt/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/pt/aspose.slides/iimage) |  |

### Observações

Este método permite substituir as texturas de efeito de tinta padrão por texturas definidas pelo usuário, o que é particularmente útil quando os recursos padrão são restritos por licenciamento ou indisponíveis em tempo de execução. Cada par de valor registrado deve associar um valor [`InkEffectType`](/slides/python-net/pt/aspose.slides.ink/inkeffecttype) a um objeto [`IImage`](/slides/python-net/pt/aspose.slides/iimage) correspondente (por exemplo, Bitmap ou uma interface de imagem Aspose).

### Ver também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`Ink`](/slides/python-net/pt/aspose.slides.ink/ink)
* enumeração [`InkEffectType`](/slides/python-net/pt/aspose.slides.ink/inkeffecttype)
* módulo [`aspose.slides.ink`](/slides/python-net/pt/aspose.slides.ink)
* biblioteca [`Aspose.Slides`](/slides/python-net)