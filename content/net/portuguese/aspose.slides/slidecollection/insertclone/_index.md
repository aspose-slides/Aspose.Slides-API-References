---
title: InsertClone
second_title: Aspose.Sildes para referência da API .NET
description: Insere uma cópia de um slide especificado na posição especificada da coleção.
type: docs
weight: 120
url: /pt/aspose.slides/slidecollection/insertclone/
---
## InsertClone(int, ISlide) {#insertclone}

Insere uma cópia de um slide especificado na posição especificada da coleção.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Índice do novo slide. |
| sourceSlide | ISlide | Slide a ser clonado. |

### Valor de retorno

Slide inserido.

### Observações

Quando clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente para evitar a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use [`InsertClone`](../insertclone) ou [`InsertClone`](../insertclone) para clonar slides e [`AddClone`](../../imasterslidecollection/addclone) para clonar mestres.

### Exemplos

O exemplo a seguir mostra como clonar em outra posição dentro de Presentation.

```csharp
[C#]
// Instanciar a classe Presentation que representa um arquivo de apresentação
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Clonar o slide desejado para o final da coleção de slides na mesma apresentação
    ISlideCollection slds = pres.Slides;
    // Clonar o slide desejado para o índice especificado na mesma apresentação
    slds.InsertClone(2, pres.Slides[1]);
    // Gravar a apresentação modificada no disco
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

O exemplo a seguir mostra como clonar em outra posição dentro de Presentation.

```csharp
[C#]
// Instanciar a classe Presentation para carregar o arquivo de apresentação de origem
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instanciar a classe Presentation para o PPTX de destino (onde o slide será clonado)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Gravar a apresentação de destino no disco
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Insere uma cópia de um slide especificado na posição especificada da coleção.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Índice do novo slide. |
| sourceSlide | ISlide | Slide a ser clonado. |
| destLayout | ILayoutSlide | Slide de layout para o novo slide. |

### Valor de retorno

Slide inserido.

### Veja Também

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Insere uma cópia de um slide de origem especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do layout do slide de origem). Se não houver layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Índice do novo slide. |
| sourceSlide | ISlide | Slide a ser clonado. |
| destMaster | IMasterSlide | Slide mestre para o novo slide. |
| allowCloneMissingLayout | Boolean | Se não houver layout apropriado no mestre especificado, o layout do slide de origem será clonado (se allowCloneMissingLayout for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout for false). |

### Valor de retorno

Slide inserido.

### Exceções

| exceção | condição |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lançada se não houver layout apropriado no mestre especificado e allowCloneMissingLayout for false. |

### Veja Também

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->