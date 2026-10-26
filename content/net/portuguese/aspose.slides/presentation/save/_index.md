---
title: Save
second_title: Aspose.Sildes para .NET Referência da API
description: Salva todos os slides de uma apresentação em um arquivo com o formato especificado.
type: docs
weight: 390
url: /pt/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Salva todos os slides de uma apresentação em um arquivo com o formato especificado.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| format | SaveFormat | Formato dos dados exportados. |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Salva todos os slides de uma apresentação em um fluxo no formato especificado.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| format | SaveFormat | Formato dos dados exportados. |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Exceções

| Exceção | Condição |
| --- | --- |
| NotSupportedException | Se você tentar salvar um arquivo criptografado em um formato que não seja Office 2007-2010 |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Salva todos os slides de uma apresentação em um conjunto de arquivos que representam a marcação XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | IXamlOptions | As opções de formato XAML. |

### Exemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Veja também

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Salva os slides especificados de uma apresentação em um arquivo com o formato especificado, preservando a numeração das páginas.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| slides | Int32[] | Array com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |

### Exceções

| Exceção | Condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Salva os slides especificados de uma apresentação em um arquivo com o formato especificado, preservando a numeração das páginas.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| slides | Int32[] | Array com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Salva os slides especificados de uma apresentação em um fluxo no formato especificado, preservando a numeração das páginas.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| slides | Int32[] | Array com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Salva os slides especificados de uma apresentação em um fluxo no formato especificado, preservando a numeração das páginas.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| slides | Int32[] | Array com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Exceções

| Exceção | Condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Exemplos

O exemplo a seguir mostra como converter PowerPoint para PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

O exemplo a seguir mostra como converter PowerPoint para PNG com dimensões personalizadas.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

O exemplo a seguir mostra como converter PowerPoint para PNG com tamanho personalizado.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### Veja também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->