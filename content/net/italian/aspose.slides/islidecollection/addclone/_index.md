---
title: AddClone
second_title: Riferimento API Aspose.Sildes per .NET
description: Aggiunge una copia di una diapositiva specificata alla fine della raccolta.
type: docs
weight: 20
url: /it/aspose.slides/islidecollection/addclone/
---
## AddClone(ISlide) {#addclone}

Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |

### Valore restituito

Nuova diapositiva.

### Osservazioni

Durante la clonazione di una diapositiva tra presentazioni diverse, anche il master della diapositiva può essere clonato. Un registro interno viene utilizzato per tenere traccia dei master clonati automaticamente, evitando la creazione di più cloni dello stesso master. La clonazione manuale dei master non sarà né impedita né registrata. Se è necessario un maggiore controllo sul processo di clonazione, utilizzare [`AddClone`](../addclone) o [`AddClone`](../addclone) per clonare le diapositive, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone) per clonare i layout e [`AddClone`](../../imasterslidecollection/addclone) per clonare i master.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| section | ISection | Sezione per la nuova diapositiva. |

### Valore restituito

Nuova diapositiva.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Esempi

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Ora la seconda sezione contiene una copia della prima diapositiva.
}
```

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ISection](../../isection)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destLayout | ILayoutSlide | Layout della diapositiva per una nuova diapositiva. |

### Valore restituito

Nuova diapositiva.

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [ILayoutSlide](../../ilayoutslide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. Il layout appropriato sarà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva da clonare. |
| destMaster | IMasterSlide | Master slide per una nuova diapositiva. |
| allowCloneMissingLayout | Boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

### Valore restituito

Nuova diapositiva.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Sollevata se non esiste un layout appropriato nel master specificato e allowCloneMissingLayout è false. |

### Vedi anche

* interfaccia [ISlide](../../islide)
* interfaccia [IMasterSlide](../../imasterslide)
* interfaccia [ISlideCollection](../../islidecollection)
* spazio dei nomi [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->