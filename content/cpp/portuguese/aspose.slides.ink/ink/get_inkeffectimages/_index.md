---
title: get_InkEffectImages()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém a coleção de imagens personalizadas usadas para simular efeitos visuais de pincéis de tinta. Essas imagens são usadas ao renderizar tinta com valores específicos de InkEffectType, como Galaxy, Rainbow, etc. Ao fornecer suas próprias imagens, você pode controlar como cada efeito de tinta aparece.
type: docs
weight: 14
url: /pt/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() método

Obtém a coleção de imagens personalizadas usadas para simular efeitos visuais de pincéis de tinta. Essas imagens são usadas ao renderizar tinta com valores específicos de [InkEffectType](../../inkeffecttype/), como Galaxy, Rainbow, etc. Ao fornecer suas próprias imagens, você pode controlar como cada efeito de tinta aparece.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Observações

Esta propriedade permite substituir as texturas padrão de efeito de tinta por imagens definidas pelo usuário, o que é particularmente útil quando os recursos padrão são restritos por licenciamento ou indisponíveis em tempo de execução.

Cada entrada no dicionário deve associar um valor [InkEffectType](../../inkeffecttype/) a um objeto [IImage](../../../aspose.slides/iimage/) correspondente (por exemplo, Bitmap, ou uma interface de imagem **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Veja Também

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [IImage](../../../aspose.slides/iimage/)
* Classe [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)