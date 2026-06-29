---
title: GetImage
second_title: Aspose.Sildes para .NET - Referência da API
description: Retorna um objeto Thumbnail Image com dimensionamento personalizado.
type: docs
weight: 80
url: /pt/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Retorna um objeto Thumbnail Image com dimensionamento personalizado.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleX | Single | O valor pelo qual dimensionar esta Thumbnail na direção do eixo x. |
| scaleY | Single | O valor pelo qual dimensionar esta Thumbnail na direção do eixo y. |

### Valor de retorno

objeto IImage.

### Exemplos

O exemplo a seguir mostra como gerar miniaturas a partir de PowerPoint Presentation.

```csharp
[C#]
// Instancie a classe Presentation que representa o arquivo de apresentação
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Acesse o primeiro slide
    ISlide sld = pres.Slides[0];
    // Crie uma imagem em escala total
    IImage bmp = sld.GetImage(1f, 1f);
    // Salve a imagem no disco no formato JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

O exemplo a seguir mostra como converter slides em bitmap e salvar as imagens em PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converte o primeiro slide da apresentação em um objeto Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Salva a imagem no formato PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

O exemplo a seguir mostra como converter PowerPoint PPT/PPTX para JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Crie uma imagem em escala total
		IImage bmp = sld.GetImage(1f, 1f);
		// Salve a imagem no disco no formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

O exemplo a seguir mostra como converter PowerPoint PPT/PPTX para JPG com dimensões personalizadas.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Defina as dimensões
	int desiredX = 1200;
	int desiredY = 800;
	// Obtenha os valores escalados de X e Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Crie uma imagem em escala total
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Salve a imagem no disco no formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Veja também

* interface [IImage](../../iimage)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Retorna um objeto Thumbnail Image (20% do tamanho real).

```csharp
public IImage GetImage()
```

### Veja também

* interface [IImage](../../iimage)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Retorna um objeto Thumbnail Image com tamanho especificado.

```csharp
public IImage GetImage(Size imageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSize | Size | Tamanho da imagem a ser criada. |

### Valor de retorno

objeto Image.

### Exemplos

O exemplo a seguir mostra como converter slides em imagens com tamanhos personalizados usando C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converte o primeiro slide da apresentação em um Bitmap com o tamanho especificado
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Salva a imagem no formato JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Veja também

* interface [IImage](../../iimage)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Retorna um objeto Thumbnail tiff Image com parâmetros especificados.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | ITiffOptions | Opções tiff. |

### Valor de retorno

objeto Image.

### Exceções

| exceção | condição |
| --- | --- |
| InvalidOperationException | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition recebe o valor NotesPositions.BottomFull. |

### Veja também

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Retorna um objeto Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | IRenderingOptions | Opções de renderização. |

### Valor de retorno

objeto Image.

### Exceções

| exceção | condição |
| --- | --- |
| InvalidOperationException | Lançada quando notesCommentsLayouting.NotesPosition recebe o valor NotesPositions.BottomFull |

### Veja também

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Retorna um objeto Thumbnail Image com dimensionamento personalizado.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | IRenderingOptions | Opções de renderização. |
| scaleX | Single | O valor pelo qual dimensionar esta Thumbnail na direção do eixo x. |
| scaleY | Single | O valor pelo qual dimensionar esta Thumbnail na direção do eixo y. |

### Valor de retorno

objetos Bitmap.

### Exceções

| exceção | condição |
| --- | --- |
| InvalidOperationException | Lançada quando notesCommentsLayouting.NotesPosition recebe o valor NotesPositions.BottomFull |

### Exemplos

O exemplo a seguir mostra como converter slides com notas e comentários em Imagens usando C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Crie as opções de renderização
    IRenderingOptions options = new RenderingOptions();
    // Crie as opções de layout de notas e comentários
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Define a posição das notas na página
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Define a posição dos comentários na página
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Define a largura da área de saída de comentários
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Define a cor da área de comentários
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Defina as opções de layout para renderização
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Converte o primeiro slide da apresentação em um objeto IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Salva a imagem no formato GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Veja também

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Retorna um objeto Thumbnail Image com tamanho especificado.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | IRenderingOptions | Opções de renderização. |
| imageSize | Size | Tamanho da imagem a ser criada. |

### Valor de retorno

objeto Image.

### Exceções

| exceção | condição |
| --- | --- |
| InvalidOperationException | Lançada quando options.SlideLayoutOption é NotesCommentsLayoutingOptions e sua propriedade NotesPosition recebe o valor NotesPositions.BottomFull. |

### Veja também

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->