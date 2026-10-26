---
title: CompressImage()
second_title: Referência da API Aspose.Slides para C++
description: Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.
type: docs
weight: 443
url: /pt/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) método

Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Se verdadeiro, o método removerá as áreas recortadas da imagem, reduzindo ainda mais seu tamanho. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | A resolução alvo para compressão, especificada como um valor da enumeração [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Valor de Retorno

Um **bool** indicando se a imagem foi comprimida com sucesso. Retorna ****true****

## Observações

Este método altera o tamanho e a resolução da imagem de forma semelhante ao recurso "Formato da Imagem -> Comprimir Imagens" do PowerPoint.

se a imagem foi redimensionada ou recortada, caso contrário ****false****

. 

O exemplo a seguir demonstra como usar o método **CompressImage** para reduzir o tamanho de uma imagem em uma apresentação definindo uma resolução alvo e removendo áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Comprime a imagem com uma resolução alvo de 150 DPI (resolução Web) e remove áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) método

Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Se verdadeiro, o método removerá as áreas recortadas da imagem, reduzindo ainda mais seu tamanho. |
| resolution | **float** | A resolução alvo em DPI. Esse valor deve ser positivo e define como a imagem será redimensionada. |

### Valor de Retorno

Um **bool** indicando se a imagem foi comprimida com sucesso. Retorna ****true****

## Observações

Este método altera o tamanho e a resolução da imagem de forma semelhante ao recurso "Formato da Imagem -> Comprimir Imagens" do PowerPoint.

se a imagem foi redimensionada ou recortada, caso contrário ****false****

. 

O exemplo a seguir demonstra como usar o método **CompressImage** para reduzir o tamanho de uma imagem em uma apresentação definindo uma resolução alvo e removendo áreas recortadas: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Comprime a imagem com uma resolução alvo de 150 DPI (resolução Web) e remove áreas recortadas
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Resolução Web
```

## Veja Também

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)