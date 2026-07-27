---
title: get_Images()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a coleção de todas as imagens na apresentação. Somente leitura IImageCollection.
type: docs
weight: 209
url: /pt/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() método


Retorna a coleção de todas as imagens na apresentação. Somente leitura [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Observações


Os exemplos a seguir mostram como adicionar uma imagem como BLOB no PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// cria uma nova apresentação à qual a imagem será adicionada.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Vamos adicionar a imagem à apresentação - escolhemos o comportamento KeepLocked porque nós
// NÃO pretendemos acessar o arquivo "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Salva a apresentação. Enquanto uma apresentação grande é gerada, o consumo de memória
// permanece baixo ao longo do ciclo de vida do objeto pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 Os exemplos a seguir adicionam um hyperlink a uma imagem no PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Adiciona a imagem à apresentação
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Cria um quadro de imagem no slide 1 baseado na imagem adicionada anteriormente
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImageCollection](../../iimagecollection/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)