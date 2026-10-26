---
title: Save
second_title: Referência da API Aspose.Sildes para .NET
description: Salva todos os slides de uma apresentação em um arquivo com o formato especificado.
type: docs
weight: 380
url: /pt/aspose.slides/ipresentation/save/
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

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
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

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
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

| exceção | condição |
| --- | --- |
| NotSupportedException | Se tentar salvar um arquivo criptografado em um formato que não seja Office 2007-2010 |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Salva slides específicos de uma apresentação em um arquivo com o formato especificado.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| slides | Int32[] | Vetor com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Salva slides específicos de uma apresentação em um arquivo com o formato especificado.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | String | Caminho para o arquivo criado. |
| slides | Int32[] | Vetor com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Salva slides específicos de uma apresentação em um fluxo no formato especificado.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| slides | Int32[] | Vetor com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Salva slides específicos de uma apresentação em um fluxo no formato especificado.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | Stream | Fluxo de saída. |
| slides | Int32[] | Vetor com as posições dos slides, começando em 1. |
| format | SaveFormat | Formato dos dados exportados. |
| options | ISaveOptions | Opções de formato adicionais. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Quando o parâmetro stream ou slides for nulo. |
| ArgumentOutOfRangeException | Quando o parâmetro slides contiver números de página incorretos. |
| InvalidOperationException | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Veja Também

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
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

### Veja Também

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->