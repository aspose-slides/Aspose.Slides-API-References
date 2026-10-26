---
title: GetImage()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um objeto Thumbnail Image com dimensionamento personalizado.
type: docs
weight: 144
url: /pt/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) método


Retorna um objeto Thumbnail Image com dimensionamento personalizado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleX | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |

### Valor de Retorno

[IImage](../../iimage/) objeto.

## Observações



O exemplo a seguir mostra como gerar thumbnails a partir do PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
 O exemplo a seguir mostra como converter slides em bitmap e salvar as imagens em PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converts the first slide in the presentation to a Bitmap object
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Saves the image in the PNG format
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
 O exemplo a seguir mostra como converter PowerPoint PPT/PPTX para JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Cria uma imagem em escala completa
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Salva a imagem no disco no formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
 O exemplo a seguir mostra como converter PowerPoint PPT/PPTX para JPG com dimensões personalizadas: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Defina dimensões
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Obtenha valores escalados de X e Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Crie uma imagem em escala completa
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Salve a imagem no disco no formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() método


Retorna um objeto Thumbnail Image (20% do tamanho real).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) método


Retorna um objeto Thumbnail Image com tamanho especificado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Image objeto.

## Observações



O exemplo a seguir mostra como converter slides em imagens com tamanhos personalizados usando C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Converte o primeiro slide da apresentação em um Bitmap com o tamanho especificado
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Salva a imagem no formato JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) método


Retorna um objeto Thumbnail tiff image com parâmetros especificados.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opções Tiff. |

### Valor de Retorno

Image objeto.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) método


Retorna um objeto Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |

### Valor de Retorno

Image objeto.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método


Retorna um objeto Thumbnail Image com dimensionamento personalizado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| scaleX | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scaleY | **float** | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |

### Valor de Retorno

Objetos Bitmap.

## Observações



O exemplo a seguir mostra como converter slides com notas e comentários para [Images](../../images/) usando C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Cria as opções de renderização
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Cria opções de layout de notas e comentários
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Define a posição das notas na página
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Define a posição dos comentários na página
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Define a largura da área de saída dos comentários
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Define a cor da área de comentários
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Define opções de layout para renderização
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Converte o primeiro slide da apresentação em um objeto IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Salva a imagem no formato GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método


Retorna um objeto Thumbnail Image com tamanho especificado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opções de renderização. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamanho da imagem a ser criada. |

### Valor de Retorno

Image objeto.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)